# Todo-Liste

Ein einfaches Todo-Listen-Projekt mit [json-server](https://github.com/typicode/json-server) als Backend und Vanilla JavaScript als Frontend.

## Voraussetzungen

- [Node.js](https://nodejs.org/) installiert

## Backend starten

Installiere json-server global:

```bash
npm install -g json-server
```

Starte das Backend mit deiner Datenbankdatei:

```bash
json-server --watch db.json
```

Das Backend läuft jetzt auf [http://localhost:3000](http://localhost:3000).

## Frontend starten

Öffne die Datei `index.html` im Browser.

## Hinweise

- Die Todos werden unter `/todos` bereitgestellt.
- Änderungen an der Datei `db.json` werden automatisch übernommen.
- Das Frontend greift über `fetch('http://localhost:3000/todos')` auf die Daten zu.

---
