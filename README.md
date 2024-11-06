# 專案名稱

> 國家教育研究院 全國中小學題庫網 自動下載程序

## 目錄
- [專案介紹](#專案介紹)
- [安裝指引](#安裝指引)
- [使用方法](#使用方法)
- [授權條款](#授權條款)

## 專案介紹

國家教育研究院 全國中小學題庫網(以下簡稱[題庫網])將於113年12月31日24時正式停止服務。
為了搶救各位家中學子的成績，特開發此程式供各位家長使用。
透過本程序，一鍵下載您所需要的試巻，以利將來參考。不僅節省您的時間，更守護了您的錢包。

## 安裝指引

1. **安裝依賴套件**：請確保已安裝 Python 並執行以下指令來安裝必要的套件：
    ```bash
    pip install requests beautifulsoup4
    ```

2. **設定**：
    ```請依據實際需求，修改程式代碼中的Step 1以及Step 2的參數。
    Step 1: [題庫網]輸入查詢條件後，所生成的查詢網址。
    Step 2: 所下載的題庫PDF檔案，將存放在專案同目錄下以Step 2所設定的資料夾名稱中。
    ```

## 使用方法

描述如何運行程式：

```bash
python naerExamPaperDownload.py
```

## 授權條款

```
MIT License
```
