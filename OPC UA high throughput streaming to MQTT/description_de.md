Diese Solution enthält einen für den **Multi Datachange Trigger** optimierten **OPC UA Client Connector**, der für einen **hohen Datendurchsatz** optimiert ist.

##### Vorgenommene Optimierungen

* OPC UA Client
  * Asynchrones Browsing für den Multi Datachange Trigger wird genutzt.
* Multi Datachange Trigger
  * Aktualisierung der Items wurde deaktiviert.

Der enthaltene Flow realisiert die Übertragung der Daten aus dem Multi Datachange Trigger an einen MQTT Broker.
