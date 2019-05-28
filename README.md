# Postman Calls für die EUROPACE APIs

Eine Übersicht aller APIs ist hier zu finden: https://developer.europace.de/

Probeaufrufe der APIs sind sehr hilfreich, um schnell einzusteigen. Dafür empfehlen wir [Postman](https://www.getpostman.com/), was auf Windows, Mac OS und Linux funktioniert.

Schritte um Postman einzurichten:
1. Postman installieren
2. [Postman Collection](https://github.com/europace/api-sandbox/blob/master/EUROPACE%20API%20Calls.postman_collection.json) als JSON-Datein runterladen.
3. In dieser JSON-Datei PartnerID und API-Key mit Wert `TODO` durch eigene Credentials ersetzen. Das geht mit einem Text-Editor.
4. Die JSON_Datei als Collection im Postman importieren.
5. Der erste Call in der Collection (`Login -> JWT erzeugen  mit PartnerId und API-Key`) müsste ein "JWT-Token" zurückliefern. Damit hat der Login stattgefunden.
6. Jetzt können alle weiteren Calls ausgeführt werden.
