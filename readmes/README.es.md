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

Un reloj digital adaptativo con un diseño moderno y minimalista, desarrollado utilizando el framework Kivy.

[🇬🇧 English](../README.md) |  
[🇦🇿 Azərbaycan](README.az.md) |  
[🇹🇷 Türkçe](README.tr.md) |  
[🇸🇦 العربية](README.ar.md) |  
[🇮🇷 فارسی](README.fa.md) |  
[🇷🇺 Русский](README.ru.md) |  
[🇩🇪 Deutsch](README.de.md) |  
[🇮🇹 Italiano](README.it.md) |  
[🇫🇷 Français](README.fr.md) |  
[🇯🇵 日本語](README.ja.md) |  
[🇨🇳 中文](README.zh.md) |  
[🇮🇳 हिंदी](README.hi.md)

## Características

- Adaptación automática de la interfaz para orientación vertical y horizontal
- Animaciones fluidas al cambiar la orientación y actualizar la hora
- Esquema de colores personalizable con 9 colores predefinidos
- Diseño minimalista con fondo negro
- Rendimiento optimizado utilizando histéresis para la detección de orientación

## Aplicaciones y Capacidades

OrrClock no es solo un reloj, es una aplicación multifuncional de visualización del tiempo que se puede utilizar en varios escenarios:

### Uso Doméstico
- Como reloj de escritorio en tu computadora o laptop
- Como reloj para presentaciones o reuniones en línea
- Como reloj de pantalla completa para cine en casa

### Uso Profesional
- En estudios de televisión para mostrar la hora actual
- En pantallas informativas en oficinas y espacios públicos
- En instituciones educativas para el control del tiempo

### Ventajas
- El diseño adaptativo permite usar la aplicación en pantallas de cualquier orientación
- Alta legibilidad gracias a los colores contrastantes y al diseño minimalista
- Los colores personalizables permiten adaptar el reloj a cualquier interior o estilo corporativo

### Personalización
La aplicación es fácilmente personalizable:
- Elección de esquemas de colores
- Adaptación al modo vertical u horizontal

## Tecnologías

- Python 3
- Kivy 2.2.1
- Arquitectura modular con separación de componentes UI

## Estructura del proyecto

OrrClock/
├── main.py                 # Archivo principal de la aplicación
├── ui/                     # Componentes de UI
│   ├── base_clock.py       # Clase base del reloj
│   ├── landscape_clock.py  # Orientación horizontal
│   ├── portrait_clock.py   # Orientación vertical
│   └── settings_window.py  # Ventana de configuración
├── data/                   # Datos adicionales
├── fonts/                  # Fuentes
└── requirements.txt        # Dependencias

## Instalación

1. Clona el repositorio:
```bash
git clone https://github.com/OrrStudio/OrrClock.git
cd OrrClock
```

2. Crea y activa el entorno virtual:
```bash
python -m venv venv
source venv/bin/activate  # para Linux/Mac
```

3. Instala las dependencias:
```bash
pip install -r requirements.txt
```

4. Ejecuta la aplicación:
```bash
python main.py
```

## Requisitos del Sistema

- Python 3.8 o superior
- Kivy 2.2.1
- Mínimo 512MB RAM
- Cualquier sistema operativo que soporte Python y Kivy (Windows, Linux, macOS)

## Licencia

MIT License

## Autor

Oruc Qafar - Desarrollador Python
- GitHub: [OrrStudio](https://github.com/OrrStudio)
- Email: orr888@gmail.com
