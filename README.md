# ⚙️ 垂直捲線機構負載計算系統 (Vertical Winch Load System)
### Precision Engineering Calculation Tool - System V4.7

![Build Status](https://img.shields.io/badge/Status-Live-emerald)
![Version](https://img.shields.io/badge/Version-4.7-blue)
![Language](https://img.shields.io/badge/Language-ZH%20%2F%20EN-orange)

這是一個專為自動化設備、舞台機械、工業捲揚機設計的專業計算工具。透過 V4.7 版本的優化，能快速協助工程師進行馬達功率選型與負載驗證。

🔗 **線上即時計算：** [點此開啟系統](https://changyi3788.github.io/motor-load-calculator/)

---

## 🚀 核心優化：V4.7 更新重點
- **【新增】雙重扭矩顯示**：同時呈現「捲筒負載端」與「馬達輸出端」扭矩，方便減速機選型。
- **【新增】規格防呆機制**：計算功率超過 30HP 標準範圍時，自動標記為 **CUSTOM (特殊規格)**。
- **【優化】UI 響應速度**：針對行動裝置輸入法與報表生成進行了效能優化。
- **【修正】單位換算邏輯**：強化了 mm/min 與 m/s 之間的轉換精確度。

---

## 🛠️ 功能特點 (Features)

### 1. 雙模式計算 (Dual Calculation Modes)
- **Power Mode (算功率)**：依據目標荷重 $W$，計算所需理論功率與建議馬達等級。
- **Load Mode (算荷重)**：依據現有馬達馬力，反向推算系統在安全係數下可承載的最大重量。

### 2. 規格推薦系統 (Smart Recommendation)
- 自動對比標準馬達清單 (0.125HP ~ 30HP)。
- 依據計算轉速自動判定建議極數 (**2P / 4P / 6P / 8P**)。

### 3. 工業級報表導出 (Professional Export)
- 內建報表區塊，可一鍵將計算結果轉換為 PNG 圖檔，方便附加於設計圖紙或技術文件中。

---

## 📐 計算物理邏輯 (Physics Logic)

本系統依據以下核心公式進行撰寫，確保計算結果具備工程參考價值：

- **馬達轉速 (RPM)**：
  $$N_m = \frac{V}{\pi \cdot D} \cdot i$$
- **理論功率 (Power)**：
  $$P_{kW} = \frac{F \cdot V}{\eta \cdot 1000} \cdot S.F.$$
- **馬達端扭矩 (Motor Torque)**：
  $$T_m = \frac{F \cdot R}{i \cdot \eta}$$

---

## 💻 技術開發 (Technical Stack)

- **Layout**: Tailwind CSS (JIT mode)
- **Icons & Fonts**: JetBrains Mono, Noto Sans TC
- **Core**: Vanilla JavaScript (Object-Literal Pattern)
- **Library**: html2canvas v1.4.1

---

## 📅 版本更新歷程 (Change Log)

- **V4.7** (2025/01) - 加入雙扭矩顯示、馬達選型防呆提示。
- **V4.6** - 新增多國語系 (EN/ZH) 切換功能、強化 UI 動畫。
- **V4.0** - 引入 Tailwind CSS 介面重構，支援報表截圖導出。
- **V1.0** - 基礎功率計算功能上線。

---

## 👥 作者資訊 (Author)
- **Developer**: ChangYi (長益)
- **Project Link**: [https://github.com/changyi3788/motor-load-calculator](https://github.com/changyi3788/motor-load-calculator)

---

> **Disclaimer (免責聲明)**: 
> 本計算器提供之數據僅供設計初期參考使用。實際工程建置請務必聯繫專業馬達商進行負載曲線確認，並考慮馬達啟動扭矩 (Starting Torque) 與過載係數。

