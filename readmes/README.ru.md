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

Адаптивные цифровые часы с современным минималистичным дизайном, разработанные с использованием Kivy Framework.

## Особенности

- Автоматическая адаптация интерфейса под портретную и ландшафтную ориентацию
- Плавные анимации при смене ориентации и обновлении времени
- Настраиваемая цветовая схема с 9 предустановленными цветами
- Минималистичный дизайн с чёрным фоном
- Оптимизированная производительность с использованием гистерезиса при определении ориентации

## Применение и возможности

OrrClock - это не просто часы, это многофункциональное приложение для отображения времени, которое можно использовать в различных сценариях:

### Домашнее использование
- Как настольные часы на компьютере или ноутбуке
- В качестве часов для презентаций или онлайн-встреч
- Как полноэкранные часы для домашнего кинотеатра

### Профессиональное применение
- В телевизионных студиях для отображения текущего времени
- На информационных экранах в офисах и общественных местах
- В образовательных учреждениях для контроля времени занятий

### Преимущества
- Адаптивный дизайн позволяет использовать приложение на экранах любой ориентации
- Высокая читаемость благодаря контрастным цветам и минималистичному дизайну
- Настраиваемые цвета позволяют подстроить часы под любой интерьер или корпоративный стиль

### Кастомизация
Приложение легко настраивается:
- Выбор цветовых схем
- Адаптация под портретный или ландшафтный режим

## Технологии

- Python 3
- Kivy 2.2.1
- Модульная архитектура с разделением UI компонентов

## Структура проекта

OrrClock/
├── main.py                 # Основной файл приложения  
├── ui/                     # UI компоненты  
│   ├── base_clock.py       # Базовый класс часов  
│   ├── landscape_clock.py  # Ландшафтная ориентация  
│   ├── portrait_clock.py   # Портретная ориентация  
│   └── settings_window.py  # Окно настроек  
├── data/                   # Дополнительные данные  
├── fonts/                  # Шрифты  
└── requirements.txt        # Зависимости проекта  

## Установка

1. Клонируйте репозиторий:
```bash
git clone https://github.com/yourusername/OrrClock.git
cd OrrClock
```

2. Создайте виртуальное окружение и активируйте его:
```bash
python -m venv venv
source venv/bin/activate  # для Linux/Mac
```

3. Установите зависимости:
```bash
pip install -r requirements.txt
```

4. Запустите приложение:
```bash
python main.py
```

## Системные требования

- Python 3.8 или выше
- Kivy 2.2.1
- Минимум 512MB RAM
- Любая операционная система, поддерживающая Python и Kivy (Windows, Linux, macOS)

## Лицензия

MIT License

## Автор

Oruc Qafar - Python разработчик
- GitHub: [OrrStudio](https://github.com/OrrStudio)
- Email: orr888@gmail.com
