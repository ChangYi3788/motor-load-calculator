# 🏭 Vertical Winch Motor Load Calculator | 垂直捲線機構馬達負載計算工具

![Project Status](https://img.shields.io/badge/status-active-brightgreen) ![License](https://img.shields.io/badge/license-MIT-blue) ![Version](https://img.shields.io/badge/version-3.1-orange)

> A professional web-based tool designed for mechanical engineers to calculate motor power and allowable load for vertical lifting mechanisms.
> 
> 專為機械設計工程師開發的網頁計算工具，用於快速評估垂直捲線機構的馬達功率與容許荷重。

---

## 🚀 Live Demo | 線上預覽

👉 **[Launch Application / 啟動應用程式](https://changyi3788.github.io/motor-load-calculator/)**

---

## 🖼️ Screenshots | 介面預覽

| Calculation Report / 計算報告截圖範例 |
|:---:|
| <img src="screenshot-desktop.png" alt="Report Screenshot" width="500"> |

*(Note: Please ensure you have uploaded 'screenshot-desktop.png' to your repository.)*

---

## ✨ Features | 特色功能

### 🔧 Core Functions (核心功能)
* **Dual Calculation Modes (雙向計算模式)**:
    * **Power Calculation (推算功率)**: Calculate required motor power (kW/HP) based on target load.
    * **Load Calculation (推算荷重)**: Calculate maximum allowable load based on existing motor power.
* **Unit Conversion (單位切換)**: Instant toggling between **kW** and **HP** (Horsepower).
* **Real-time RPM Analysis (即時轉速分析)**: Automatically calculates output RPM and warns about dangerous speeds (>1800/3600 RPM).
* **Report Generation (報告生成)**: One-click export to a high-quality **PNG image** with an industrial-style layout.
* **Presets (快速載入)**: Built-in standard configurations for quick testing.

### 🎨 UI/UX Design (介面設計)
* **Industrial Dark Theme**: Optimized for visual comfort.
* **Fully Responsive (RWD)**: Works perfectly on Desktop and Mobile.
* **History Log**: Keeps track of recent calculations for quick comparison.

---

## 📐 Calculation Logic | 計算邏輯

This tool uses standard mechanical engineering formulas for vertical lifting:
本工具採用標準機械工程垂直捲揚公式：

### 核心物理公式 (Physical Formulas)

* **提升速度 (Velocity):**
    $$V = \frac{v_{min}}{60 \times 1000} \quad (m/s)$$
* **馬達推算功率 (Required Power):**
    $$P_{kW} = \frac{m \cdot g \cdot V}{\eta \cdot 1000} \cdot S.F.$$
* **輸出扭矩 (Output Torque):**
    $$T = m \cdot g \cdot r \quad (N\cdot m)$$

> Where $g \approx 9.81 m/s^2$, $\eta$ is transmission efficiency, $S.F.$ is safety factor, and $r$ is drum radius (meters).

---

## 🛠️ Tech Stack | 技術棧

* **Frontend**: HTML5, Vanilla JavaScript (ES6+)
* **Styling**: [Tailwind CSS](https://tailwindcss.com/)
* **Library**: [html2canvas](https://html2canvas.hertzen.com/)
* **Deployment**: GitHub Pages

---

## 📦 Installation | 安裝說明

This is a **Single File Application**. No build process is required.
1. Clone the repository.
2. Open `index.html` in any modern browser.

---

## 📄 License | 授權條款

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

**Copyright © 2025 ChangYi, Wu. All rights reserved.**

---

## 🤝 Contact | 聯絡資訊

* **Author**: ChangYi, Wu
* **GitHub**: [changyi3788](https://github.com/changyi3788)