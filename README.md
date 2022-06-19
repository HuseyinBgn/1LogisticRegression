Name des Projekts:	Logistische Regression

Link zum MyBinder: 	https://github.com/HuseyinBgn/1LogisticRegression

Doku:	

Die Beispiele der Übungsaufgabe befinden sich in dem Logistische_Regression.ipynb Datei.
Die erwarteten Ergebnisse sind unterhalb der jeweiligen Befehle dargestellt. 

Hinweis: Um das erwartete Ergebnis nicht zu verlieren wird empfohlen eine Zwischenzeile zw. dem Befehl 
und dem bereits stehendem Ergebnis hinzufügen bevor das Befehl ausgeführt wird!


1. Libraries installieren & importieren: 
- Hier werden die Librairies für die Datenverarbeitung und -visualisierung installiert und anschließend importiert

2. Die Daten:
- Advertising.csv Datei wird gelesen
- Advertising Daten werden überprüft ob sie richtig gelesen wurden, ob die Darstellung korrekt übernommen wurde, usw.

3. Explorative Datenanalyse:
- Histogram von "Age" wird erstellt. 
- Ein Jointplot, das den "Area Income" mit "Age" vergleicht.
- Ein Jointplot mit KDE Verteilung, der den "Daily Time Spent on Time" mit "Age" vergleicht.
- Ein weiteres Jointplot mit grüner Farbe, diesmal ein Vergleich zw. "Daily Time Spent on Time" und "Age".
- Pair Plot von "Clicked on Ad".

4. Logistische Regression:
- Die Daten werden in Trainings und Testset aufgeteilt.
- Anschließend werden die Trainingsdaten auf das Regressionsmodell trainiert.

5. Vorhersagen und Auswertung
- Nun wird das Regressionsmodell mit Testdaten getestet. Es soll die Werte voraussagen.
- Ein Klassifizierungsreport für das Model wird erstellt.