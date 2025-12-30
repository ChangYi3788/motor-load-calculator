# 垂直捲線機構馬達負載計算系統 (V4.6)
## Vertical Winch Motor Load Calculation System

[![GitHub Pages](https://img.shields.io/badge/Status-Live-emerald?style=for-the-badge&logo=github)](https://changyi3788.github.io/motor-load-calculator/)
[![Version](https://img.shields.io/badge/Version-4.6-blue?style=for-the-badge)](https://github.com/changyi3788/motor-load-calculator)



## 🌟 簡介 | Introduction

### [中文]
這是一個專為工程現場設計的 **馬達負載計算工具**。針對捲線機構、吊掛系統等垂直提升場景提供精確的物理運算。本工具優化了行動裝置的操作體驗，支援中英文雙語切換，並具備一鍵導出計算報告功能。

### [English]
A specialized **Motor Load Calculation Tool** designed for engineering field use. It provides precise physical calculations for vertical lifting scenarios such as winch mechanisms and hoist systems. Optimized for mobile devices, the tool supports bilingual switching (Chinese/English) and features a one-click calculation report export.

---

## 🚀 主要功能 | Core Features

* **雙向模式切換 | Dual Calculation Modes**:
    * **算功率 (Power Mode)**: 根據目標荷重推算馬達所需功率與建議規格。 / Calculate required motor power based on target load.
    * **算荷重 (Load Mode)**: 根據馬達功率推算系統安全容許荷重。 / Calculate allowable load capacity based on motor power.
* **智慧選型推薦 | Smart Recommendation**:
    * 自動對比標準馬達功率表（HP/kW），並根據馬達轉速建議適用極數 (2P-8P)。 / Automatically matches standard motor tables and suggests pole counts (2P-8P).
* **物理邏輯精確 | Engineering Precision**:
    * 考慮減速比、機構效率 (η) 及安全係數 (S.F.)。 / Includes gear ratio, mechanical efficiency (η), and safety factor (S.F.).
* **行動優先設計 | Mobile First Design**:
    * 加大觸控熱區，適合工地單手操作。 / Enlarged touch targets for one-handed operation in the field.
* **報告導出 | Report Export**:
    * 一鍵將計算結果轉化為 PNG 圖檔。 / Instant PNG report generation via `html2canvas`.

---

## ⚙️ 物理公式 | Physical Logic

本系統基於以下核心公式進行運算：
This system is built upon the following physical principles:

1. **馬達端轉速 | Motor RPM ($n_{motor}$)**:
   $$n_{motor} = \frac{v}{2\pi r} \times i$$
   *(v: 線速度 linear speed, r: 半徑 radius, i: 減速比 ratio)*

2. **理論功率 | Theoretical Power ($P_{kW}$)**:
   $$P (kW) = \left( \frac{m \cdot g \cdot v}{\eta \cdot 1000} \right) \times S.F.$$
   *(m: 荷重 load, g: 重力加速度 9.80665, η: 效率 efficiency)*

3. **輸出轉矩 | Output Torque ($T_{Nm}$)**:
   $$T = m \cdot g \cdot (r/1000)$$

---

## 🛠️ 技術棧 | Tech Stack

* **Frontend**: HTML5, Tailwind CSS
* **Typography**: JetBrains Mono, Noto Sans TC
* **Library**: [html2canvas](https://html2canvas.hertzen.com/)
* **Deployment**: GitHub Pages

---

## 📖 使用說明 | Instructions

1.  **輸入參數 | Input Parameters**: 填入半徑、速度及減速比。 / Enter radius, speed, and gear ratio.
2.  **設定環境 | Configuration**: 選擇傳動效率及安全係數。 / Select mechanical efficiency and S.F.
3.  **執行計算 | Calculate**: 輸入數值後點擊「執行計算」。 / Enter values and click "Calculate".
4.  **導出報告 | Export**: 點擊「導出報告」存為圖片。 / Click "Export" to save the result as an image.

---
© 2025 ChangYi Engineering Tools.
