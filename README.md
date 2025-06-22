# Cursor Rules 整理工具

這個專案用於整理和收集來自不同專案的Cursor規則檔案，提供多種程式語言和框架的規則支援。

## 專案簡介

Cursor是一款AI輔助編程工具，它使用規則檔案來指導其行為。本專案的目標是收集、整理和標準化這些規則檔案，使開發者能夠更有效地利用Cursor進行開發工作。

參考文章教程：

[Cursor Rules 的一次全面總結，希望能夠幫助到你！](https://mp.weixin.qq.com/s/l8r2lJlEv5fKWJRSsSd1kQ)

[Cursor 0.49.x 自動化生成 Project Rules 實用指南](https://mp.weixin.qq.com/s/1yTkzYzOFjty1D0gtYHuHA)

[Cursor Rules 進階指南：打造企業級多語言開發規範](https://mp.weixin.qq.com/s/rfanrMtMMuyUTwsDYmlxSg)

[Cursor Rules 最佳實踐總結](https://mp.weixin.qq.com/s/-J_LwfwH9rmFy4dzEy0RXg)

## 目前支援的規則類型

### 通用規則
- **一般性編程規則** (general.mdc)
- **Git相關規則** (git.mdc)
- **Git Flow工作流規則** (gitflow.mdc)
- **文件編寫規則** (document.mdc)

### 程式語言
- **Python** (python.mdc)
- **Java** (java.mdc)
- **TypeScript** (typescript.mdc)
- **Go** (golang.mdc)
- **C++** (c++.mdc)
- **CSS** (css.mdc)
- **WXML** (wxml.mdc) - 微信小程序標記語言
- **WXSS** (wxss.mdc) - 微信小程序樣式表

### 框架支援

#### 前端框架
- **React** (react.mdc) - React 應用開發
- **Vue.js** (vuejs.mdc) - Vue.js 應用開發
- **Next.js** (nextjs.mdc) - React 全端框架
- **Tailwind CSS** (tailwind.mdc) - 實用優先的 CSS 框架

#### 後端框架
- **Django** (django.mdc) - Python Web 框架
- **Flask** (flask.mdc) - Python 輕量級 Web 框架
- **FastAPI** (fastapi.mdc) - Python 現代 API 框架
- **Spring Boot** (springboot.mdc) - Java 企業級框架

#### 行動開發框架
- **Flutter** (flutter.mdc) - 跨平台行動應用開發
- **SwiftUI** (swiftui.mdc) - iOS 原生 UI 框架
- **React Native** (react-native.mdc) - 跨平台行動應用開發

## 功能特點

- 收集不同專案中的Cursor規則檔案
- 對規則檔案進行分類和整理
- 提供標準化的規則範本
- 便於在不同專案間共享和重用規則
- 支援多種程式語言和框架
- 包含備份和歷史版本管理

## 使用方法

1. 克隆本倉庫
2. 瀏覽相應語言和框架的規則
3. 將適用的規則應用到您的專案中
4. 貢獻您自己的規則回饋社群

## 專案結構

```
cursor-rules/
├── common/              # 通用規則
│   ├── general.mdc      # 一般性編程規則
│   ├── git.mdc          # Git相關規則
│   ├── gitflow.mdc      # Git Flow工作流規則
│   └── document.mdc     # 文件編寫規則
├── languages/           # 程式語言特定規則
│   ├── python.mdc       # Python語言規則
│   ├── java.mdc         # Java語言規則
│   ├── typescript.mdc   # TypeScript語言規則
│   ├── golang.mdc       # Go語言規則
│   ├── c++.mdc          # C++語言規則
│   ├── css.mdc          # CSS樣式規則
│   ├── wxml.mdc         # 微信小程序標記語言規則
│   └── wxss.mdc         # 微信小程序樣式表規則
├── frameworks/          # 框架相關規則
│   ├── # 前端框架
│   ├── react.mdc        # React框架規則
│   ├── vuejs.mdc        # Vue.js框架規則
│   ├── nextjs.mdc       # Next.js框架規則
│   ├── # 後端框架
│   ├── django.mdc       # Django框架規則
│   ├── flask.mdc        # Flask框架規則
│   ├── fastapi.mdc      # FastAPI框架規則
│   ├── springboot.mdc   # Spring Boot框架規則
│   ├── # 行動開發框架
│   ├── flutter.mdc      # Flutter框架規則
│   ├── swiftui.mdc      # SwiftUI框架規則
│   ├── react-native.mdc # React Native框架規則
│   └── # 樣式框架
│   └── tailwind.mdc     # Tailwind CSS規則
└── backup/              # 備份資料夾
    ├── python/          # Python相關備份
    └── vue/             # Vue相關備份
```

## 貢獻指南

歡迎提交Pull Request来分享您的Cursor規則。請確保您的規則檔案遵循專案的命名約定和結構。規則可以使用Markdown(.mdc)或JSON格式。

### 貢獻步驟
1. Fork 本倉庫
2. 建立您的特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交您的變更 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 開啟一個 Pull Request

## 授權

MIT
