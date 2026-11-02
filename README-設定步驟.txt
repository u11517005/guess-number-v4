版本四設定說明

1. 版本四與版本三不同：不再輸入自訂識別碼，而是使用 Google 帳號授權。
2. 開啟 https://script.google.com/ 建立新的 Apps Script 專案。
3. 將 Code.gs 全部貼入預設程式碼檔案並儲存。
4. 左側按「＋」新增 HTML 檔案，檔名輸入 Index（不要輸入副檔名），貼入 Index.html 的全部內容並儲存。
5. 部署 → 新增部署作業 → 網頁應用程式。
6. 執行身分必須選「使用網頁應用程式的使用者」；存取權限依課程要求設定為允許測試者使用的選項。
7. 部署後開啟網頁應用程式網址，依提示使用 Google 帳號登入及授權。
8. 首次使用會在該登入帳號的 Google 雲端硬碟建立「猜數字遊戲版本四資料」，內含 Games、Guesses 工作表。
9. 請用第二個 Google 帳號測試；第二個帳號應建立另一份專屬試算表，且看不到第一個帳號資料。

重要：本版本使用 google.script.run，必須透過 Apps Script 部署網址開啟。不能只把 Index.html 放到 GitHub Pages，因為 GitHub Pages 不提供 google.script.run。
若課程要求網站一定要放 GitHub Pages，先向老師確認版本四是否可用 Apps Script 網頁應用程式網址作為入口。

若無法顯示登入 Email，請確認部署「執行身分」是使用網頁應用程式的使用者；部分學校 Google Workspace 管理政策可能限制此功能。
