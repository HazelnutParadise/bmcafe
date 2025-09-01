# BM Café 商管咖啡廳

**BM Café 商管咖啡廳** 是一個會每天自動將HBR文章改寫成故事的Ghost部落格。此repo包含了架設此站所需的docker-compose.yml、n8n工作流代碼，以及網頁上內嵌的程式碼。

網址：https://bmcafe.hazelnut-paradise.com/

![logo](bmcafe.png)

## 各檔案功能

- `bmcafe.json`：n8n工作流。
- `docker-compose.yml`：架設此Ghost部落格所需的stack，包含Ghost容器與資料庫。
- `header.html`：放在部落格上方的header程式碼。
- `footer.html`：放在部落格下方的footer程式碼。
- `bmcafe.png`：logo。
