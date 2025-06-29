# 🗑️ Trash Classify - 垃圾影像分類專案

一個基於深度學習的多類別垃圾分類模型，透過 TensorFlow 與 InceptionV3 預訓練模型實現，可辨識塑膠、玻璃、紙類等垃圾影像類別。

![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange)  
![License](https://img.shields.io/badge/license-MIT-blue)

---

## 📦 專案簡介

本專案利用遷移學習技術，將在 ImageNet 上預訓練好的 InceptionV3 模型作為特徵萃取器，搭配自定義輸出層進行垃圾圖片分類。主要目的是快速建立一個準確率高、可視化且易於擴充的分類系統。

---

## 🧠 主要技術概念

- **監督式學習**（Supervised Learning）
- **遷移學習**（Transfer Learning）與微調（Fine-tuning）
- **影像資料增強**（Data Augmentation）
- **TensorBoard** 訓練過程可視化
- **模型保存與預測結果視覺化**

---
