☆ Music Start 小助手 ☆

☆ ISA 指令集
1. `.attach` 將 Music Start 加入您目前所在的語音房中 alias: `.join`
2. `.bye` 將 Music Start 踢出語音房
3. `..[url]` 播放音樂，若音樂正在播放，則會加入播放清單。若 Music Start 不在語音房中，則會自動呼叫 `.attach`
4. `..` 暫停或播放
5. `.stop` 停止播放，但不會將 Music Start 踢出語音房
6. `.list` 列出播放清單 alias: `.ls`
7. `.jump [index]` 直接跳到播放清單的某一首歌 alias: `.jmp`
8. `.remove [index]` 直接刪除播放清單的某一首歌 alias: `.rm`
9. `.clear` 清空播放清單
10. `.sort` 按照名稱排序播放清單
11. `.shuffle` 將播放清單隨機打亂，正在播放的歌位置不會受影響
12. `.next` 播放下一首
13. `.pre` 播放前一首
14. `.vol [num]` 設定音量 num 介於 [0, 1] 間，若不指定 num 則會顯示目前的音量，預設為 0.64
15. `.seek [time]` 跳到歌曲的某個時間點，time 的單位為秒
16. `.json` 將播放清單以 json 格式輸出，此方法可以將喜歡的曲目存成文字檔，下次聽歌時可以做批次輸入
17. `.json [json string]` 將 json 格式的播放清單一次加入到播放清單中

☆ 參數說明

1. **url** 目前僅支援 youtube 的網址
2. **index** index 為播放清單的編號，由 0 開始，若 index 為負數則由清單最末尾開始計數，也就是說 -1 表示清單最後一首，若數字超過播放清單長度，則系統會啟用溢位
3. **time** 該參數如果指定為 `1` 就代表 1 秒，指定為 `1:1` 就代表 61 秒，指定為 `1:1:1` 就代表 3661 秒。也就是說 `:` 是 60 進位的分割符。小數、負數都支援。

☆ Github

https://github.com/liao2000/Music-start-discord-bot

