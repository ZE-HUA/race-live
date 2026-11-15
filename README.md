# Race Live — 多人即時位置與車速

手機打開網頁，輸入名字和房間代碼，同一個房間的人會在地圖上即時看到彼此的位置、方向和車速。

- 網址：https://ze-hua.github.io/race-live/
- 即時同步：公開 MQTT 伺服器（broker.hivemq.com，WebSocket over TLS），每秒上傳一次位置
- 地圖：Leaflet + OpenStreetMap
- 限制：螢幕關閉或切到背景時會停止定位；知道房間代碼的人都能看到位置
