# FQS 量化作戰室

## 如何讓所有AI讀到？
把這個 repo 網址給任何AI，第一句話說：
「請先讀 AGENTS.md 和 backtests/summary.csv，再讀 strategies/ 下所有 .md」

## 工作流
1. AI 在 strategies/ 新增策略 (用模板)
2. 照著策略描述設定
3. 回測，截圖
4. 把數據填回該策略的 .md 和 summary.csv
5. 下一個AI來讀 summary.csv 就知道要優化什麼

## 你的條件庫
把你原本的條件庫.md 拆解，放到 strategies/_library/ 備用
- 價量: 收盤價>=50, 今日上漲, 紅K, 收最高, 創5日新高等15個
- 後續可再貼籌碼/技術面等分類
