# Student-Spending-Analysis
Die Untersuchung basiert auf der Analyse von studentischen Ausgaben, um mögliche Zusammenhänge zwischen verschiedenen Faktoren und finanziellen Verhaltensweisen zu identifizieren.

## Der Datensatz

- **Datenquelle:**: https://www.kaggle.com/datasets/sumanthnimmagadda/student-spending-dataset

- **Datenbeschreibung:**
Als Datenquelle wurde der Datensatz "Student spending habits dataset" verwendet. Er besteht aus 1000 Einträge mit der Information zum Hintergrund der Studierenden und ihren Ausgaben in genauen Zahlen. Alle Daten wuden künstlich erstellt.

- **Daten Interpretierung:**
Die Spalte "Finanzielle Unterstützung" (eng. "Financial Aid") wurde in der Analyse als zusätzliche Einkommnsquelle interpretiert, da es auf der Webseite des Datensatzes an genaue Datenbeschreibung fehlte. Die Bedeutung anderer Säulen kann nachgeprüft werden:

- **Lizenz:** Apache 2.0 https://www.apache.org/licenses/LICENSE-2.0

## Tools & Libraries

- Python (pandas, seaborn, matplotlib, numpy, statsmodels, scipy)
- Google Colab (for development)
  
## Zusammengefasst

Mit diesem Projekt wurde das Ziel gesetzt, das finanzielle Verhalten von Studierenden mit unterschiedlichem Hintergrund zu analysieren, um mögliche Zusammenhänge zu erkennen und zu überprüfen.
Vor der Bearbeitung des Datensatzes wurden drei konkrete Fragestellungen zu Alter, Studiengang, Ausgaben und Einkommen formuliert, um den Rahmen der Analyse klar abzustecken.
Die Bearbeitung der Daten begann mit der Übersetzung des Datensatzes sowie der Umrechnung der Währung, um eine bessere Darstellung und ein besseres Verständnis der Informationen zu ermöglichen. Die Studienjahre wurden von den Kategorien Freshman, Sophomore, Junior und Senior in genaue Studienjahre umgewandelt. Die Währung wurde mithilfe einer API von US-Dollar in Euro umgerechnet. Alle anderen Bezeichnungen wurden ebenfalls ins Deutsche übersetzt.
Im zweiten Schritt erfolgte die explorative Datenanalyse und eine erste Mustererkennung. Dabei wurde kein Bedarf an Data Cleaning festgestellt: Alle Namen waren standardisiert, fehlende Werte oder Ausreißer wurden nicht gefunden.
In der anschließenden Datenanalyse wurden verschiedene Methoden eingesetzt, um Zusammenhänge im Hinblick auf die zuvor formulierten Fragen zu untersuchen. Zum Einsatz kamen T-Test, F-Test, Säulendiagramme, Regressionsmodell und K-Clustering. Es konnten jedoch keine signifikanten Zusammenhänge festgestellt werden.
