# CnnMathematicalFunctions
Python project from AWS Sagemaker to train a CNN to categorize images of mathematical functions.
Folder structure:
* main: Main Datei, die den Fluss des Programms steuert
* data: Daten (train, val, test) für das Modell. Lädt ggf Daten von S3
* models: Eigentliches Modell. Initialisiert Modell, kompiliert es und gibt predictions ab
* services: Kleinere Hilfsfunktionalitäten zur Ausführung des Modells (z.B: Generieren von Beispielbildern)
* resuls: Speichern eines fergies Modells zur späteren Wiederverwendung
* logs: Sichern von log-Daten zur Ausführung eines Modells zur späteren Analyse
