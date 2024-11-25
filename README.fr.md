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

Horloge numérique adaptative avec un design minimaliste moderne, développée avec le framework Kivy.

[🇬🇧 Version Anglaise](README.md)

## Caractéristiques

- Adaptation automatique de l'interface pour l'orientation portrait et paysage
- Animations fluides lors du changement d'orientation et de la mise à jour de l'heure
- Schéma de couleurs personnalisable avec 9 couleurs prédéfinies
- Design minimaliste avec fond noir
- Performance optimisée utilisant l'hystérésis pour la détection d'orientation

## Applications et Capacités

OrrClock n'est pas qu'une simple horloge, c'est une application multifonctionnelle d'affichage du temps qui peut être utilisée dans divers scénarios :

### Usage Domestique
- Comme horloge de bureau sur votre ordinateur ou portable
- Comme horloge pour les présentations ou réunions en ligne
- Comme horloge plein écran pour le home cinéma

### Usage Professionnel
- Dans les studios de télévision pour l'affichage de l'heure actuelle
- Sur les écrans d'information dans les bureaux et espaces publics
- Dans les établissements d'enseignement pour le contrôle du temps

### Avantages
- Le design adaptatif permet l'utilisation de l'application sur des écrans de toute orientation
- Haute lisibilité grâce aux couleurs contrastées et au design minimaliste
- Les couleurs personnalisables permettent d'adapter l'horloge à tout intérieur ou style d'entreprise

### Personnalisation
L'application est facilement personnalisable :
- Choix des schémas de couleurs
- Adaptation au mode portrait ou paysage

## Technologies

- Python 3
- Kivy 2.2.1
- Architecture modulaire avec séparation des composants UI

## Structure du Projet

OrrClock/
├── main.py                 # Fichier principal de l'application  
├── ui/                     # Composants UI  
│   ├── base_clock.py       # Classe de base de l'horloge  
│   ├── landscape_clock.py  # Orientation paysage  
│   ├── portrait_clock.py   # Orientation portrait  
│   └── settings_window.py  # Fenêtre de paramètres  
├── data/                   # Données supplémentaires  
├── fonts/                  # Polices  
└── requirements.txt        # Dépendances  

## Installation

1. Clonez le dépôt :
```bash
git clone https://github.com/OrrStudio/OrrClock.git
cd OrrClock
```

2. Créez et activez l'environnement virtuel :
```bash
python -m venv venv
source venv/bin/activate  # pour Linux/Mac
```

3. Installez les dépendances :
```bash
pip install -r requirements.txt
```

4. Lancez l'application :
```bash
python main.py
```

## Configuration Requise

- Python 3.8 ou supérieur
- Kivy 2.2.1
- Minimum 512MB RAM
- Tout système d'exploitation supportant Python et Kivy (Windows, Linux, macOS)

## Licence

MIT License

## Auteur

Oruc Qafar - Développeur Python
- GitHub: [OrrStudio](https://github.com/OrrStudio)
- Email: orr888@gmail.com
