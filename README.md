# Eleganza Studio

Eleganza Studio 是一個電商平台，通過團隊協作形式進行開發，內容包括商品、會員、課程、文章及購物車系統。開發過程中使用Next.js及Express分別作為前後端框架，並在前端中搭配Bootstrap以提高開發效率。

## 目錄

- [功能](#功能)
- [使用技術](#使用技術)
- [負責項目](#負責項目)
- [安裝說明](#安裝說明)
  
## 功能

- 商品展示與管理
- 會員系統
- 購物車功能
- 課程展示與管理
- 文章展示與管理
- 評論功能

## 使用技術

- **前端**: Next.js, React, Bootstrap
- **後端**: Express.js, Node.js
- **數據庫**: MySQL
- **其他工具**: Posterman, Git, GitHub, Figma

## 負責項目

#### 專案基礎建置

- 使用Provider建立全站讀取動畫。
- 導入所需框架（如Bootstrap），確保開發流程的標準化和高效性。
- 設定頁面基礎樣板以及不同尺寸下的頁面Header以及Footer的開發，確保所有頁面具備一致的結構和樣式。

#### 商品頁開發

- 個尺寸平台下的RWD。
- 視窗預覽動畫開發。
- 商品分頁、商品篩選、商品排序以及商品搜尋和提示效果，並使用狀態管理保留各尺寸下的篩選條件。
- 使用Hooks開發加入購物車功能、會員登入判斷。
- 使用React套件製作彈跳視窗。
- 通過Bootstrap加速樣式和布局的開發，提高開發效率。
- 使用Express開發後端API，與前端對接。

## 安裝說明

### 先決條件

1.確保系統已安裝以下軟件：
- Node.js
- npm（Node.js的包管理器）

2.將檔案根目錄中的db_violin.sql匯入並依據.env檔案創建使用者。

### 克隆項目

從GitHub倉庫克隆項目：
```bash
git clone https://github.com/yourusername/eleganza-studio.git
cd eleganza-studio
```

### 資料庫設定

將項目根目錄中的`db_violin.sql`匯入並依據`.env`檔案創建使用者。

### 安裝依賴並啟動開發伺服器

```
# 在 eleganza-next 目錄中
cd eleganza-next
npm install
npm run dev

# 在 express-base-esm-main 目錄中
cd ../express-base-esm-main
npm install
npm run dev
```
### 伺服器啟動

伺服器啟動後，在瀏覽器中打開 http://localhost:3000 查看應用。


