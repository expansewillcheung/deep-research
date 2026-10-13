# 价格证据（SGD / GBP / JPY）

**重要限制**：Uniqlo 各区官网的价格由 JavaScript 动态加载。2026-10-13 用 WebFetch 读到的产品页静态文本里**没有价格**；curl 直连 SG 站为 HTTP 403。因此，除下表标"直接读取"的一项外，价格都来自**搜索引擎对官网页面的摘要**（抓取时间不明），不是逐字原文。按规则不尝试绕过，所以 SGD 价格整体置信度为"中"或"低"，全部列入手动核查清单。

## SGD（uniqlo.com/sg）
| 商品 | 价格 | 依据 | 置信度 |
|---|---|---|---|
| Cashmere Crew Neck Sweater (Long Sleeve)（Unisex，E450543） | S$129.90；评分 4.9（23） | **直接读取** SG 类目页静态文本 https://www.uniqlo.com/sg/en/men/knitwear/sweaters（2026-10-13） | 高 |
| Merino Crew Neck Sweater (Long Sleeve)（E450535） | S$39.90 | 3 次独立搜索的摘要一致指向 SG 男/女类目页 | 中 |
| Extra Fine Merino V Neck Sweater (Long Sleeve)（E450536） | S$39.90 | 搜索摘要（SG 男装类目页，"Men, S-XL"） | 中 |
| Merino Knitted Polo Shirt (Long Sleeve)（E460939） | S$49.90 | 搜索摘要（SG 类目页，两次一致） | 中 |
| Lambswool Crew Neck Sweater（E479832，Unisex） | S$49.90 | 搜索摘要（SG 类目页，带 "Available Mid-Aug, Limited Store"） | 中 |
| Lambswool V Neck Cardigan | S$59.90 | 搜索摘要 | 低 |
| Cashmere Turtleneck (Long Sleeve)（E450544） | S$169.90（另一摘要见 S$79.90，疑为特价） | 搜索摘要，互相矛盾 | 低 |
| Cashmere Half-Zip Sweater | S$169.90 | 搜索摘要 | 低 |
| Souffle Yarn Crew Neck Sweater（E471229） | S$39.90 | 搜索摘要 | 中 |
| Souffle Yarn Polo Sweater（E487939） | S$49.90 | 搜索摘要 | 低 |
| Washable Milano Ribbed Crew Neck（E453754） | **未取得** | 摘要中无 SGD 价格 | — |
| Merino Cardigan（E450540） | **未取得** | — | — |
| Unisex Balmacaan Coat（E481241） | **未取得** | — | — |

### SG 近期 Limited Offer / 特价
- 2026-10-13 直接读取的 SG 页面横幅："10.10 Special Offers: Shop limited-time deals from $9.90 and enjoy underwear essentials at 2 for $12.90."（全站活动，**未显示哪些针织品参与**）
- 搜索摘要中出现过：Cashmere Crew S$99.90（"sale and limited-color offer"）、Cashmere Turtleneck S$79.90（"sale-type listing"）；**日期不明**，置信度：低。
- 结论：**近期针对性的 Limited Offer 价格未能验证**，需手动查。

## GBP（uniqlo.com/uk）——全部为搜索摘要
| 商品 | 原价 | 摘要中出现的特价 | 置信度 |
|---|---|---|---|
| 100% Merino Crew Neck Jumper（E450535） | £34.90（类目页：4.6 分/855 评论） | £19.90，"30-Day Lowest Price: £24.90" | 中 |
| 100% Merino V Neck Jumper（E450536） | £34.90 | — | 中 |
| 100% Merino Polo Jumper | £34.90 | — | 中 |
| 100% Merino V Neck Cardigan | £39.90 | — | 中 |
| 100% Merino Half-Zip | £39.90 | — | 低 |
| 100% Cashmere Crew Neck Jumper（E450543） | £89.90（4.8 分） | 3XL £49.90，"30-Day Lowest £69.90" | 中 |
| 100% Lambswool V Neck Cardigan | £39.90 | — | 低 |
| 100% Lambswool Crew Neck Jumper（E479832） | 可能为 £34.90（摘要不明确） | £19.90 | 低 |
| Souffle Yarn Crew Neck Jumper | £34.90 | — | 低 |
| Washable Milano Ribbed Crew Neck Jumper | £34.90（4.7 分/750 评论） | £12.90，"30-Day Lowest £19.90" | 中 |
| Balmacaan Overcoat | £109.90 | — | 低（来自 T3 文章摘要，https://www.t3.com/luxury/style/uniqlo-balmacaan-overcoat-0926 ，原文 WebFetch 被截断） |

来源 URL（搜索摘要所指页面）：
- https://www.uniqlo.com/uk/en/men/jumpers/jumpers/extra-fine-merino
- https://www.uniqlo.com/uk/en/men/jumpers
- https://www.uniqlo.com/uk/en/men/jumpers/jumpers?tagDesign=crew-neck
- https://www.uniqlo.com/uk/en/products/E453754-000/01

## JPY（直接读取 JP 评论汇总页，2026-10-13）——仅作对照
- メリノクルーネックセーター（E450535）：¥3,990（https://www.uniqlo.com/jp/ja/contents/kw/detail-E450535-000/）
- カシミヤクルーネックセーター（E450543）：¥7,990（https://www.uniqlo.com/jp/ja/contents/kw/detail-E450543-000/）
- メリノニットポロセーター：¥3,990（tradman-dc 2025-10-13 博客）
