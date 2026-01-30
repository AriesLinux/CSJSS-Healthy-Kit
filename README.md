<div align="center">

# 🏥 CSJ Health Connect on [EazyUI-Framework]
## By CSJ Tech (明愛聖若瑟中學)
<img src="https://img.icons8.com/fluent/150/heart-health.png" width="90" alt="School Logo">
<img src="https://img.icons8.com/fluent/150/heart-health.png" width="120" alt="App Logo">

![Platform](https://img.shields.io/badge/Platform-Android-green?style=for-the-badge&logo=android&logoColor=white)
![Engine](https://img.shields.io/badge/Engine-MIT_App_Inventor-orange?style=for-the-badge)
![UI](https://img.shields.io/badge/UI_Arch-EazyUI-blue?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-lightgrey?style=for-the-badge)

<p align="center">
  <strong>基於 EazyUI 自研架構與 MIT App Inventor 開發的校園智慧健康監測系統</strong>
</p>

[功能簡介](#-主要功能) | [介面架構](#-eazyui-自研架構) | [開發團隊](#-開發團隊與鳴謝)

</div>

---

## 🖥️ 專案規格 (Project Specs)

| 項目 (Component) | 規格 (Model) | 備註 (Notes) |
| :--- | :--- | :--- |
| **開發平台** | [MIT App Inventor 2] | 視覺化邏輯開發 |
| **介面架構** | [EazyUI Framework] | **校內自研**，底層組件優化 |
| **適用設備** | [Android 8.0 或以上] | 需具備藍牙與感測器支援 |
| **核心技術** | [Bluetooth LE / TinyDB] | 實現數據即時傳輸與存儲 |

## 📊 運行狀態 (Status)

### ✅ 正常運作 (Working)
* [x] **EazyUI 全域渲染** (自適應佈局、圓角按鈕與統一配色)
* [x] **氧仔 (Oxy)**: 血氧監測模組 (實時數據與飽和度分析)
* [x] **度度 (Tempy)**: 溫度工具模組 (高精準度體溫預警)
* [x] **脈動仔 (Pulso)**: 血壓工具模組 (脈搏追蹤與歷史紀錄)
* [x] **數據持久化**: 紀錄歷史量測數據不遺失

### ❌ 待開發 (Roadmap)
* [ ] [Firebase 雲端同步]*
* [ ] [多語言 UI 切換]*

---

## ✨ EazyUI 自研架構 (The EazyUI Framework)

**EazyUI** 是我們針對 MIT App Inventor 原生介面美觀度不足所開發的一套解決方案：

1.  **組件封裝**: 透過特殊的背景圖形切割與 CSS-like 邏輯，實現了流暢的圓角與陰影效果。
2.  **視覺語言**: 採用校園健康綠為基調，並將 UI 元素與吉祥物交互深度整合。
3.  **流暢體驗**: 優化了 Screen 切換邏輯，減少在低配 Android 設備上的載入感。

---

## 🛡️ 三大健康守護者 (The Health Guardians)

本程式將量測功能具象化為三位守護吉祥物，讓健康量測更具親和力：

* **🍀 氧仔 (Oxy)**
  - **負責工具**: 血氧量測。
  - **互動**: 當血氧低於 95% 時，氧仔會顯示擔心的表情並提醒深呼吸。
* **🌡️ 度度 (Tempy)**
  - **負責工具**: 體溫量測。
  - **互動**: 內建校園發燒警戒線，即時判斷是否需要前往校醫室。
* **💓 脈動仔 (Pulso)**
  - **負責工具**: 血壓與脈搏。
  - **互動**: 以視覺化的波形動效配合脈搏跳動，直觀感受心血管律動。

---

## ⚙️ 設置與權限 (Settings & Permissions)

**為了確保數據量測準確，請檢查以下設置：**

* **停用 (Disable):**
    * 電池過度優化 (防止背景量測被中斷)
* **啟用 (Enable):**
    * **Bluetooth (藍牙)**: 用於與量測硬體連線。
    * **Location (定位)**: Android 系統掃描藍牙裝置之必要權限。
    * **Storage (存儲)**: 用於讀寫健康日誌。

---

## 👏 開發團隊與鳴謝 (Credits)

* **主辦學校**: [明愛聖若瑟中學](https://www.csj.edu.hk/)
* **核心開發**: EazyUI 開發組
* **感謝**: 感謝所有參與測試的師生提供的寶貴反饋。

---

<div align="center">
  <p>致力於用科技守護 CSJ 師生的每一分健康 💖</p>
  <p>如果這個專案幫助到了你，歡迎給我們一個 Star！ o((>ω< ))o</p>
</div>
