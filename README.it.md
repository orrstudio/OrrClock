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

Orologio digitale adattivo con design minimalista moderno, sviluppato utilizzando il framework Kivy.

[🇬🇧 English Version](README.md)

## Caratteristiche

- Adattamento automatico dell'interfaccia per l'orientamento verticale e orizzontale
- Animazioni fluide durante il cambio di orientamento e l'aggiornamento dell'ora
- Schema colori personalizzabile con 9 colori preimpostati
- Design minimalista con sfondo nero
- Prestazioni ottimizzate utilizzando l'isteresi per il rilevamento dell'orientamento

## Applicazioni e Capacità

OrrClock non è solo un orologio, è un'applicazione multifunzionale per la visualizzazione del tempo che può essere utilizzata in vari scenari:

### Uso Domestico
- Come orologio da scrivania sul computer o laptop
- Come orologio per presentazioni o riunioni online
- Come orologio a schermo intero per l'home theater

### Uso Professionale
- Negli studi televisivi per la visualizzazione dell'ora corrente
- Su display informativi in uffici e spazi pubblici
- Nelle istituzioni educative per il controllo del tempo

### Vantaggi
- Il design adattivo permette l'utilizzo dell'applicazione su schermi di qualsiasi orientamento
- Alta leggibilità grazie ai colori contrastanti e al design minimalista
- I colori personalizzabili permettono di adattare l'orologio a qualsiasi interno o stile aziendale

### Personalizzazione
L'applicazione è facilmente personalizzabile:
- Scelta degli schemi colore
- Adattamento alla modalità verticale o orizzontale

## Tecnologie

- Python 3
- Kivy 2.2.1
- Architettura modulare con separazione dei componenti UI

## Struttura del Progetto

OrrClock/
├── main.py                 # File principale dell'applicazione  
├── ui/                     # Componenti UI  
│   ├── base_clock.py       # Classe base dell'orologio  
│   ├── landscape_clock.py  # Orientamento orizzontale  
│   ├── portrait_clock.py   # Orientamento verticale  
│   └── settings_window.py  # Finestra impostazioni  
├── data/                   # Dati aggiuntivi  
├── fonts/                  # Font  
└── requirements.txt        # Dipendenze  

## Installazione

1. Clona il repository:
```bash
git clone https://github.com/OrrStudio/OrrClock.git
cd OrrClock
```

2. Crea e attiva l'ambiente virtuale:
```bash
python -m venv venv
source venv/bin/activate  # per Linux/Mac
```

3. Installa le dipendenze:
```bash
pip install -r requirements.txt
```

4. Avvia l'applicazione:
```bash
python main.py
```

## Requisiti di Sistema

- Python 3.8 o superiore
- Kivy 2.2.1
- Minimo 512MB RAM
- Qualsiasi sistema operativo che supporti Python e Kivy (Windows, Linux, macOS)

## Licenza

MIT License

## Autore

Oruc Qafar - Sviluppatore Python
- GitHub: [OrrStudio](https://github.com/OrrStudio)
- Email: orr888@gmail.com