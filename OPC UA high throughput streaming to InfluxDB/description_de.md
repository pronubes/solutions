Diese Solution enthält einen für den **Multi Datachange Trigger** optimierten **OPC UA Client Connector** und einen **InfluxDB Connector**. Beide Connectors sind für einen **hohen Datendurchsatz** optimiert.

##### Vorgenommene Optimierungen

* OPC UA Client
  * Asynchrones Browsing für den Multi Datachange Trigger wird genutzt.
* Multi Datachange Trigger
  * Aktualisierung der Items wurde deaktiviert.
* InfluxDB
  * Es werden gestapelte/asynchrone Inserts verwendet.

Der enthaltene Flow realisiert die Übertragung der Daten aus dem Multi Datachange Trigger an eine InfluxDB.
