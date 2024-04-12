Unser Programm soll in der Lage sein, REST-API-Anfragen zu verarbeiten und Dateien zu verwalten. Wir möchten einen zentralen Ort haben, in dem wir alle Dateien speichern können, die wir für unsere Projekte benötigen. Wir möchten in der Lage sein, Notizen zu erstellen, zu bearbeiten, zu löschen und auszugeben. Wir möchten in der Lage sein, unsere Anfragen der Nutzer zu speichern und auszugeben.

Bei Anfragen der Nutzer sollen die Informationen entsprechend verarbeitet und gespeichert werden. Der Speicherort sind JSON-Dateien, die in dem Ordner datagespeichert werden. Wir brauchen mehrere Dateien:

notes.jsonfür die Notizen der Nutzer
log.txtfür Protokollierung der Nutzeranfragen
notes.jsonFolgende Struktur soll haben:

{
  "notes": [
    {
      "id": 1,
      "title": "Max' Erste Notiz",
      "content": "Das ist meine erste Notiz.",
      "user": "Max"
    },
    {
      "id": 2,
      "title": "Max' Zweite Notiz",
      "content": "Das ist meine zweite Notiz.",
      "user": "Max"
    },
    {
      "id": 3,
      "title": "Lisas Erste Notiz",
      "content": "Das ist meine erste Notiz.",
      "user": "Lisa"
    }
  ]
}
Anforderungen
Express-Server

REST-API-Anfragen verarbeiten

Dateien erstellen und bearbeiten

Notizen ausgeben

CRUD-Operationen für Notizen

Anfragen der Nutzer speichern und ausgeben

Optionale Anforderungen
Fehlerbehandlung
Dokumentation
Tests