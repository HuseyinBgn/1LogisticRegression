Name des Projekts:	Logistische Regression

Link zum MyBinder: 	[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/HuseyinBgn/1LogisticRegression/HEAD)

Doku:	

Die Beispiele der Übungsaufgabe befinden sich in dem Logistische_Regression.ipynb Datei.
Die erwarteten Ergebnisse sind unterhalb der jeweiligen Befehle dargestellt. 

Hinweis: Um das erwartete Ergebnis nicht zu verlieren wird empfohlen eine Zwischenzeile zw. dem Befehl 
und dem bereits stehendem Ergebnis hinzufügen bevor das Befehl ausgeführt wird!

Zum Ausführen der einzelnen Code-Zeilen "STRG" + "Enter" Tasten drücken.
Beachten Sie keine der Zeilen zu überspringen, denn sonst kann es zu Fehlerhaften Ausführung führen.

1. Libraries installieren & importieren: 
- Librairies für die Datenverarbeitung und -visualisierung werden installiert und anschließend importiert.

2. Die Daten:
- Advertising.csv Datei wird gelesen.
- Mit head(), info() und describe() Methoden wird auf die Korrektheit und Darstellung der Tabelle überprüft.

3. Explorative Datenanalyse:
- Ein Histogram von "Age". 
- Ein Jointplot, das den "Area Income" mit "Age" vergleicht.
- Ein Jointplot mit KDE Verteilung, der den "Daily Time Spent on Time" mit "Age" vergleicht.
- Ein weiteres Jointplot mit grüner Farbe, diesmal ein Vergleich zw. "Daily Time Spent on Time" und "Age".
- Pair Plot von "Clicked on Ad".

4. Logistische Regression:
- Die Daten werden in Trainings und Testset aufgeteilt.
- Anschließend wird das Regressionsmodell mit Trainingsdaten trainiert. Dies geschieht mit fit() Methode.

5. Vorhersagen und Auswertung
- Das Regressionsmodel soll mit Testdaten durch Nutzung von predict() Methode Vorhersagen. 
- Ein Klassifizierungsreport für das Model wird erstellt.