# 充滿榮耀的頒獎音樂

8bit 風格的音樂播放器網頁：戴著粉紅色眼鏡的法國貴族指揮家，按下播放鍵就會開始指揮。

- 播放 YouTube 音樂片段 0:24–0:46，最後 5 秒漸弱結束，只播放一次
- 指揮家動畫：`conductor.gif`（播放時）／`conductor-still.png`（靜止時）

## 使用方式

網頁必須透過 http(s) 網址開啟（例如 GitHub Pages），直接雙擊 html 檔案時 YouTube 會出現錯誤 153。

本機測試：

```bash
python3 -m http.server 8000
```

然後開啟 http://localhost:8000

## 音樂出處

https://youtu.be/dMTDjavVmH4
