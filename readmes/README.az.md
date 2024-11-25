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

Kivy framework istifadə edərək hazırlanmış müasir və minimalist dizayna malik adaptiv rəqəmsal saat.

[🇬🇧 English](../README.md) |  
[🇹🇷 Türkçe](README.tr.md) |  
[🇸🇦 العربية](README.ar.md) |  
[🇮🇷 فارسی](README.fa.md) |  
[🇷🇺 Русский](README.ru.md) |  
[🇩🇪 Deutsch](README.de.md) |  
[🇮🇹 Italiano](README.it.md) |  
[🇪🇸 Español](README.es.md) |  
[🇫🇷 Français](README.fr.md) |  
[🇯🇵 日本語](README.ja.md) |  
[🇨🇳 中文](README.zh.md) |  
[🇮🇳 हिंदी](README.hi.md)

## Xüsusiyyətlər

- Portret və landşaft istiqaməti üçün avtomatik interfeys adaptasiyası
- İstiqaməti dəyişərkən və vaxtı yeniləyərkən səlis animasiyalar
- 9 əvvəlcədən təyin edilmiş rənglə fərdiləşdirilə bilən rəng sxemi
- Qara fon ilə minimalist dizayn
- İstiqamət aşkarlanması üçün histerezis istifadə edərək optimallaşdırılmış performans

## Tətbiqlər və İmkanlar

OrrClock sadəcə bir saat deyil, müxtəlif ssenarilərdə istifadə edilə bilən çoxfunksiyalı vaxt göstərmə tətbiqidir:

### Ev İstifadəsi
- Kompüter və ya noutbukda masaüstü saatı kimi
- Təqdimatlar və ya onlayn görüşlər üçün saat kimi
- Ev teatrı üçün tam ekran saatı kimi

### Peşəkar İstifadə
- TV studiyalarında cari vaxtı göstərmək üçün
- Ofis və ictimai məkanlarda məlumat ekranlarında
- Təhsil müəssisələrində vaxt nəzarəti üçün

### Üstünlüklər
- Adaptiv dizayn tətbiqin istənilən istiqamətli ekranda istifadəsinə imkan verir
- Kontrast rənglər və minimalist dizayn sayəsində yüksək oxunaqlılıq
- Fərdiləşdirilə bilən rənglər saatın istənilən interyerə və ya korporativ üsluba uyğunlaşmasına imkan verir

### Fərdiləşdirmə
Tətbiq asanlıqla fərdiləşdirilə bilər:
- Rəng sxemlərinin seçimi
- Portret və ya landşaft rejimi üçün adaptasiya

## Texnologiyalar

- Python 3
- Kivy 2.2.1
- UI komponentlərinin ayrılması ilə modulyar arxitektura

## Layihə Strukturu

OrrClock/
├── main.py                 # Əsas tətbiq faylı  
├── ui/                     # UI komponentləri  
│   ├── base_clock.py       # Baza saat sinifi  
│   ├── landscape_clock.py  # Landşaft istiqaməti  
│   ├── portrait_clock.py   # Portret istiqaməti  
│   └── settings_window.py  # Parametrlər pəncərəsi  
├── data/                   # Əlavə məlumatlar  
├── fonts/                  # Şriftlər  
└── requirements.txt        # Asılılıqlar  

## Quraşdırma

1. Repozitoriyanı klonlayın:
```bash
git clone https://github.com/OrrStudio/OrrClock.git
cd OrrClock
```

2. Virtual mühiti yaradın və aktivləşdirin:
```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac üçün
```

3. Asılılıqları quraşdırın:
```bash
pip install -r requirements.txt
```

4. Tətbiqi başladın:
```bash
python main.py
```

## Sistem Tələbləri

- Python 3.8 və ya daha yüksək
- Kivy 2.2.1
- Minimum 512MB RAM
- Python və Kivy dəstəkləyən istənilən əməliyyat sistemi (Windows, Linux, macOS)

## Lisenziya

MIT License

## Müəllif

Oruc Qafar - Python Developer
- GitHub: [OrrStudio](https://github.com/OrrStudio)
- E-poçt: orr888@gmail.com
