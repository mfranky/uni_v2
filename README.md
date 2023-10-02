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
---

<!-- ## Woche 13
Aus mehrfachen Wunsch hin findet die letzte Veranstaltung des Semesters [online](https://hm-edu.zoom.us/j/66727078430?pwd=WjMzWC9ZWStuci9hdHJ0MXkyZGxtQT09) statt. Wir betrachten eine knappe Einführung in neuronale Netze. Die Notizen dazu finden Sie im [OneNote-Dokument][onenote]. 

Außerdem können Fragen im Umfeld der Studienarbeiten besprochen werden.

### Praktikum
[TensorFlow Playground](https://playground.tensorflow.org/) stellt eine direkt zugängliche, einfache und intuitive Umgebung bereit, um mit neuronalen Netzen sehr einfach zu experimentieren. Eine Anleitung, wie Sie damit die Funktionsweise neuronaler Netze strukturiert erkunden können, finden Sie [hier](Praktikum/Pr9_TF_Playground.html).

---
## Woche 12
Diese Woche betrachten wir nach PCA ein weiteres Verfahren der Klasse *unsupervised*. Konkret geht es darum, vorliegende Daten in Cluster aufzuteilen. Ein intuitiv sehr gut zugängliches Verfahren (wir hatten es zu Beginn des Semesters schon mal kurz angerissen) ist [k-Means](Vorlesung/04.06_k-Means_GMM.ipynb). Einen sehr guten Überblick über die prinzipiellen Probleme der Aufgabenstellen *Clustern* finden Sie in Kap. 22 von *Understanding Machine Learning*. Auch der Zusammenhang zu graphentheoretischen Problemen wird dort deutlich gemacht.
Um gewisse Probleme von k-Means zu umgehen, betrachten wir außerdem noch sog. Gaussian Mixture Models (GMMs). 

### Praktikum
Diese Woche gibt es keine neue Praktikumsaufgabe. Stattdessen findet wie angekündigt die Präsentation einer Projektarbeit statt, bei der vier Studenten einen automatischen Logger entwickelt haben, der mit einer Kamera Messinstrumente abließt, diese durch ML-Methoden interpretiert und protokolliert.
Auch auf mögliche Fragen zu den Themen der Studienarbeit werden wir eingehen.

---

## Woche 11
**WICHTIG:** Diese Woche findet **keine** Präsenzveranstaltung statt.

Ich bitte Sie, das Thema [Principal Component Analysis (PCA)](Vorlesung/04.05_PCA.ipynb) anhand des Notebooks und des darin verlinkten Videos zu erarbeiten. Anschließend stehe ich Ihnen ab 11:45 Uhr via [Zoom](https://hm-edu.zoom.us/j/69101999484?pwd=RkZFWU5Ic1l6U3VINEpvZmxMZGhuQT09) für Fragen bzw. zur Diskussion des Themas zur Verfügung.

### Praktikum
Auf mehrfache Anregung hin stelle ich Ihnen diese Woche Zeit zur Verfügung, um das zugegebenermaßen sehr umfangreiche [Praktikum 7 (End-to-end ML project)](Praktikum/Pr7_End_to_end_ML_project.ipynb) weiter zu bearbeiten. Dies ist eine optimale Vorbereitung für die Studienarbeit, deren Themen nächste Woche gestellt werden.

---

## Woche 10
Wir ergänzen das Beispiel "Gesichtserkennung" zu den SVMs.
Danach besprechen wir [Entscheidungsbäume](Vorlesung/04.04_Random_Forests.ipynb) (*Decision Trees*) und darauf aufbauend - anhand des *Bagging* Prinzips - die sog. *Random Forests*. In diesem Zusammenhang betrachten wir sowohl Klassifizierungs- als auch Regressionsprobleme.

### Praktikum
Im Praktikum versuchen wir uns anhand der berühmten [MNIST-Daten](http://yann.lecun.com/exdb/mnist/) eine Multiclass-Klassifizierung zu meistern. Wir erstellen dazu ein Ensemble von verschiedenen Methoden und verwenden Hard- und Soft-Voting. Damit werden wir einen Genauigkeit von knapp 97% erzielen können.
- [Aufgabenstellung](Praktikum/Pr8_MNIST_blank.ipynb)
- [Lösungsvorschlag](Praktikum/Pr8_MNIST_sol.ipynb)

---

## Woche 9
Wir besprechen [Support Vector Machines](Vorlesung/04.03_SVM.ipynb) und beleuchten knapp das Konzept der Datenanreicherung bzw. den "Kernel-Trick".

### Praktkikum
In dieser Session sollen Sie die Möglichkeit bekommen, ein komplettes Machine Learning Projekt von Anfang bis Ende durchzuführen. Dazu verwenden wir das sehr gut beschriebene Beispiel einer Regressionsanalyse von Immobilienpreisen aus dem Buch *Hands-on machine learning with Scikit-Learn, Keras & TensorFlow von A. Géron*. Eine Kopie eines Großteils des *Chapter 2 – End-to-end Machine Learning project* finden Sie bei [hier](Praktikum/Geron%20-%20Hands-on-ML%20chap_2.pdf). 
Ziel ist es, dass Sie dieses Projekt durcharbeiten/nachvollziehen um sich speziell auf Ihr eigenes Projekt im Rahmen der Studienarbeit vorzubereiten bzw. um dafür eine weitere Referenz zu haben.
- [Beschreibung: Chapter 2 – End-to-end Machine Learning project](Praktikum/Geron%20-%20Hands-on-ML%20chap_2.pdf)
- [Zugehöriges Jupyter Notebook](Praktikum/Pr7_End_to_end_ML_project.ipynb)
---

## Woche 8
Wir besprechen [lineare Modelle](Vorlesung/04.02_Lineare_Modelle.ipynb) allgemein und erläutern daran verschiedene Möglichkeiten zur Regularisierung. Konkret betrachten wir *Ridge* und *Lasso*, d.h. die $`L_2`$ und $`L_1`$ Regularisierung. Außerdem betrachten wir, wie Multi-Class Klassifizierung funktioniert.

### Praktikum
Wir setzen das Praktikum der letzen Woche fort. Zuerst versuchen wir, die vorleigenden Daten besser zu treffen. Im zweiten Teil erstellen wir ein Vorhersagemodell, welches basierend auf historischen Daten den Fahrradverkehr auf der Fremont Bridge vorhersagen kann.
- [Aufgabenstellung](Praktikum/Pr6_Lineare_Modelle_blank.ipynb)
- [Lösungsvorschlag](Praktikum/Pr5_6_Lineare_Modelle_sol.ipynb)
---

## Woche 7
Diese Woche nehmen wir uns bewusst weniger vor um Zeit für ausführliche Diskussionen und das Praktikum zu haben. Wir besprechen detaillierter die Klasse der [Naive Bayes Modelle](Vorlesung/04.01_Naive_Bayes.ipynb).

Die Naive Bayes Modelle haben wir komplett besprochen.

### Praktikum
Wir bauen ein (lineares) Modell, dass den Fahrradverkehr über die [Fremont Bridge in Seattle](https://en.wikipedia.org/wiki/Fremont_Bridge_(Seattle)) modelliert. Datenaufbereitung, Erzeugung von Features und Hinzufügen weiterer Daten stehen hier im Mittelpunkt.
- [Aufgabenstellung](Praktikum/Pr5_Lineare_Modelle_blank.ipynb)
- [Lösungsvorschlag](Praktikum/Pr5_Lineare_Modelle_sol.ipynb)
---

## Woche 6
Wir besprechen den wichtigen Aspekt, aus vorliegenden Daten neue Features zu generieren, siehe Abschnitt "Abgeleitete Features" im [Notebook](Vorlesung/03.03_Feature_Eng.ipynb).

Außerdem starten betrachten wir eine erste Modellklasse detaillierter: [Naive Bayes](Vorlesung/04.01_Naive_Bayes.ipynb)
Hiervon haben wir das allgemeine Prinzip behandelt, das Kapitel "Gaussian Naive Bayes" starten wir nächste Woche.

### Praktikum
Im Praktikum behandeln wir die in der Machine Learning Welt sehr populäre "Titanic-Challenge". Aus den Personendaten der einzelnen Passagiere der Titanic soll vorhergesagt werden, wer die Schiffskatastrophe überlebt:
- [Aufgabenstellung](Praktikum/Pr4_Titanic_blank.ipynb)
- [Lösungsvorschlag](Praktikum/Pr4_Titanic_sol.ipynb)
---
## Woche 5
Wir führen die Überlegungen zur Modellwahl von letzter Woche fort. Insbesondere betrachten wir die Abhängigkeit der Modellperformance von der  Kapazität des Modells durch sog. Validierungskurven. Anschließend untersuchen wir die Auswirkung der Menge der Trainingsdaten mit Hilfe von Trainingskurven, siehe [Notebook](Vorlesung/03.02_Modellwahl.ipynb).

Außerdem beginnen wir mit dem wichtigen Thema *Feature Engineering*. Damit ist gemeint, dass aus vorliegenden Daten erst einmal Features abgeleitet werden, bevor diese dann als Input für ML-Modelle verwendet werden können. Dies ist offensichtlich nötig, wenn der Input z.B. aus kategorischen Daten oder aus Text besteht, siehe [Notebook](Vorlesung/03.03_Feature_Eng.ipynb). Das Kapitel "Abgeleitete Features" besprechen wir nächste Woche.

### Praktikum
Im Praktikum behandeln wir Cross Validation, um für unterschiedliche Modell die optimalen Hyperparameter zu bestimmen:
- [Aufgabenstellung](Praktikum/Pr3_CrossVal_GridSearch_blank.ipynb)
- [Lösungsvorschlag](Praktikum/Pr3_CrossVal_GridSearch_sol.ipynb)

---

## Woche 4
Wir vertiefen die Überlungen zur Modellbewertung der letzten Woche durch eine konkrete Anwendung auf das Iris-Beispiel um, siehe [Notebook](Vorlesung/03.01_Accuracy.ipynb). Eine mit der Modellbewertung eng verwandte Fragestellung ist die der Modellwahl: *Wenn die Performance des Modells nicht befriedigend ist, was kann unternommen werden?*
Prinzipiell kann ein komplexeres (oder ein weniger komplexes) Modell verwendet werden und es können mehr (oder weniger) Daten eingesetzt werden. Die weitere (und sehr wichtige) Möglichkeit, andere Features zu verwenden, klammern wir für die Betrachtung diese Woche noch aus.

Detailliert untersuchen wir mit Hilfe von Validierungskurven die Abhängigkeit der Modellperformance von der gegebenen Kapazität des Modells, siehe [Notebook](Vorlesung/03.02_Modellwahl.ipynb).

### Praktikum
Im Praktikum geht es um die Erkennung handschriftlicher Ziffern. Die Daten sollen mit Hilfe von Dimensionsreduktion zuerst untersucht werden, um ein Gefühl dafür zu bekommen, wie kompliziert eine derartige Klassifizierungsaufgabe wohl ist. Zur Modellvalidierung soll Cross Validation verwendet werden. Als Zusatz wird der Aspekt der "Stratification", also der "statistischen Ausbalancierung" angesprochen.

- [Aufgabenstellung](Praktikum/Pr2_handwritten_digits_blank.ipynb)
- [Lösungsvorschlag](Praktikum/Pr2_handwritten_digits_sol.ipynb) 
---
## Woche 3
Diese Woche arbeiten wir weiter mit der Estimator API von Scikit-Learn, konkret betrachten wir ein noch ausstehendes Beispiel zu *unsupervised learning*:

Wir wollen die Iris-Daten clustern, sprich die vorhandenen Daten in drei Gruppen aufteilen, ohne dass wir spezifizieren, wie diese Gruppen ("Cluster") aussehen. Bevor wir das machen, wollen wir erst einmal einen Eindruck bekommen, ob ein solches Clustering überhaupt vielversprechend ist, d.h. ob wir erwarten dürfen, dass die erzeugten Cluster mit den real vorliegenden unterschiedlichen Spezies übereinstimmen. Dazu führen wir eine Dimensionsreduktion mittels PCA ("Principal Component Analysis", Details in einer späteren Vorlesung) durch, die ursprünglich vierdimensionalen Iris-Daten sollen auf die wesentlichen zwei Dimensionen reduziert werden. Die so aufbereiteten Daten können wir dann visuell untersuchen. Dieses Beispiel finden Sie in [diesem Notebook](Vorlesung/02.03_API_unsupervised.ipynb). 
 

Wir untersuchen auch die Frage, welche Fehler bei einem ML Model relevant sind und wie Modelle bewertet werden können, siehe [OneNote][onenote] Kapitel 3 und 3.1. Diese Überlegungen setzen vertiefen wir nächste Woche in einem Beispiel mit den Iris-Daten. 
 
### Praktikum
Im Praktikum werden diese Inhalte anhand verschiedener Clustering-Algorithmen u.a. am Beispiel der Iris-Daten vertieft. Die Aufgabenstellung des Praktikums finden Sie (inkl. Erläuterung per Video) in unten stehendem Notebook. Auch einen Lösungsvorschlag (inkl. Erläuterung per Video) finden Sie unten.
- [Aufgabenstellung](Praktikum/Pr1_Clustering_blank.ipynb)
- [Lösungsvorschlag](Praktikum/Pr1_Clustering_sol.ipynb) 
 
**Somit können Sie auch das Praktikum ggf. rein online absolvieren (hier bietet es sich vielleicht noch mehr an als beim Vorlesungsteil).**

Ich rate Ihnen, wirklich zu versuchen, die Aufgaben zu lösen OHNE in den Lösungsvorschlag zu schauen. Nutzen Sie gerne alle anderen verfügbaren Quellen, insbesondere auch die Suchmaschine Ihrer Wahl und die [Scikit-Learn Dokumentation][sklearn_user_guide]. So lernen Sie, mit immer verfügbaren Quellen Aufgaben zu lösen - das ist aus meiner Sicht ein wesentliches Ziel der Veranstaltung!

---
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

Wie erwähnt findet heute um 15 Uhr ein möglicherweise für Sie interessantes Kolloquium unseres Masterstudiengangs Computationa Engineering statt, gerne können Sie [hier](https://hm-edu.zoom.us/j/65474372368?pwd=WjhicDdqalRaQW5OTnltR0E1eWx6dz09) beitreten.

--- -->

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




[onenote]: https://1drv.ms/o/s!AhdJTnngugIpjTspCZMn58QtIXnt?e=TKQbVN
[sklearn_user_guide]: https://scikit-learn.org/stable/user_guide.html