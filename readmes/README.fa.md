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

ساعت دیجیتال تطبیق‌پذیر با طراحی مدرن و مینیمالیستی، توسعه یافته با استفاده از فریم‌ورک Kivy.

[🇬🇧 English](../README.md) |  
[🇦🇿 Azərbaycan](README.az.md) |  
[🇹🇷 Türkçe](README.tr.md) |  
[🇸🇦 العربية](README.ar.md) |  
[🇷🇺 Русский](README.ru.md) |  
[🇩🇪 Deutsch](README.de.md) |  
[🇮🇹 Italiano](README.it.md) |  
[🇪🇸 Español](README.es.md) |  
[🇫🇷 Français](README.fr.md) |  
[🇯🇵 日本語](README.ja.md) |  
[🇨🇳 中文](README.zh.md) |  
[🇮🇳 हिंदी](README.hi.md)

## ویژگی‌ها

- تطبیق خودکار رابط کاربری برای جهت عمودی و افقی
- انیمیشن‌های روان هنگام تغییر جهت و به‌روزرسانی زمان
- طرح رنگی قابل تنظیم با 9 رنگ از پیش تعیین شده
- طراحی مینیمال با پس‌زمینه مشکی
- عملکرد بهینه‌سازی شده با استفاده از هیسترزیس برای تشخیص جهت

## کاربردها و قابلیت‌ها

OrrClock فقط یک ساعت نیست، یک برنامه چندمنظوره نمایش زمان است که می‌تواند در سناریوهای مختلف استفاده شود:

### استفاده خانگی
- به عنوان ساعت رومیزی روی کامپیوتر یا لپ‌تاپ
- به عنوان ساعت برای ارائه‌ها یا جلسات آنلاین
- به عنوان ساعت تمام صفحه برای سینمای خانگی

### استفاده حرفه‌ای
- در استودیوهای تلویزیونی برای نمایش زمان فعلی
- روی نمایشگرهای اطلاعات در دفاتر و فضاهای عمومی
- در موسسات آموزشی برای کنترل زمان

### مزایا
- طراحی تطبیق‌پذیر امکان استفاده از برنامه در نمایشگرهای با هر جهتی را فراهم می‌کند
- خوانایی بالا به لطف رنگ‌های متضاد و طراحی مینیمال
- رنگ‌های قابل تنظیم امکان تطبیق ساعت با هر دکوراسیون داخلی یا سبک شرکتی را فراهم می‌کند

### شخصی‌سازی
برنامه به راحتی قابل شخصی‌سازی است:
- انتخاب طرح‌های رنگی
- تطبیق با حالت عمودی یا افقی

## تکنولوژی‌ها

- Python 3
- Kivy 2.2.1
- معماری ماژولار با جداسازی اجزای رابط کاربری

## ساختار پروژه

```
OrrClock/
├── main.py                 # فایل اصلی برنامه
├── ui/                     # اجزای رابط کاربری
│   ├── base_clock.py       # کلاس پایه ساعت
│   ├── landscape_clock.py  # جهت افقی
│   ├── portrait_clock.py   # جهت عمودی
│   └── settings_window.py  # پنجره تنظیمات
├── data/                   # داده‌های اضافی
├── fonts/                  # فونت‌ها
└── requirements.txt        # وابستگی‌ها
```

## نصب

1. کلون کردن مخزن:
```bash
git clone https://github.com/OrrStudio/OrrClock.git
cd OrrClock
```

2. ایجاد و فعال‌سازی محیط مجازی:
```bash
python -m venv venv
source venv/bin/activate  # برای Linux/Mac
```

3. نصب وابستگی‌ها:
```bash
pip install -r requirements.txt
```

4. اجرای برنامه:
```bash
python main.py
```

## ساخت APK برای اندروید با استفاده از Buildozer

برای ساخت یک APK با استفاده از Buildozer، مراحل زیر را دنبال کنید:

1. **نصب Buildozer**:
   دستورالعمل‌های نصب را از [مستندات Buildozer](https://buildozer.readthedocs.io/en/latest/installation.html) دنبال کنید.

2. **ساخت APK**:
   دستور زیر را برای ساخت APK اجرا کنید:
   ```bash
   buildozer android debug
   ```
   APK ساخته شده در دایرکتوری `bin/` پروژه شما قرار خواهد گرفت.

3. **استقرار در دستگاه** (اختیاری):
   اگر یک دستگاه اندروید متصل دارید، می‌توانید APK را مستقیماً با استفاده از دستور زیر مستقر کنید:
   ```bash
   buildozer android deploy run
   ```

## نیازمندی‌های سیستم

- Python 3.8 یا بالاتر
- Kivy 2.2.1
- حداقل 512MB RAM
- هر سیستم عاملی که از Python و Kivy پشتیبانی کند (Windows, Linux, macOS)

## مجوز

MIT License

## نویسنده

Oruc Qafar - توسعه‌دهنده Python
- GitHub: [OrrStudio](https://github.com/OrrStudio)
- ایمیل: orr888@gmail.com
