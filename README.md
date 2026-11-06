# counting-bot

每天北京时间 00:05 记一次 [TechCafe](https://www.noctuna.cc/) 在 [Vercount](https://vercount.one/) 上的累计访问量 / 访客数（只读，不改计数），追加到 [`data/visits.json`](data/visits.json)。

博客侧栏「网站资讯」卡片读这份数据，画近 30 天的每日访问量曲线（某天的访问量 = 当天累计 − 前一天累计）。

- 定时任务：[`.github/workflows/visits.yml`](.github/workflows/visits.yml)，也可以在 Actions 页面手动运行
- 数据地址：`https://cdn.jsdelivr.net/gh/Harukuya/counting-bot@main/data/visits.json`
