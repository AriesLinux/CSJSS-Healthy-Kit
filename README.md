<div align="center">

# 🏥 CSJSS Healthy Kit [EazyUI-Framework]
## By CSJ Tech (明愛聖若瑟中學)
<br><br><br>
<img src="https://github.com/AriesLinux/CSJSS-Healthy-Kit/blob/main/school_logo.jpg" width="450" alt="School Logo">
<br><br><br>
<img src="https://github.com/AriesLinux/CSJSS-Healthy-Kit/blob/main/CSJSS%20Healthy%20Kit.png" width="150" alt="App Logo">
<br><br>

![Platform](https://img.shields.io/badge/Platform-Android-green?style=for-the-badge&logo=android&logoColor=white)
![Engine](https://img.shields.io/badge/Engine-MIT_App_Inventor-orange?style=for-the-badge)
![UI](https://img.shields.io/badge/UI_Arch-EazyUI-blue?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-lightgrey?style=for-the-badge)

<p align="center">
  <strong>基於 EazyUI 自研架構與 MIT App Inventor 開發的智能健康監測APP，依賴iRED公司開發的Smart Learning HEALTH KIT硬件</strong>
</p>


</div>

---

## 🖥️ 專案規格 (Project Specs)

| 項目 (Component) | 規格 (Model) | 備註 (Notes) |
| :--- | :--- | :--- |
| **開發平台** | [MIT App Inventor 2] | 視覺化邏輯開發 |
| **介面架構** | [EazyUI Framework] | **校內自研**，底層組件優化 |
| **適用設備** | [Android 8.0 或以上] | 需具備藍牙與感測器及掃二維碼支援 |
| **核心技術** | [Bluetooth LE / TinyDB] | 實現數據即時傳輸與雲端存儲 |

## 📊 運行狀態 (Status)

### ✅ 正常運作 (Working)
* [x] **EazyUI 全域渲染** (自適應佈局、圓角按鈕與主題統一配色)
* [x] **氧仔 (Oxy)**: 血氧監測模組 (實時數據與飽和度分析，數據超出正常值警告)
* [x] **度度 (Tempy)**: 溫度工具模組 (較高精準度體溫預警)
* [x] **脈動仔 (Pulso)**: 血壓工具模組 (脈搏追蹤實時顯示血壓度數，并作出警告)
* [x] **數據持久化**: 紀錄歷史量測數據不遺失

### ❌ 待開發 (Roadmap)
* [ ] [雲端同步，僅限單雲端]*
* [ ] [多語言 UI 切換]*
* [ ] [在測試血氧檢測時只允許保存無法捨棄，否則會出錯]*
* [ ] [暫無實質性AI功能]*

---

## ✨ EazyUI 自研架構 (The EazyUI Framework)
<br><br>
<img src="https://github.com/AriesLinux/CSJSS-Healthy-Kit/blob/main/EazyUI%20Logo.png" width="450" alt="EazyUI Logo">
<br><br>
**EazyUI** 是我們針對 MIT App Inventor 原生介面美觀度不足所開發的一套解決方案：

1.  **組件封裝**: 透過Canva APP模擬設計UI組件，并爲老人家單獨設計排版
2.  **視覺語言**: 採用一功能一顔色設計，並將 UI 元素與吉祥物交互深度整合
3.  **流暢體驗**: 優化了 Screen 切換邏輯，減少在低配 Android 設備上的載入感，并加入適當的動畫

---

## 🛡️ 三大健康守護者 (The Health Guardians)

本程式將量測功能具象化為三位守護吉祥物，讓健康量測更具親和力：
<br><br>
<img src="https://github.com/AriesLinux/CSJSS-Healthy-Kit/blob/main/3Luckin.png" width="450" alt="3Luckin">
<br><br>
* **💖 氧仔 (Oxy)**
  - **負責工具**: 血氧量測
  - **互動**: 當血氧低於 95% 時，氧仔會發出擔心的訊息框表情並提醒深呼吸（未開啓AI分析功能）
* **🌡️ 度度 (Tempy)**
  - **負責工具**: 體溫量測
  - **互動**: 即時檢測額頭溫度或耳内溫度，并作出反應（未開啓AI分析功能）
* **📈 脈動仔 (Pulso)**
  - **負責工具**: 血壓與脈搏
  - **互動**: 多個模塊顯示血壓並繪製波形圖，并有雲端保存功能

---

## ⚙️ 設置與權限 (Settings & Permissions)

**為了確保數據量測準確，請檢查以下設置：**

* **停用 (Disable):**
    * 電池過度優化 (防止背景量測被中斷)
* **啟用 (Enable):**
    * **Bluetooth (藍牙)**: 用於與量測硬體連線
    * **Location (定位)**: Android 系統掃描藍牙裝置之必要權限
    * **Storage (存儲)**: 用於讀寫健康日誌
    * **Camera (相機)**: 掃描外置檢測硬件背後二維碼
---

## 👏 開發團隊與鳴謝 (Credits)

* **主辦學校**: [明愛聖若瑟中學](https://www.csjss.edu.hk/)
* **核心開發**: DONG ALLEN SHUHANG（同學），LUO DEMING（同學），XIN QICHENG（同學），JERRY ZHOU JINGHAN（同學），XIE HAOLIN（同學）
* **感謝**: LEE WY（老師指導及支持)，Chapman（導師指導及支持），Tsui Lai Ha（老師測試及支持），You（支持及測試）

---
## 🤝 Support and production philosophy：
<img src="https://github.com/AriesLinux/CSJSS-Healthy-Kit/blob/main/app_iREd_Logo.png" width="300" alt="app_iREd_Logo">
<img src="https://github.com/AriesLinux/CSJSS-Healthy-Kit/blob/main/HealthKitLogo.png" width="300" alt="HealthKitLogo">


---
<div align="center">
  <p>致力於用科技守護 CSJ 師生及每一位老人家的每一分健康💖</p>
  <p>如果這個專案幫助到了你，歡迎給我們一個 Star！ o((>ω< ))o</p>
</div>
