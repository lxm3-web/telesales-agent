# telesales-agent — 電話行銷排程專員（Agent 版）

同事拿到這包後：
1. 安裝 Claude Code（一次），或在瀏覽器 claude.ai/code 選這個 repo
2. 開終端機到這個資料夾，輸入 `claude`
3. 說「林經理丟了本週指示，幫我排」→ 它讀 inbox、分群、排 30 通、寫話術卡到 `outbox/` → 看完說「發下去」

資料全部是教學用假資料；公司「觀點週刊」為虛構。

**demo 完要歸零**：`inbox/*.txt.done` 改回 `.txt`、清空 `outbox/`、`log/campaign_log.md` 只留表頭。
