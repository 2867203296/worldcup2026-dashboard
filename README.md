# ⚽ 绿茵神算 — World Cup 2026 AI 预测仪表盘

> 2026 FIFA World Cup 实时赛程 + AI 预测引擎  
> 48 支球队 · 12 个小组 · 104 场比赛 · 零依赖单文件

## 🔥 为什么现在做

2026 世界杯 **6月11日已开赛**，全球数十亿球迷关注。  
这个仪表盘提供：

- 📊 **小组积分实时更新** — 48 队 12 组完整积分榜
- 📅 **赛程赛果** — 全场次时间/地点/比分
- 🤖 **AI 预测** — 每场比赛胜平负概率 + 比分预测（Premium）
- 🏆 **淘汰赛推演** — 小组赛后自动生成完整路径

## 💰 变现模式

| 层级 | 价格 | 内容 |
|---|---|---|
| 免费 | ¥0 | 小组积分、赛程、已完赛比分 |
| **Premium** | ¥9.99/月 | AI 胜平负预测、比分预测、淘汰赛推演、每日推送 |

世界杯周期 39 天。1000 付费用户 × ¥9.99 = ¥9,990。推广到 10,000 用户 = ¥99,900。

额外收入：
- Google AdSense 广告（免费层）
- 博彩平台 affiliate 导流
- 淘汰赛阶段单场预测付费（¥0.99/场）

## 🚀 使用

```bash
python3 -m http.server 8766
# 打开 http://localhost:8766
```

纯静态 HTML，可部署到 GitHub Pages / Vercel / Cloudflare Pages / 任何静态托管。

## 🛠️ 技术

- 单文件 HTML + 嵌入式 JS
- CSS Grid + Custom Properties 暗色主题
- 真实赛程数据（fixturedownload.com API）
- 零框架、零构建、零依赖
- 遵循 ponytail-ladder 哲学

## 📊 数据来源

赛程数据来自 [fixturedownload.com](https://fixturedownload.com) 公开 API，每日更新。

## 📝 License

MIT — 开源可商用。预测内容仅供娱乐参考，不构成博彩建议。
