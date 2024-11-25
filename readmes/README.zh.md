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

一个使用Kivy框架开发的具有现代简约设计的自适应数字时钟。

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
[🇮🇳 हिंदी](README.hi.md)

## 特点

- 自动适应纵向和横向界面
- 方向切换和时间更新时的流畅动画
- 可自定义的配色方案，预设 9 种颜色
- 黑色背景的简约设计
- 使用滞后检测优化的方向识别性能

## 应用场景和功能

OrrClock 不仅仅是一个时钟，它是一个可以在各种场景中使用的多功能时间显示应用：

### 家庭使用
- 作为电脑或笔记本上的桌面时钟
- 作为演示或在线会议的时钟
- 作为家庭影院的全屏时钟

### 专业使用
- 在电视演播室显示当前时间
- 在办公室和公共场所的信息显示屏上
- 在教育机构进行时间控制

### 优势
- 自适应设计允许在任何方向的屏幕上使用应用
- 对比度颜色和简约设计确保高可读性
- 可自定义颜色适应任何室内或企业风格

### 自定义
应用程序易于自定义：
- 选择颜色方案
- 适应纵向或横向模式

## 技术

- Python 3
- Kivy 2.2.1
- 具有 UI 组件分离的模块化架构

## 项目结构

```
OrrClock/
├── main.py                 # 主应用程序文件
├── ui/                     # UI组件
│   ├── base_clock.py       # 基础时钟类
│   ├── landscape_clock.py  # 横向布局
│   ├── portrait_clock.py   # 纵向布局
│   └── settings_window.py  # 设置窗口
├── data/                   # 附加数据
├── fonts/                  # 字体
└── requirements.txt        # 依赖项
```

## 安装

1. 克隆仓库：
```bash
git clone https://github.com/OrrStudio/OrrClock.git
cd OrrClock
```

2. 创建并激活虚拟环境：
```bash
python -m venv venv
source venv/bin/activate  # 适用于 Linux/Mac
```

3. 安装依赖项：
```bash
pip install -r requirements.txt
```

4. 运行应用程序：
```bash
python main.py
```

## 系统要求

- Python 3.8 或更高版本
- Kivy 2.2.1
- 最小 512MB RAM
- 任何支持 Python 和 Kivy 的操作系统（Windows、Linux、macOS）

## 许可证

MIT License

## 作者

Oruc Qafar - Python 开发者
- GitHub: [OrrStudio](https://github.com/OrrStudio)
- 邮箱: orr888@gmail.com
