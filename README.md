# Einführung in künstliche Intelligenz und Machine Learning

Das Hauptziel dieser Veranstaltung ist **💪ENABLING💪**. D.h. Sie sollen am Ende des Semesters etwas möglicherweise/hoffentlich nützliches können. Um dieses Ziel in der knappen zur Verfügung stehenden Zeit zu erreichen, werden Sie an der ein oder anderen Stelle ins kalte Wasser geworfen — schwimmen 🏊‍♀️ Sie los!

In Bezug auf maschinelles Lernen brauchen wir, um etwas nützliches bewerkstelligen zu können insbesondere
- ein paar grundlegende Überlegungen zum "Lernen" an sich;
- ein paar mathematische Überlegungen;
- eine grobe Vorstellung, wie Algorithmen funktionieren;
- ein paar grundlegende Programmierkenntnisse;
- eine benutzerfreundliche Software-Bibliothek, in der ML-Methoden professionell implementiert sind.

Um Ihre Erwartungen zu managen: Nein, Sie werden in diesem Kurs in keinem der genannten Gebiete Profis! Nein, wir legen nirgends ein solides Fundament, auf das man mühelos beliebig hoch aufbauen kann. Aber: Sie lernen alles um direkt loslegen zu können 😎.

## Literatur
Im Rahmen dieser Veranstaltung empfehle ich insbesondere folgende Werke:
- Géron, Hands-on machine learning with Scikit-Learn & TensorFlow, O’Reilly (2022) — [Jupyter Notebooks](https://github.com/ageron/handson-ml3) verfügbar
- Goodfellow, Deep Learning (Adaptive Computation and Machine Learning), MIT Press (2016) — DAS einführende Standardwerk zu Deep Learning, [im Volltext verfügbar](http://www.deeplearningbook.org)
- VanderPlas, Python Data Science Handbook, O'Reilly — sehr intuitive Darstellung einiger Algorithmen, [im Volltext verfügbar](https://jakevdp.github.io/PythonDataScienceHandbook/)
- Shalev-Schwartz, Ben-David, Understanding Machine Learning, Cambridge University Press, 2014 — genaue Einführung in die Thematik inkl. Lerntheorie und genauen Hintergründen der Algorithmen, [im Volltext verfügbar](https://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning)

## Woche 1
In der Einführung besprechen wir:
- Verhältnis verschiedener relevanter Begriffe zueinander
- Was ist "Lernen"?
- Definition(en) vom Machine Learning
- Wann ist ML sinnvoll?
- Arten von ML
- ERM ("Empirical Risk Minimization") Prinzip
- Overfitting

Die entsprechenden Notizen finden Sie im [OneNote Notebook][onenote].

❗ Um insbesondere die Themen ERM und Overfitting zu vertiefen und ein Gefühl dafür zu vermitteln, dass all diese Themen auf einem soliden mathematischen Fundament stehen, arbeiten Sie bitte Kapitel 2 "A gentle start" von [Understanding Machine Learning](https://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning/understanding-machine-learning-theory-algorithms.pdf) durch. Wir werden dies nächste Woche besprechen.   

Im Praktikum gebe ich außerdem einen Crash-Kurs in Python. Im Rahmen dessen werde ich auch Googles Cloud-Computing Umgebung [Colab](https://colab.research.google.com/) kurz präsentieren. Das entsprechende [Jupyter Notebook](Tutorials/python_tutorial.ipynb) stammt aus dem Kurs [CS231n](http://cs231n.stanford.edu/).

## Woche 2
Diese Woche betrachten wir 
- ein erstes Beispiel, welches gem. der Definition von Mitchell (vgl. erste Vorlesung) als "maschinelles Lernen" bezeichnet werden kann: die **lineare Regression**. Wir begründen, warum lineare Regression eine (einfache) Methode des maschinellen Lernens ist und betrachten ein ganz [konkretes Beispiel](Vorlesung/01_lin_reg.ipynb).
- die strukturierte [Darstellung von Daten](Vorlesung/02.01_Ausgangspunkt_Daten.ipynb). Wir stellen insbesondere Überlegungen an zur grafischen Darstellung von Daten und warum das so wichtig ist.
- das Software-Tool, welches wir für die Veranstaltung nutzen werden: [Scikit-Learn](https://scikit-learn.org/)
Wir betrachten, wie Daten typischerweise dargestellt werden und sprechen die wesentlichen Elemente der Estimator API durch. Das Prinzip ist knapp im [OneNote Notebook][onenote] dargestellt, als erstes Beispiel für die systematische Anwendung der API im Rahmen einer *supervised learning* Aufgabe betrachten wir eine [einfache lineare Regression](Vorlesung/02.02_API_supervised.ipynb).

Um Scikit-Learn nutzen zu können, können Sie (u.a.)
- die kostenfreie Cloudplattform [Google Colab](https://colab.research.google.com/) verwenden;
- Python und Scikit-Learn lokal auf Ihrem Rechner installieren. Eine einfache Möglichkeit ist die Installation von [Anaconda](https://www.anaconda.com/), als Editor bzw. IDE empfehle ich [VSCode](https://code.visualstudio.com/).
Für den leichten und problemfreien Einstieg rate ich zur ersten Option.


Um für dieses umfangreiche Programm ausreichend Zeit zu haben, werden wir auch einen Teil der Praktikumsstunde ab 11:45 Uhr nutzen. Ein Praktikum im eigentlichen Sinne findet aber diese Woche noch nicht statt. Alle Inhalte finden Sie auch online, die Videos sind im OneNote verlinkt.

## Woche 3
Diese Woche arbeiten wir weiter mit der Estimator API von Scikit-Learn, konkret betrachten wir ein noch ausstehendes Beispiel zu *unsupervised learning*:

Wir wollen die Iris-Daten clustern, sprich die vorhandenen Daten in drei Gruppen aufteilen, ohne dass wir spezifizieren, wie diese Gruppen ("Cluster") aussehen. Bevor wir das machen, wollen wir erst einmal einen Eindruck bekommen, ob ein solches Clustering überhaupt vielversprechend ist, d.h. ob wir erwarten dürfen, dass die erzeugten Cluster mit den real vorliegenden unterschiedlichen Spezies übereinstimmen. Dazu führen wir eine Dimensionsreduktion mittels PCA ("Principal Component Analysis", Details in einer späteren Vorlesung) durch, die ursprünglich vierdimensionalen Iris-Daten sollen auf die wesentlichen zwei Dimensionen reduziert werden. Die so aufbereiteten Daten können wir dann visuell untersuchen. Dieses Beispiel finden Sie in [diesem Notebook](Vorlesung/02.03_API_unsupervised.ipynb). 
 

Wir untersuchen auch die Frage, welche Fehler bei einem ML Model relevant sind und wie Modelle bewertet werden können, siehe [OneNote][onenote] Kapitel 3 und 3.1. Diese Überlegungen setzen wir dann wieder im Iris-Beispiel um, siehe [Notebook](Vorlesung/03.01_Accuracy.ipynb).
 
### Praktikum
Im Praktikum werden diese Inhalte anhand verschiedener Clustering-Algorithmen u.a. am Beispiel der Iris-Daten vertieft. Die Aufgabenstellung des Praktikums finden Sie (inkl. Erläuterung per Video) in unten stehendem Notebook. Auch einen Lösungsvorschlag (inkl. Erläuterung per Video) finden Sie unten.
- [Aufgabenstellung](Praktikum/Pr1_Clustering_blank.ipynb)
- [Lösungsvorschlag](Praktikum/Pr1_Clustering_sol.ipynb) 
 
**Somit können Sie auch das Praktikum ggf. rein online absolvieren (hier bietet es sich vielleicht noch mehr an als beim Vorlesungsteil).**

Ich rate Ihnen, wirklich zu versuchen, die Aufgaben zu lösen OHNE in den Lösungsvorschlag zu schauen. Nutzen Sie gerne alle anderen verfügbaren Quellen, insbesondere auch die Suchmaschine Ihrer Wahl und die [Scikit-Learn Dokumentation][sklearn_user_guide]. So lernen Sie, mit immer verfügbaren Quellen Aufgaben zu lösen - das ist aus meiner Sicht ein wesentliches Ziel der Veranstaltung!


[onenote]: https://1drv.ms/u/s!AhdJTnngugIpjTsnJWCmXJsxpBf3?e=6de34K
[sklearn_user_guide]: https://scikit-learn.org/stable/user_guide.html