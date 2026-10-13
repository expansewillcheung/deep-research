# Woolmark 授权（licence）核查

- 访问日期: 2026-10-13

## 直接查询尝试
| 目标 | 方式 | 结果 |
|---|---|---|
| https://www.woolmark.com/industry/source-wool/woolmark-supplier-search/ | curl | HTTP 403，Cloudflare "Just a moment…" |
| 同上 | WebFetch | HTTP 403 |
| 同上 | 普通 headless Chromium（无伪装） | HTTP 403，Cloudflare Turnstile "Verify you are human"（Ray ID a49c0c81380dc93b），截图 `06_woolmark_cloudflare_block_2026-10-13.png` |
| woolmark.com 的 licensee 指南 PDF（gd4441-how-to-become-a-woolmark-licensee_brand.pdf） | curl | HTTP 403 |

遇到人机验证后停止。**Woolmark 授权状态：未能在官方数据库验证（列入手动核查）。**

## 搜索摘要中关于制度本身的信息（来自搜索引擎摘要，未能打开原页，置信度：中）
- Woolmark 有两条授权路线：供应链 licensee（纺纱/织造/针织/成衣）与 brand/retailer licensee；品牌可以继承上游已认证供应商的认证，获得免费（fee-free）许可，并拿到 licence number。
  - https://www.woolmark.com/industry/certification/how-to-become-a-brand-or-retailer-licensee/
- Woolmark Supplier Search 页面称完整名单见 "Active Licensees List"（未能取得该名单 URL/内容）。
  - https://www.woolmark.com/industry/source-wool/woolmark-supplier-search/

## 间接证据
1. **Stock Journal，2024-10-16，作者 Victoria Nugent**（第三方新闻，转述 AWI 董事 Georgina Haack 在网络研讨会上的发言）
   - URL: https://www.stockjournal.com.au/story/8786891/promoting-australian-merino-wool-in-the-fashion-world/
   - 摘录（WebFetch 返回的片段）："…or even Uniqlo, Benetton, all of these brands that we have partnerships with" ；"It's the volume from say Uniqlo, that we've recently had some very good discussions with, …"
   - 解读：AWI（Woolmark 的母公司）称与 Uniqlo 有"partnership"/"讨论"，**但这不等于 Uniqlo 产品持有 Woolmark 授权**。置信度：低（单一转述来源）。
2. **二手平台**：Poshmark 一则"UNIQLO Woolmark Pure New Wool Sweater"挂牌（卖家自述，年份不明）
   - URL: https://poshmark.com/listing/UNIQLO-Woolmark-Pure-New-Wool-Sweater-68d05ba7ff0320a28c2e6a17
   - 置信度：最低；只能说明历史上可能有个别 Uniqlo 产品带 Woolmark 标，无法推广到现行系列。
3. Uniqlo 官网产品页（经搜索摘要）与 Fast Retailing 报告：**未见 "Woolmark" 字样**（FR Integrated Report 2025 全文 0 次，见 04 号来源）。

## 结论
- 现行 Uniqlo 男装羊毛系列持有 Woolmark 授权：**无证据**（不是"已证实没有"）。
- 需要手动：在 woolmark.com 登录或用浏览器通过人机验证后查 Active Licensees List，搜索 "UNIQLO" / "Fast Retailing" / 已知的 Uniqlo 针织供应商。
