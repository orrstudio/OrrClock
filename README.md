# OrrClock

<div align="center">
  <img src="https://github.com/user-attachments/assets/83289c8e-472e-44d9-8bc7-eb27bec46763" alt="OrrClock Logo" width="800"/>
</div>

<div align="center">
  
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)
[![Kivy](https://img.shields.io/badge/Kivy-2.2.1-brightgreen)](https://kivy.org/)
[![GitHub release](https://img.shields.io/badge/Release-v1.0.0-blue)](https://github.com/OrrStudio/OrrClock/releases)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/OrrStudio/OrrClock/graphs/commit-activity)
[![GitHub issues](https://img.shields.io/github/issues/OrrStudio/OrrClock)](https://github.com/OrrStudio/OrrClock/issues)

</div>

Adaptive digital clock with a modern minimalist design, developed using the Kivy Framework.

[🇦🇿 Azərbaycan](readmes/README.az.md) |  
[🇹🇷 Türkçe](readmes/README.tr.md) |  
[🇸🇦 العربية](readmes/README.ar.md)  
[🇮🇷 فارسی](readmes/README.fa.md) |  
[🇷🇺 Русский](readmes/README.ru.md) |  
[🇩🇪 Deutsch](readmes/README.de.md) |  
[🇮🇹 Italiano](readmes/README.it.md) |  
[🇪🇸 Español](readmes/README.es.md) |  
[🇫🇷 Français](readmes/README.fr.md) |  
[🇯🇵 日本語](readmes/README.ja.md) |  
[🇨🇳 中文](readmes/README.zh.md) |  
[🇮🇳 हिंदी](readmes/README.hi.md) |  

## Features

- Automatic interface adaptation for portrait and landscape orientation
- Smooth animations when changing orientation and updating time
- Customizable color scheme with 9 preset colors
- Minimalist design with black background
- Optimized performance using hysteresis for orientation detection

## Applications and Capabilities

OrrClock is not just a clock, it's a multifunctional time display application that can be used in various scenarios:

### Home Use
- As a desktop clock on your computer or laptop
- As a clock for presentations or online meetings
- As a fullscreen clock for home theater

### Professional Use
- In TV studios for current time display
- On information displays in offices and public spaces
- In educational institutions for time control

### Advantages
- Adaptive design allows using the application on screens of any orientation
- High readability thanks to contrasting colors and minimalist design
- Customizable colors allow adapting the clock to any interior or corporate style

### Customization
The application is easily customizable:
- Choice of color schemes
- Adaptation to portrait or landscape mode

## Technologies

- Python 3
- Kivy 2.2.1
- Modular architecture with UI component separation

## Project Structure
```
OrrClock/
├── main.py                 # Main application file
├── ui/                     # UI components
│   ├── base_clock.py       # Base clock class
│   ├── landscape_clock.py  # Landscape orientation
│   ├── portrait_clock.py   # Portrait orientation
│   └── settings_window.py  # Settings window
├── data/                   # Additional data
├── fonts/                  # Fonts
└── requirements.txt        # Dependencies
```

## Installation

1. Clone the repository:
```bash
git clone https://github.com/OrrStudio/OrrClock.git
cd OrrClock
```

2. Create and activate virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # for Linux/Mac
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Run the application:
```bash
python main.py
```

## System Requirements

- Python 3.8 or higher
- Kivy 2.2.1
- Minimum 512MB RAM
- Any operating system supporting Python and Kivy (Windows, Linux, macOS)

## Testing Branch Protection
This is a test commit to verify branch protection rules.

## Test Protection
This is a test commit to verify branch protection rules.

## License

MIT License

## Author

Oruc Qafar - Python Developer
- GitHub: [OrrStudio](https://github.com/OrrStudio)
- Email: orr888@gmail.com
