# 🏎️ 2021 Abu Dhabi GP Lap Time Analysis

![Python](https://img.shields.io/badge/Python-3.13-blue)
![FastF1](https://img.shields.io/badge/FastF1-3.x-orange)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.x-green)

## 📌 プロジェクト概要
このプロジェクトは、**2021年F1アブダビGP** における  
マックス・フェルスタッペンとルイス・ハミルトンのラップタイムを比較・可視化する分析です。  
FastF1ライブラリを用いて公式データを取得し、タイヤ戦略やピットインの影響をグラフで表現します。

---

## 📂 ディレクトリ構成
# f1-lap-analysis/ ├── 2021_AbuDhabiGP_LapTimeComparison.ipynb  
# 分析ノートブック ├── images/                                   
# グラフ画像保存用 ├── cache/                                   
# FastF1キャッシュ └── README.md

---

## ⚙️ 使用技術
- Python 3.13
- [FastF1](https://theoehrly.github.io/Fast-F1/)
- Matplotlib
- Pandas

---

## 🚀 セットアップ方法
1. リポジトリをクローン
   ```bash
   git clone https://github.com/ユーザー名/f1-lap-analysis.git
   cd f1-lap-analysis
   - 仮想環境を作成・有効化
2. 	仮想環境を作成・有効化
   ```bash
   python -m venv .venv
   .\.venv\Scripts\activate  # Windows
```
3.  必要パッケージをインストール
   ```bash
   pip install -r requirements.txt
```
4.  ※requirements.txtがない場合は手動で：
   ```bash
   pip install fastf1 pandas matplotlib
```
## 📊 実行方法
1.  Jupyter Labを起動
   ```
jupyter lab
```
2.  2021_AbuDhabiGP_LapTimeComparison.ipynb を開く
3.  セルを順に実行すると、ラップタイム比較グラフが表示されます
## 📈 分析ポイント
・ タイヤコンパウンドごとのラップタイム推移
・ ピットインのタイミングと戦略の違い
・ 最終周逆転の可視化
## 📜 ライセンス
このプロジェクトは MIT License のもとで公開されています。
