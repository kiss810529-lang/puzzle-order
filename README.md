# puzzle-order

拼圖文創的寶寶藍客製訂單網站，前端使用原生 HTML/CSS/JavaScript，訂單寫入 Firebase Firestore。

## 目前功能

- 手機與電腦響應式客製訂單表單
- 聯絡資料、商品需求、取貨與付款方式
- 宅配時自動顯示收件地址
- 送出後產生需求編號
- Firestore 儲存訂單與最小權限安全規則

## 啟用 Firebase

1. 在 Firebase Console 建立專案與 Web App。
2. 建立 Firestore Database。
3. 將 Web App 設定填入 `firebase-config.js`。
4. 將 `firestore.rules` 發布至 Firestore Rules。
5. 使用網頁伺服器預覽，請勿直接用 `file://` 開啟。

Firebase 尚未設定前，頁面可以正常預覽，但不會真的送出訂單。
