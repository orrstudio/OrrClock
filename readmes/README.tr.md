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

Kivy Framework kullanılarak geliştirilmiş modern minimalist tasarıma sahip adaptif dijital saat.

## Özellikler

- Dikey ve yatay yönlendirme için otomatik arayüz uyarlaması
- Yön değiştirme ve zaman güncellemelerinde akıcı animasyonlar
- 9 ön ayarlı renkle özelleştirilebilir renk şeması
- Siyah arka planlı minimalist tasarım
- Yönlendirme tespitinde histerezis kullanarak optimize edilmiş performans

## Uygulama ve Yetenekler

OrrClock sadece bir saat değil, çeşitli senaryolarda kullanılabilen çok fonksiyonlu bir zaman gösterme uygulamasıdır:

### Ev Kullanımı
- Bilgisayar veya dizüstü bilgisayarınızda masaüstü saati olarak
- Sunum veya çevrimiçi toplantılar için saat olarak
- Ev sineması için tam ekran saat olarak

### Profesyonel Kullanım
- TV stüdyolarında güncel zaman gösterimi için
- Ofis ve halka açık alanlarda bilgi ekranlarında
- Eğitim kurumlarında zaman kontrolü için

### Avantajlar
- Adaptif tasarım, uygulamanın her türlü ekranda kullanılmasına olanak tanır
- Kontrast renkler ve minimalist tasarım sayesinde yüksek okunabilirlik
- Özelleştirilebilir renkler saatin her iç mekan veya kurumsal stile uyarlanmasını sağlar

### Özelleştirme
Uygulama kolayca özelleştirilebilir:
- Renk şemaları seçimi
- Dikey veya yatay moda uyarlama

## Teknolojiler

- Python 3
- Kivy 2.2.1
- UI bileşen ayrımı ile modüler mimari

## Proje Yapısı

OrrClock/
├── main.py                 # Ana uygulama dosyası  
├── ui/                     # UI bileşenleri  
│   ├── base_clock.py       # Temel saat sınıfı  
│   ├── landscape_clock.py  # Yatay yönlendirme  
│   ├── portrait_clock.py   # Dikey yönlendirme  
│   └── settings_window.py  # Ayarlar penceresi  
├── data/                   # Ek veriler  
├── fonts/                  # Yazı tipleri  
└── requirements.txt        # Bağımlılıklar  

## Kurulum

1. Depoyu klonlayın:
```bash
git clone https://github.com/OrrStudio/OrrClock.git
cd OrrClock
```

2. Sanal ortam oluşturun ve etkinleştirin:
```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac için
```

3. Bağımlılıkları yükleyin:
```bash
pip install -r requirements.txt
```

4. Uygulamayı çalıştırın:
```bash
python main.py
```

## Sistem Gereksinimleri

- Python 3.8 veya üstü
- Kivy 2.2.1
- Minimum 512MB RAM
- Python ve Kivy'yi destekleyen herhangi bir işletim sistemi (Windows, Linux, macOS)

## Lisans

MIT License

## Yazar

Oruc Qafar - Python Geliştirici
- GitHub: [OrrStudio](https://github.com/OrrStudio)
- Email: orr888@gmail.com
