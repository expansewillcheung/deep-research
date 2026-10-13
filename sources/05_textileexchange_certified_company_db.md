# Textile Exchange — Find a Certified Company（RWS 认证公司数据库）直接查询尝试

- 目标 URL: https://textileexchange.org/find-certified-company/ （也试了 https://textileexchange.org/find-certified ）
- 访问日期: 2026-10-13
- 来源类型: 认证机构数据库（若能查到为一手证据）

## 查询过程与结果
| 时间（UTC） | 方式 | 结果 |
|---|---|---|
| 2026-10-13 | curl | HTTP 403，返回 Cloudflare "Just a moment… Enable JavaScript and cookies to continue" |
| 2026-10-13 | WebFetch | HTTP 403 Forbidden |
| 2026-10-13 | 普通 headless Chromium（Playwright，未用任何伪装/验证码破解） | HTTP 403，页面标题 "Just a moment..."，出现 Cloudflare Turnstile "Verify you are human" 复选框（Ray ID a49c0a36d970ef61）。截图：`05_textileexchange_cloudflare_block_2026-10-13.png` |

在出现人机验证后**停止**，没有尝试绕过。**结论：本次未能直接查询数据库，"Uniqlo / Fast Retailing 是否有 RWS 证书"在数据库层面为"未验证"，不是"没有"。** 已列入 report.md 手动核查清单。

## 为什么"数据库里搜不到"本身也不能推出"没有 RWS 羊毛"
Textile Exchange《Quick Guide to the RWS》(RAF-403a-V2.1-2020.07.13，**2020 年资料，可能已过时**)：
- URL: https://textileexchange.org/app/uploads/2021/02/RAF-403a-V2.1-Quick-Guide-to-the-RWS.pdf （访问 2026-10-13，HTTP 200）

> The RWS requires all sites to be certified, beginning with the wool farmers and through to the seller in the final business-to-business transaction. Usually, the last stage to be certified is the garment manufacturer or the brand; retailers (business-to-consumers) are not required to be certified.

→ 也就是说：RWS 链条上应该被查的是**纺纱厂/针织厂/成衣厂**（以及若品牌自行做 B2B 交易时的品牌）。Uniqlo 作为面向消费者的零售商，即使使用 RWS 羊毛，数据库里也可能查不到 "UNIQLO" 名下的证书；反之，若 Uniqlo 产品要**标示** RWS，按 RWS 规则需要完整的认证链和交易证书（TC）。

## 数据库的权威性（为什么必须查它）
Textile Exchange《Policy for Scope and Transaction Certificates》TE-TXL-POL-203-V4.0，发布日期 2026-04-01：
- URL: https://textileexchange.org/app/uploads/2026/03/TE-TXL-POL-203-V4.0-Policy-for-Scope-and-Transaction-Certificates.pdf （访问 2026-10-13，HTTP 200）

> Curated Trackit data is publicly available via tools on our website such as Find a Certified Company, Authenticate a Transaction, …

> …a statement shall be included that the Textile Exchange Find a Certified Company webpage is the only official source to authenticate scope certificates …

## RWS 对 mulesing 的要求（用于对照 FR 政策）
Responsible Wool Standard V2.2（RAF-101a-V2.2，2020 年发布文件，可能已有更新版本）：
- URL: https://textileexchange.org/app/uploads/2020/08/RAF-101a-V2.2-Responsible-Wool-Standard.pdf （访问 2026-10-13）

> AW3.11 Mulesing is prohibited. … Farms with Ceased Mulesing status are accepted. … AW3.11.1 Freeze Mulesing (Steining) is prohibited.

## 间接检索（均为"查过但没有"）
- WebSearch `Uniqlo "Responsible Wool Standard" OR "RWS" wool product certified`（2026-10-13）：无任何结果把 Uniqlo 产品与 RWS 关联。
- Fast Retailing 采购页（英/日）与 Integrated Report 2025：RWS 出现 0 次（见 01、02、04 号来源）。
- Textile Exchange Material Change Index 排行榜 pfmm.textileexchange.org：WebFetch 报 DNS 解析失败（ENOTFOUND），未能核对 FR 是否参与。
