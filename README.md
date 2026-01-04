# ⚙️ Motor Load Calculator (馬達負載計算系統)
### Precision Engineering Calculation Tool - System V4.7

![License](https://img.shields.io/badge/license-MIT-green.svg)
[**English**](#english) | [**中文說明**](#中文說明)

---

## English

### 🌟 Project Overview
A professional engineering tool designed for **Vertical Winch** systems. It assists engineers in calculating required motor power, torque, and selecting standard motor specifications with an intuitive industrial-grade interface.

🔗 **Live Demo:** [Motor Load Calculator](https://changyi3788.github.io/motor-load-calculator/)

### 🚀 Key Features (V4.7)
- **Dual Mode Calculation**: Toggle between "Calculate Power" and "Calculate Allowable Load".
- **Dual Torque Analysis**: Displays both **Load-side Torque** (Drum) and **Motor-side Torque** (Reflected).
- **Smart Motor Recommendation**: Matches calculated results with standard motor catalogs (0.125HP to 30HP).
- **Safety Safeguards**: 
    - Auto-warning for high RPM (>1800).
    - "CUSTOM" alert for power requirements exceeding 30HP.
- **Report Export**: One-click PNG report generation via `html2canvas`.

---

## 中文說明

### 🌟 專案簡介
這是一個專為 **垂直捲線機構** 設計的專業工程工具。透過直覺的工業風介面，協助工程師精確計算所需的馬達功率、扭矩，並自動推薦適合的標準馬達規格。

🔗 **線上試算：** [馬達負載計算系統](https://changyi3788.github.io/motor-load-calculator/)

### 🚀 核心功能 (V4.7)
- **雙向計算模式**：支援「算功率」與「反算容許荷重」。
- **精密扭矩分析**：同時顯示 **負載端 (捲筒)** 與 **馬達端 (經減速比與效率折算)** 的扭矩數值。
- **智能選型推薦**：自動比對標準馬達規格表 (0.125HP ~ 30HP) 並建議馬達極數。
- **安全防護機制**：
    - 高轉速警示 (超過 1800 RPM 時提示)。
    - 超規格提示 (超過 30HP 時自動標記為 **CUSTOM 特殊規格**)。
- **專業報告導出**：整合 `html2canvas` 技術，一鍵生成 PNG 計算報告。

---

## ⚖️ License / 授權說明
This project is licensed under the **MIT License**. See the [LICENSE](./LICENSE) file for details.
本專案採用 **MIT 授權條款**。詳情請參閱 [LICENSE](./LICENSE) 檔案。

---

## 📅 Change Log (更新歷程)
- **V4.7** (Latest) - Added Dual Torque display and Over-limit safeguard.
- **V4.6** - Multilingual support (EN/ZH) & UI animations.
- **V4.0** - Tailwind CSS UI overhaul & Report export function.

## 👥 Author
- **Developer**: ChangYi (長益)
- **GitHub**: [changyi3788](https://github.com/changyi3788)

---

> **Disclaimer / 免責聲明**: 
> This tool is for design reference only. Please consult motor suppliers for final specifications.
> 本工具提供之數據僅供設計參考，實際選型請務必諮詢馬達供應商。
