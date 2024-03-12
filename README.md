# Studienarbeit-Eric-Schwarz
In diesem Repository sind alle Dateien, die für die Anwendung für die von mir erstellten ML-Modelle benötigt werden

Unter den verfügbaren Dateien befinden sich die Jupyter Notebook Dateien mit den einzelnen ML-Modellen.
Es gibt die vier Jupyter Notebooks "KNN Zugwerte T", "KNN Zugwerte V", "KNN Dichte" und "KNN Abweichung" - dort ist jeweils der Python-Code enthalten der verwendet wurde um die Daten vorzubereiten und die Modelle zu tranineren und zu validieren.

Zusätzlich gibt es zu jeder dieser vier Jupyter Notebooks einen gleichnamigen Ordner, sowie eine .plk-Datei. In den Ordnern sind die gespeicherten Gewichtungen und Einstellungen der von mir trainierten Modelle enthalten. Die plk.-Dateien entahlten die Einstellungen der Skalierungsfunktion StandardScaler, die jeweils verwendet wurde, um die genuttzten Ausgangsdaten für das Künstliche Neuronale Netz zu skalieren.

In der Jupyter Notebook Datei "KNN Vorhersage" werden die gespeicherten trainierten Modelle und die Werteskalierungen geladen, sodass bei Eingabe der Parameter Schichtdicke, Druckgeschwindigkeit, Drucktemperatur und Fülldichte als Ausgabewerte die Vorhersagen der Modelle ausgegeben werden.


Neben den KNN-Modellen gibt es noch die vier RF-Regressionsmodelle.
