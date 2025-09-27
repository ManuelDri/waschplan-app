# Waschplan-App

Die Waschplan-App ist eine kleine Web-App, mit der man im Mehrfamilienhaus ganz entspannt die Waschmaschine buchen kann. Schluss mit Zetteln an der Tür oder Diskussionen im Treppenhaus – jeder sieht sofort, wann die Maschine frei ist, und kann sich unkompliziert einen Slot reservieren.

## Was die App kann

* Übersichtlicher Wochenplan mit freien und belegten Zeiten
* Slots direkt online reservieren oder wieder freigeben
* Alles läuft in Echtzeit über Firebase – jeder sieht sofort die aktuellen Buchungen

## Technik unter der Haube

* **Frontend:** Angular
* **Backend & Hosting:** Firebase Hosting + Firebase Functions
* **Datenbank:** Cloud Firestore
* **Login:** Firebase Authentication

## Warum?

Weil jeder im Haus waschen muss – und es viel entspannter ist, wenn das Ganze digital und transparent geregelt ist.

## Schnellstart

```bash
git clone https://github.com/<dein-user>/waschplan-app.git
cd waschplan-app
npm install
npm start
```

Deployment auf Firebase:

```bash
firebase deploy
```
