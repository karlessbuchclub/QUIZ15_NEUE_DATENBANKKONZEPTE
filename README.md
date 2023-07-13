# QUIZ15_NEUE_DATENBANKKONZEPTE
Hier ist das Projekt für "Neue Datenbankkonzepte" hinterlegt. Das QUIZ15 kann hier abgerufen und gedownloaded werden. 

Hier der Link zum Projekt:
https://github.com/karlessbuchclub/QUIZ15_NEUE_DATENBANKKONZEPTE/

Anleitung zum Setup und Starten des Projekts
Diese Anleitung erklärt, wie Sie unsere Quiz-App auf Ihrem lokalen System einrichten und starten können.

Voraussetzungen
Bevor Sie fortfahren, stellen Sie sicher, dass die folgenden Tools auf Ihrem System installiert sind:
- Node.js und npm
- MongoDB

Schritt 1: Projekt-Repository klonen
Öffnen Sie ein Terminal auf Ihrem Computer und klonen Sie das Repository mit dem folgenden Befehl:
git clone [Link-zum-Projekt-Repository]
Schritt 2: Abhängigkeiten installieren

Navigieren Sie in das Projektverzeichnis und installieren Sie die notwendigen Abhängigkeiten mit npm:
cd [Projekt-Verzeichnis]
npm install
Schritt 3: Datenbank einrichten

Starten Sie MongoDB auf Ihrem System. Wenn Sie eine spezielle Datenbankkonfiguration verwenden möchten, können Sie diese in einer .env-Datei im Wurzelverzeichnis des Projekts festlegen. Die Datei sollte folgende Variablen enthalten:
DB_HOST= localhost
DB_PORT= 3000
DB_URI = mongodb://127.0.0.1:27017/fivquiz

Schritt 4: Server starten
Jetzt können Sie den Server starten. Führen Sie dazu den folgenden Befehl aus:
npm start

Sie sollten eine Meldung sehen, dass der Server läuft und auf Verbindungen wartet.

Glückwunsch! Sie haben nun die Quiz-App auf Ihrem System eingerichtet und ausgeführt. Sie können die Anwendung in Ihrem Webbrowser unter der angegebenen Adresse öffnen.
