# 💻 Krypto Watchlist/Tracker (Frontend-Projekt)

Dieses Projekt ist eine Web-App zur Verwaltung von Kryptowährungen. Nutzer können Kryptowährungen zur Watchlist hinzufügen, bearbeiten oder löschen. Das Ganze basiert auf einem lokalen JSON-Server und wurde mit HTML, CSS, JavaScript und Bootstrap umgesetzt.

## ⚙️ Features

- Dynamische Watchlist mit API-Anbindung
- Datenbindung an lokalen JSON-Server (Fake API)
- Responsives Design mit Bootstrap
- REST-Aufrufe mit JavaScript (fetch)
- Live-Vorschau via VSCode Live Server
- Teilweise automatisiertes Testing mit Selenium

## 🔄 Funktionen

- Kryptowährung hinzufügen
- Eintrag ersetzen (Update)
- Eintrag löschen
- Visuelles Feedback bei Aktionen

## 🧪 Tests

- REST Client Tests auf JSON-Server
- Teilweise Selenium-Automation (z. B. für „Hinzufügen“)

## 🧠 Reflexion

Ich wollte dieses Projekt mit JavaScript umsetzen, weil ich besser verstehen wollte, wie APIs in echten Webanwendungen eingebunden werden. Die Hauptfunktion ist eine Krypto-Watchlist, bei der man verschiedene Coins hinzufügen und deren Preise in Echtzeit sehen kann. Dabei war mir wichtig, dass die Daten direkt von einer API kommen und sich dynamisch im DOM aktualisieren.
Am Anfang hatte ich Probleme mit dem JSON-Server und CORS, aber nach mehreren Debugging-Sessions habe ich gelernt, wie man API-Abfragen richtig strukturiert – und worauf man bei fetch() und JSON achten muss. Auch die DOM-Manipulation in reinem JavaScript (ohne Framework) war neu für mich, besonders was das gezielte Erstellen und Löschen von Elementen betrifft.
Die Testphase mit Selenium war ebenfalls eine Herausforderung, weil manche HTML-Elemente nicht sauber selektierbar waren und dadurch das es Popups gab konnte es auch nicht sauber automatisch getestet werden. Trotzdem konnte ich dadurch viel über automatisierte Tests und strukturierte Code-Aufteilung im Frontend lernen. Ich bin jetzt sehr Stolz auf meine Krypto-Watchlist auch wenn ich nicht die beste Note dafür bekamm. Für mich bleibt sie eine von meinen lieblings Projekten.
