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

Kivy फ्रेमवर्क का उपयोग करके विकसित आधुनिक मिनिमलिस्ट डिज़ाइन के साथ अनुकूली डिजिटल घड़ी।

[🇬🇧 English](../README.md) |  
[🇦🇿 Azərbaycan](README.az.md) |  
[🇹🇷 Türkçe](README.tr.md) |  
[🇸🇦 العربية](README.ar.md) |  
[🇮🇷 فارسی](README.fa.md) |  
[🇷🇺 Русский](README.ru.md) |  
[🇩🇪 Deutsch](README.de.md) |  
[🇮🇹 Italiano](README.it.md) |  
[🇪🇸 Español](README.es.md) |  
[🇫🇷 Français](README.fr.md) |  
[🇯🇵 日本語](README.ja.md) |  
[🇨🇳 中文](README.zh.md)

## विशेषताएं

- पोर्ट्रेट और लैंडस्केप ओरिएंटेशन के लिए स्वचालित इंटरफ़ेस अनुकूलन
- ओरिएंटेशन बदलने और समय अपडेट करने पर सहज एनिमेशन
- 9 पूर्व-निर्धारित रंगों के साथ अनुकूलन योग्य रंग योजना
- काले बैकग्राउंड के साथ मिनिमलिस्ट डिज़ाइन
- ओरिएंटेशन डिटेक्शन के लिए हिस्टेरिसिस का उपयोग करके अनुकूलित प्रदर्शन

## अनुप्रयोग और क्षमताएं

OrrClock केवल एक घड़ी नहीं है, यह एक बहु-कार्यात्मक समय प्रदर्शन एप्लिकेशन है जिसका उपयोग विभिन्न परिदृश्यों में किया जा सकता है:

### घरेलू उपयोग
- कंप्यूटर या लैपटॉप पर डेस्कटॉप घड़ी के रूप में
- प्रस्तुतियों या ऑनलाइन मीटिंग के लिए घड़ी के रूप में
- होम थिएटर के लिए फुल स्क्रीन घड़ी के रूप में

### व्यावसायिक उपयोग
- टीवी स्टूडियो में वर्तमान समय प्रदर्शन के लिए
- कार्यालयों और सार्वजनिक स्थानों में सूचना प्रदर्शन पर
- शैक्षिक संस्थानों में समय नियंत्रण के लिए

### लाभ
- अनुकूली डिज़ाइन किसी भी ओरिएंटेशन की स्क्रीन पर एप्लिकेशन का उपयोग करने की अनुमति देता है
- कंट्रास्ट रंगों और मिनिमलिस्ट डिज़ाइन के कारण उच्च पठनीयता
- अनुकूलन योग्य रंग किसी भी इंटीरियर या कॉर्पोरेट स्टाइल के अनुरूप घड़ी को अनुकूलित करने की अनुमति देते हैं

### अनुकूलन
एप्लिकेशन आसानी से अनुकूलन योग्य है:
- रंग योजनाओं का चयन
- पोर्ट्रेट या लैंडस्केप मोड के लिए अनुकूलन

## तकनीक

- Python 3
- Kivy 2.2.1
- UI कंपोनेंट्स के पृथक्करण के साथ मॉड्यूलर आर्किटेक्चर

## प्रोजेक्ट संरचना

OrrClock/
├── main.py                 # मुख्य एप्लिकेशन फ़ाइल  
├── ui/                     # UI कंपोनेंट्स  
│   ├── base_clock.py       # बेस क्लॉक क्लास  
│   ├── landscape_clock.py  # लैंडस्केप ओरिएंटेशन  
│   ├── portrait_clock.py   # पोर्ट्रेट ओरिएंटेशन  
│   └── settings_window.py  # सेटिंग्स विंडो  
├── data/                   # अतिरिक्त डेटा  
├── fonts/                  # फ़ॉन्ट्स  
└── requirements.txt        # निर्भरताएं  

## इंस्टॉलेशन

1. रिपॉजिटरी को क्लोन करें:
```bash
git clone https://github.com/OrrStudio/OrrClock.git
cd OrrClock
```

2. वर्चुअल एनवायरनमेंट बनाएं और सक्रिय करें:
```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac के लिए
```

3. निर्भरताएं इंस्टॉल करें:
```bash
pip install -r requirements.txt
```

4. एप्लिकेशन चलाएं:
```bash
python main.py
```

## सिस्टम आवश्यकताएं

- Python 3.8 या उच्चतर
- Kivy 2.2.1
- न्यूनतम 512MB RAM
- कोई भी ऑपरेटिंग सिस्टम जो Python और Kivy को सपोर्ट करता है (Windows, Linux, macOS)

## लाइसेंस

MIT License

## लेखक

Oruc Qafar - Python डेवलपर
- GitHub: [OrrStudio](https://github.com/OrrStudio)
- ईमेल: orr888@gmail.com
