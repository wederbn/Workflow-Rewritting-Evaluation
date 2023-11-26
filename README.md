# Evaluation der Methode zur Analyse und Umschreibung von Quantenworkflows

Dieses Repository enthält die Messungen, die als Grundlage zur Evaluation der Methode zur Analyse und Umschreibung von Quantenworkflows aus Kapitel 5.1 der Dissertation "Workflow-basierte Modellierung, Ausführung und Überwachung hybrider Quantenanwendungen" dient.

Es enthält die folgenden Daten, wobei diese jeweils als Excel Tabelle (.xlsx) und Kommaseparierte Liste (.csv) bereitgestellt werden:

* Laufzeit der Methode zur Analyse und Umschreibung: Evaluation von 7 Workflows bei 2 Providern (IBMQ, AWS) mit jeweils 100 Messungen
    * [Laufzeit-Analyse-und-Umschreibung.xlsx](./Laufzeit-Analyse-und-Umschreibung.xlsx)
    * [Laufzeit-Analyse-und-Umschreibung.csv](./Laufzeit-Analyse-und-Umschreibung.csv)

* Ausführungszeit von Quantenworkflows vor und nach der Umschreibung bei IBMQ: Evaluation von 4 Workflows bei Ausführung über IBMQ mit und ohne Qiskit Runtime und jeweils 10 Messungen
    * [Laufzeit-Vergleich-IBMQ.xlsx](./Laufzeit-Vergleich-IBMQ.xlsx)
    * [Laufzeit-Vergleich-IBMQ.csv](./Laufzeit-Vergleich-IBMQ.csv)

* Ausführungszeit von Quantenworkflows vor und nach der Umschreibung bei AWS: Evaluation von einem Workflow bei Ausführung über AWS mit und ohne Hybrid Jobs und jeweils 10 Messungen
    * [Laufzeit-Vergleich-AWS.xlsx](./Laufzeit-Vergleich-AWS.xlsx)
    * [Laufzeit-Vergleich-AWS.csv](./Laufzeit-Vergleich-AWS.csv)