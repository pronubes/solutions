Mit dieser Solution können freie Schichtbuch-Einträge mithilfe der OpenAI API automatisch klassifiziert und in ein standardisiertes JSON-Objekt überführt werden.

Es sind zwei Verbindungen enthalten.
Die Web-Trigger-Verbindung stellt eine leichte [**Debug- und Testseite**](/services/AI%20Shift%20Log%20Classifier%20API/shift-log-classifier/ui) bereit, über die Beispiel-Schichteinträge zur Validierung des Klassifizierers eingegeben werden können.
Die Eingaben werden an den in der AI-Trigger-Verbindung definierten AI-Endpunkt weitergeleitet.
Dort werden die Daten automatisch verarbeitet, an die OpenAI API gesendet und die relevanten Felder extrahiert und kategorisiert.
Das erzeugte JSON-Objekt wird anschließend an die Testseite zurückgegeben und dort angezeigt.

##### Hinweise
- Die Organisations- und Projekt-ID finden Sie unter [**platform.openai.com**](https://platform.openai.com/) in den Einstellungen unter dem **General**-Menüpunkt.
- Es ist standardmäßig das Modell **GPT-5-mini** konfiguriert.
