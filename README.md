# CnnMathematicalFunctions
Python project from AWS Sagemaker to train a CNN to categorize images of mathematical functions.  
Folder structure:
* main: Main Datei, die den Fluss des Programms steuert
* data: Daten (train, val, test) für das Modell. Lädt ggf ein Teil der Daten von AWS S3, anderer Teil erstellt mit Seaborn
* models: Eigentliches Modell. Initialisiert Modell, kompiliert es und gibt predictions ab
* services: Kleinere Hilfsfunktionalitäten zur Ausführung des Modells (z.B: Generieren von Beispielbildern)
* resuls: Speichern eines fertigen Modells zur späteren Wiederverwendung
* logs: Sichern von log-Daten zur Ausführung eines Modells zur späteren Analyse
