# OrrClock

<div align="center">
  <img src="https://github.com/user-attachments/assets/83289c8e-472e-44d9-8bc7-eb27bec46763" alt="OrrClock Logo" width="200"/>
</div>

<div align="center">
  
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)
[![Kivy](https://img.shields.io/badge/Kivy-2.2.1-brightgreen)](https://kivy.org/)
[![GitHub release](https://img.shields.io/badge/Release-v1.0.0-blue)](https://github.com/OrrStudio/OrrClock/releases)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/OrrStudio/OrrClock/graphs/commit-activity)
[![GitHub issues](https://img.shields.io/github/issues/OrrStudio/OrrClock)](https://github.com/OrrStudio/OrrClock/issues)

</div>

Adaptive digitale Uhr mit modernem minimalistischem Design, entwickelt mit dem Kivy Framework.

[🇬🇧 English Version](README.md)

## Funktionen

- Automatische Schnittstellenanpassung für Hoch- und Querformat
- Flüssige Animationen beim Wechsel der Ausrichtung und Zeitaktualisierung
- Anpassbares Farbschema mit 9 voreingestellten Farben
- Minimalistisches Design mit schwarzem Hintergrund
- Optimierte Leistung durch Hysterese bei der Orientierungserkennung

## Anwendungen und Möglichkeiten

OrrClock ist nicht nur eine Uhr, sondern eine multifunktionale Zeitanzeige-Anwendung, die in verschiedenen Szenarien eingesetzt werden kann:

### Heimgebrauch
- Als Schreibtischuhr auf Ihrem Computer oder Laptop
- Als Uhr für Präsentationen oder Online-Meetings
- Als Vollbild-Uhr für das Heimkino

### Professionelle Nutzung
- In TV-Studios zur Anzeige der aktuellen Zeit
- Auf Informationsbildschirmen in Büros und öffentlichen Räumen
- In Bildungseinrichtungen zur Zeitkontrolle

### Vorteile
- Adaptives Design ermöglicht die Nutzung der Anwendung auf Bildschirmen jeder Ausrichtung
- Hohe Lesbarkeit dank kontrastreicher Farben und minimalistischem Design
- Anpassbare Farben ermöglichen die Anpassung der Uhr an jedes Interieur oder Corporate Design

### Anpassung
Die Anwendung ist leicht anpassbar:
- Auswahl von Farbschemata
- Anpassung an Hoch- oder Querformat

## Technologien

- Python 3
- Kivy 2.2.1
- Modulare Architektur mit UI-Komponentenaufteilung

## Projektstruktur

OrrClock/
├── main.py                 # Hauptanwendungsdatei  
├── ui/                     # UI-Komponenten  
│   ├── base_clock.py       # Basis-Uhrenklasse  
│   ├── landscape_clock.py  # Querformat  
│   ├── portrait_clock.py   # Hochformat  
│   └── settings_window.py  # Einstellungsfenster  
├── data/                   # Zusätzliche Daten  
├── fonts/                  # Schriftarten  
└── requirements.txt        # Abhängigkeiten  

## Installation

1. Repository klonen:
```bash
git clone https://github.com/OrrStudio/OrrClock.git
cd OrrClock
```

2. Virtuelle Umgebung erstellen und aktivieren:
```bash
python -m venv venv
source venv/bin/activate  # für Linux/Mac
```

3. Abhängigkeiten installieren:
```bash
pip install -r requirements.txt
```

4. Anwendung starten:
```bash
python main.py
```

## Systemanforderungen

- Python 3.8 oder höher
- Kivy 2.2.1
- Mindestens 512MB RAM
- Jedes Betriebssystem, das Python und Kivy unterstützt (Windows, Linux, macOS)

## Lizenz

MIT License

## Autor

Oruc Qafar - Python-Entwickler
- GitHub: [OrrStudio](https://github.com/OrrStudio)
- Email: orr888@gmail.com