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

<div dir="rtl">

ساعت دیجیتال تطبیق‌پذیر با طراحی مینیمال مدرن، توسعه یافته با فریم‌ورک Kivy.

[🇬🇧 نسخه انگلیسی](README.md)

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

</div>