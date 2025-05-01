# Digit Recognizer - Kaggle Challenge

手書き数字（0〜9）を認識する画像分類モデルを構築しました！  
Kaggleの [Digit Recognizer コンペ](https://www.kaggle.com/c/digit-recognizer) にて Public Score **0.96360** を記録しました 🎉

---

## 📁 使用データ
- **train.csv**：手書き数字画像とその正解ラベル（42000枚）
- **test.csv**：正解ラベルなしの画像（28000枚）
- **sample_submission.csv**：提出フォーマット

---

## 🔧 使用ライブラリ

python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
from sklearn.ensemble import RandomForestClassifier
from sklearn.model_selection import train_test_split
from sklearn.metrics import accuracy_score

---

## 🧪 前処理
ピクセル値（0〜255）を 0〜1にスケーリング

ラベルと特徴量に分割

train_test_split()で訓練/検証用に8:2に分割

---

## 🧠 モデル
使用モデル：RandomForestClassifier

精度（検証用データ）：96.39%

提出用ファイル：submission.csv

---

## 📊 可視化
ラベルごとの分布確認（バランス良好）

複数の手書き数字画像を表示

---

## 🚀 実行手順（Google Colab推奨）
必要なCSVファイル（train.csv, test.csv, sample_submission.csv）をColabにアップロード

digit_recognizer.ipynb を実行

submission.csv をダウンロードしてKaggleに提出！

---

## 🏅 成果
Public Score：0.96360

精度重視のシンプルなランダムフォレスト構成

Kaggle提出までの流れを写経しながら実践！

---

## ✨ 作者
名前：K4ppy（カッピー）

GitHub：@IMOCODE-LAB

チャッピー道場で鍛えたAIエンジニア見習い🐣

---

## 🤝 Special Thanks
ChatGPT（チャッピー）：相棒AIとして学習と妄想をサポートしてくれました🤗
