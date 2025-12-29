# 🏭 Vertical Winch Motor Load Calculator | 垂直捲線機構馬達負載計算工具

![Project Status](https://img.shields.io/badge/status-active-brightgreen) ![License](https://img.shields.io/badge/license-MIT-blue) ![Version](https://img.shields.io/badge/version-3.0-orange)

> A professional web-based tool designed for mechanical engineers to calculate motor power and allowable load for vertical lifting mechanisms.
> 
> 專為機械設計工程師開發的網頁計算工具，用於快速評估垂直捲線機構的馬達功率與容許荷重。

---

## 🚀 Live Demo | 線上預覽

👉 **[Click here to use the tool / 點擊此處使用工具](https://changyi3788.github.io/motor-load-calculator/)**

*(Replace the link above after you activate GitHub Pages / 請在啟用 GitHub Pages 後替換上方連結)*

---

## 🖼️ Screenshots | 介面預覽

| Desktop / PC 介面 | Mobile / 手機介面 |
|:---:|:---:|
| <img src="screenshot-desktop.png" alt="Desktop View" width="400"> | <img src="screenshot-mobile.png" alt="Mobile View" width="200"> |

*(Note: Please upload screenshots to your repository and update filenames / 請上傳截圖至您的倉庫並更新檔名)*

---

## ✨ Features | 特色功能

### 🔧 Core Functions (核心功能)
* **Dual Calculation Modes (雙向計算模式)**:
    * **Power Calculation (推算功率)**: Calculate required motor power (kW/HP) based on target load.
    * **Load Calculation (推算荷重)**: Calculate maximum allowable load based on existing motor power.
* **Unit Conversion (單位切換)**: Instant toggling between **kW** and **HP** (Horsepower).
* **Real-time RPM Analysis (即時轉速分析)**: Automatically calculates output RPM and warns about dangerous speeds (>1800/3600 RPM).
* **Report Generation (報告生成)**: One-click export to a high-quality **PNG image** with a clean, industrial-style layout, perfect for documentation.

### 🎨 UI/UX Design (介面設計)
* **Industrial Dark Theme (工業深色主題)**: Optimized for visual comfort in various lighting conditions.
* **Fully Responsive (RWD 響應式)**: Works perfectly on Desktop, Tablets, and Mobile phones.
* **Input Optimization (輸入優化)**: Numeric keypads are automatically triggered on mobile devices.
* **Visual Feedback (視覺回饋)**: Clear error messages and interactive button states.

---

## 📐 Calculation Logic | 計算邏輯

This tool uses standard mechanical engineering formulas for vertical lifting:
本工具採用標準垂直捲揚機構計算公式：

### 1. Velocity (提升速度換算)
$$V (m/s) = \frac{Speed (mm/min)}{60 \times 1000}$$

### 2. Motor Power (馬達功率)
$$P (kW) = \frac{Load (kg) \times 9.8 \times V (m/s)}{1000 \times \eta} \times S.F.$$

* **$\eta$ (Efficiency)**: Gear efficiency (e.g., Worm Gear 70%, Cycloid 90%).
* **S.F. (Safety Factor)**: Typically 1.5 to 2.0 depending on the application.

---

## 🛠️ Tech Stack | 技術棧

* **Core**: HTML5, Vanilla JavaScript (ES6+)
* **Styling**: [Tailwind CSS](https://tailwindcss.com/) (CDN)
* **Library**: [html2canvas](https://html2canvas.hertzen.com/) (For screenshot generation)
* **Deployment**: GitHub Pages

---

## 📦 Installation & Usage | 安裝與使用

Since this is a **Single File Application**, no build process is required.
由於本專案為單一文件應用，無需複雜的建置過程。

### Method 1: Run Locally (本地運行)
1.  Clone this repository:
    ```bash
    git clone [https://github.com/YourUsername/motor-load-calculator.git](https://github.com/YourUsername/motor-load-calculator.git)
    ```
2.  Open `index.html` directly in your browser.

### Method 2: GitHub Pages (雲端部署)
1.  Fork or Push this repository to your GitHub.
2.  Go to **Settings** > **Pages**.
3.  Select `main` branch as source and Save.

---

## 📝 License | 授權條款

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
本專案採用 MIT 授權條款，詳情請參閱 [LICENSE](LICENSE) 文件。

**Copyright © 2025 ChangYi, Wu. All rights reserved.**

---

## 🤝 Contact | 聯絡資訊

If you have any questions or suggestions, feel free to open an Issue.
如有任何問題或建議，歡迎提交 Issue。

* **Author**: ChangYi, Wu