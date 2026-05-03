# SpringBootStudy

這個 repo 用來：
1) 放 Spring Boot 的練習程式碼（每一堂課一個資料夾）
2) 用 **MkDocs Material** 產生一個可隨時複習的筆記網站（支援側邊欄、全文搜尋、可擴展到 React 等主題）

## 筆記網站（Docs）
- 原始檔：`docs/`
- 設定檔：`mkdocs.yml`

### 本機啟動
```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
mkdocs serve
```

打開： http://127.0.0.1:8000/

### 部署（GitHub Pages）
推到 `main` 後，GitHub Actions 會自動 build & deploy。

## 目錄約定
- `lessons/`：每堂課程的 code
- `docs/`：可讀性優先的筆記（網站內容）
