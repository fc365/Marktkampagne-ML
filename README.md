# Marktkampagne-ML 📊

Dieses Projekt analysiert Marketingdaten einer Bank, um vorherzusagen, welche Kunden ein Festgeldkonto (*Term Deposit*) abschließen werden. Ziel ist es, durch Machine Learning die Effizienz zukünftiger Kampagnen zu steigern.

## 🚀 Projektablauf
Das Notebook umfasst den kompletten Data Science Workflow:

1.  **Explorative Datenanalyse (EDA):** Untersuchung von Alter, Job, Familienstand und Bildungsgrad der Kunden.
2.  **Datenbereinigung:** Behandlung von fehlenden Werten (z. B. "unknown") und Feature-Engineering.
3.  **Preprocessing:** Umwandlung kategorialer Daten mittels `LabelEncoder` und Skalierung der Werte.
4.  **Modellierung:** Training eines **Random Forest Classifiers**, um die Zielvariable `y` (Abo abgeschlossen: Ja/Nein) vorherzusagen.
5.  **Evaluierung:** Analyse der Modellleistung mittels einer Confusion Matrix.

## 🛠️ Verwendete Technologien
* **Python 3**
* **Pandas & NumPy** für die Datenverarbeitung
* **Matplotlib & Seaborn** für die Visualisierungen
* **Scikit-Learn** für das Machine Learning (Random Forest)

## 📈 Wichtigste Erkenntnisse
* Bestimmte Berufsgruppen und Bildungsgrade zeigen eine deutlich höhere Conversion-Rate.
* Das Modell hilft dabei, Marketingressourcen gezielt auf Kunden mit hoher Abschlusswahrscheinlichkeit zu konzentrieren.
