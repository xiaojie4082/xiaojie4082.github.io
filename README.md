# 個人網站

這是一個使用 Jekyll 建立的個人網站，包含以下功能：

- 個人簡介
- 專業經驗展示
- 預約諮詢系統

## 安裝需求

- Ruby 2.5.0 或更高版本
- Bundler
- Jekyll

## 安裝步驟

1. 安裝 Ruby 和 Bundler
2. 安裝 Jekyll：
   ```bash
   gem install jekyll bundler
   ```
3. 安裝依賴：
   ```bash
   bundle install
   ```

## 運行網站

在專案根目錄執行：
```bash
bundle exec jekyll serve
```

網站將在 http://localhost:4000 運行

## 自定義內容

- 編輯 `_config.yml` 修改網站基本設定
- 在 `_experiences` 目錄中添加或修改經驗頁面
- 修改 `index.html` 和 `booking.html` 自定義頁面內容

## 部署

網站可以部署到 GitHub Pages 或其他支援靜態網站的服務上。 