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

Kivyフレームワークを使用して開発された、モダンでミニマルなデザインの適応型デジタル時計。

[🇬🇧 English Version](README.md)

## 特徴

- 縦横の向きに自動適応するインターフェース
- 向きの変更と時刻更新時の滑らかなアニメーション
- 9つのプリセットカラーでカスタマイズ可能なカラースキーム
- 黒背景のミニマルデザイン
- ヒステリシスを使用した向き検出の最適化されたパフォーマンス

## アプリケーションと機能

OrrClockは単なる時計ではなく、様々なシナリオで使用できる多機能な時間表示アプリケーションです：

### 家庭での使用
- コンピュータやラップトップのデスクトップ時計として
- プレゼンテーションやオンラインミーティングの時計として
- ホームシアターのフルスクリーン時計として

### プロフェッショナルな使用
- テレビスタジオでの現在時刻表示
- オフィスや公共スペースの情報ディスプレイ
- 教育機関での時間管理

### 利点
- 適応型デザインにより、あらゆる向きの画面で使用可能
- コントラストの効いた色とミニマルなデザインによる高い可読性
- カスタマイズ可能な色により、あらゆるインテリアや企業スタイルに適応

### カスタマイズ
アプリケーションは簡単にカスタマイズできます：
- カラースキームの選択
- 縦向きまたは横向きモードへの適応

## 技術

- Python 3
- Kivy 2.2.1
- UIコンポーネントを分離したモジュラーアーキテクチャ

## プロジェクト構造

OrrClock/
├── main.py                 # メインアプリケーションファイル  
├── ui/                     # UIコンポーネント  
│   ├── base_clock.py       # 時計基本クラス  
│   ├── landscape_clock.py  # 横向き  
│   ├── portrait_clock.py   # 縦向き  
│   └── settings_window.py  # 設定ウィンドウ  
├── data/                   # 追加データ  
├── fonts/                  # フォント  
└── requirements.txt        # 依存関係  

## インストール

1. リポジトリをクローン：
```bash
git clone https://github.com/OrrStudio/OrrClock.git
cd OrrClock
```

2. 仮想環境の作成と有効化：
```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac用
```

3. 依存関係のインストール：
```bash
pip install -r requirements.txt
```

4. アプリケーションの実行：
```bash
python main.py
```

## システム要件

- Python 3.8以上
- Kivy 2.2.1
- 最小512MB RAM
- PythonとKivyをサポートする任意のオペレーティングシステム（Windows、Linux、macOS）

## ライセンス

MIT License

## 作者

Oruc Qafar - Pythonデベロッパー
- GitHub: [OrrStudio](https://github.com/OrrStudio)
- メール: orr888@gmail.com