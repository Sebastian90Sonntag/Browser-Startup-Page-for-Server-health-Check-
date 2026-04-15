# 🖥️ Server Health Dashboard

Eine leichtgewichtige Browser-Startseite zur Überwachung und Verwaltung von Servern — als einzelne HTML-Datei ohne Backend-Abhängigkeiten.

## Features

- **Server-Management** — Server mit Name, IP/Domain, Beschreibung und Interface-Link anlegen, bearbeiten und löschen
- **Kategorien** — Server in frei definierbare Kategorien organisieren (z. B. Produktion, Entwicklung, Staging)
- **Status-Prüfung** — Alle Server auf einmal prüfen (Online / Offline / Unbekannt)
- **Auto-Check** — Konfigurierbare automatische Statusprüfung (30s bis 1h Intervall)
- **Interface-Links** — Direkter Zugriff auf Server-Webinterfaces per Klick
- **Responsive Design** — Funktioniert auf Desktop und Mobilgeräten
- **Zero Dependencies** — Reine HTML/CSS/JavaScript-Lösung, kein Build-Prozess nötig

## Vorschau

Das Dashboard zeigt Server-Karten mit Statusanzeige, gruppiert nach Kategorien. Ein Control-Panel ermöglicht das Hinzufügen neuer Server/Kategorien und die Steuerung der automatischen Prüfung.

## Verwendung

1. `Index.html` im Browser öffnen
2. Kategorien anlegen (z. B. "Produktionsserver", "Entwicklungsumgebung")
3. Server mit IP/Domain und optionalem Interface-Link hinzufügen
4. "Status prüfen" klicken oder Auto-Check aktivieren

> **Hinweis:** Daten werden im `sessionStorage` des Browsers gespeichert und sind nur für die aktuelle Sitzung verfügbar.

## Tech Stack

| Technologie | Verwendung |
|-------------|------------|
| HTML5 | Struktur & Modals |
| CSS3 | Grid-Layout, Responsive Design, Animationen |
| JavaScript (Vanilla) | DOM-Manipulation, sessionStorage, Timer |

## Projektstruktur

```
Browser-Startup-Page-for-Server-health-Check-/
├── Index.html    # Komplette Anwendung (HTML + CSS + JS)
└── README.md
```

## Autor

**Sebastian Sonntag** — 2025
