# 垂直捲線機構馬達負載計算系統 | Vertical Winch Motor Load Calculation System (V4.3 Pro)

![Version](https://img.shields.io/badge/Version-4.3%20Pro-f59e0b)
![License](https://img.shields.io/github/license/changyi3788/motor-load-calculator?color=emerald)
![PWA](https://img.shields.io/badge/PWA-Ready-blue)

[中文介紹](#中文介紹) | [English Description](#english-description)

---

## 中文介紹

這是一款專為機械工程師與自動化設備設計人員開發的專業計算工具。針對「垂直捲線機構」進行動力學優化，支援功率與荷重的雙向精確推算。

🔗 **線上使用：** [點此開啟系統](https://changyi3788.github.io/motor-load-calculator/)

### 🚀 核心功能
- **雙向推算模式**：
  - **推算功率**：輸入目標荷重，自動計算理論功率並推薦標準馬達規格。
  - **推算荷重**：輸入現有馬達功率，回推系統容許的最大荷重。
- **智能型選型建議**：自動比對標準馬達規格（HP/kW），並根據馬達轉速自動建議最佳極數（2P-8P）。
- **高風險預警**：當馬達轉速（RPM）過高時，系統自動彈出安全性警告。
- **一鍵導出報告**：內建 `html2canvas` 技術，可將計算結果導出為高解析度圖卡。
- **PWA 行動支持**：支援安裝至手機桌面，適合工地或工廠現場即時使用。

---

## English Description

A professional engineering tool designed for mechanical engineers and automation designers, optimized for **vertical winch mechanisms**. It supports high-precision bi-directional calculations for motor power and load capacity.

🔗 **Live Demo:** [Open System](https://changyi3788.github.io/motor-load-calculator/)

### 🚀 Key Features
- **Bi-directional Calculation**:
  - **Power Calc**: Input target load to get theoretical power and recommended motor specs.
  - **Load Calc**: Input motor power to calculate the maximum allowable system load.
- **Smart Specification Matching**: Automatically matches standard motor sizes (HP/kW) and suggests the optimal number of Poles (2P-8P).
- **Safety Alert Mechanism**: Triggers a high-RPM warning if the calculated motor speed exceeds safety thresholds.
- **Export Report**: Integrated with `html2canvas` to export calculation results as high-resolution images for documentation.
- **PWA Ready**: Can be installed on mobile devices for offline-like experience on-site or on the factory floor.

---

## 🛠️ 技術棧 | Tech Stack
- **Frontend**: HTML5, Tailwind CSS (JIT mode)
- **Library**: [html2canvas](https://html2canvas.hertzen.com/)
- **UX/UI**: Industrial Dashboard UI, Progressive Web App (PWA)

## 📱 安裝方式 | Installation (PWA)
1. Open the URL in **Chrome** (Android) or **Safari** (iOS).
2. Select **"Add to Home Screen"** or **"Install App"** from the browser menu.
3. Access the system as a standalone App from your dashboard.

## 📄 免責聲明 | Disclaimer
本軟體計算結果僅供參考。實際設計時應考量機構磨耗、慣性力及環境係數。
Calculated results are for reference only. Practical designs should account for friction loss, inertia, and environmental factors.

---
**Developer**: ChangYi  
**Last Updated**: 2025
