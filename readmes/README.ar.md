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

ساعة رقمية متكيفة بتصميم عصري وبسيط، تم تطويرها باستخدام إطار عمل Kivy.

[🇬🇧 English](../README.md) |  
[🇦🇿 Azərbaycan](README.az.md) |  
[🇹🇷 Türkçe](README.tr.md) |  
[🇮🇷 فارسی](README.fa.md) |  
[🇷🇺 Русский](README.ru.md) |  
[🇩🇪 Deutsch](README.de.md) |  
[🇮🇹 Italiano](README.it.md) |  
[🇪🇸 Español](README.es.md) |  
[🇫🇷 Français](README.fr.md) |  
[🇯🇵 日本語](README.ja.md) |  
[🇨🇳 中文](README.zh.md) |  
[🇮🇳 हिंदी](README.hi.md)

## المميزات

- تكيف تلقائي للواجهة مع الاتجاه الرأسي والأفقي
- حركات سلسة عند تغيير الاتجاه وتحديث الوقت
- نظام ألوان قابل للتخصيص مع 9 ألوان مسبقة الإعداد
- تصميم بسيط مع خلفية سوداء
- أداء محسن باستخدام التباطؤ في اكتشاف الاتجاه

## التطبيقات والإمكانيات

OrrClock ليست مجرد ساعة، بل هي تطبيق متعدد الوظائف لعرض الوقت يمكن استخدامه في سيناريوهات مختلفة:

### الاستخدام المنزلي
- كساعة مكتب على جهاز الكمبيوتر أو اللابتوب
- كساعة للعروض التقديمية أو الاجتماعات عبر الإنترنت
- كساعة ملء الشاشة للمسرح المنزلي

### الاستخدام المهني
- في استوديوهات التلفزيون لعرض الوقت الحالي
- على شاشات المعلومات في المكاتب والأماكن العامة
- في المؤسسات التعليمية للتحكم في الوقت

### المزايا
- التصميم المتكيف يتيح استخدام التطبيق على شاشات بأي اتجاه
- قراءة عالية بفضل الألوان المتباينة والتصميم البسيط
- الألوان القابلة للتخصيص تتيح تكييف الساعة مع أي ديكور داخلي أو نمط مؤسسي

### التخصيص
التطبيق قابل للتخصيص بسهولة:
- اختيار مخططات الألوان
- التكيف مع الوضع الرأسي أو الأفقي

## التقنيات

- Python 3
- Kivy 2.2.1
- هيكل نمطي مع فصل مكونات واجهة المستخدم

## هيكل المشروع

OrrClock/
├── main.py                 # ملف التطبيق الرئيسي  
├── ui/                     # مكونات واجهة المستخدم  
│   ├── base_clock.py       # فئة الساعة الأساسية  
│   ├── landscape_clock.py  # الاتجاه الأفقي  
│   ├── portrait_clock.py   # الاتجاه الرأسي  
│   └── settings_window.py  # نافذة الإعدادات  
├── data/                   # البيانات الإضافية  
├── fonts/                  # الخطوط  
└── requirements.txt        # التبعيات  

## التثبيت

1. استنساخ المستودع:
```bash
git clone https://github.com/OrrStudio/OrrClock.git
cd OrrClock
```

2. إنشاء وتفعيل البيئة الافتراضية:
```bash
python -m venv venv
source venv/bin/activate  # لنظام Linux/Mac
```

3. تثبيت التبعيات:
```bash
pip install -r requirements.txt
```

4. تشغيل التطبيق:
```bash
python main.py
```

## متطلبات النظام

- Python 3.8 أو أحدث
- Kivy 2.2.1
- الحد الأدنى 512MB RAM
- أي نظام تشغيل يدعم Python و Kivy (Windows, Linux, macOS)

## الترخيص

MIT License

## المؤلف

Oruc Qafar - مطور Python
- GitHub: [OrrStudio](https://github.com/OrrStudio)
- البريد الإلكتروني: orr888@gmail.com

</div>
