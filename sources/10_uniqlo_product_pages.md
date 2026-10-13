# Uniqlo 官网产品页摘录（SG 为主，UK/AU/US 作对照）

访问说明（2026-10-13）：
- curl 直接访问 www.uniqlo.com/sg/en/ 返回 **HTTP 403 "Access Denied"（Akamai，Reference #18.6a18d017.1791870025.155ef3e8）**；未做任何 UA 伪装或绕过。
- 用 WebFetch 工具访问时，SG/UK 产品页**间歇性**返回 HTTP 503，其余时候能读到页面的静态文本。**价格、评分、评论数由 JS 动态加载，不在静态文本中**，因此 SGD/GBP 价格只能用搜索引擎摘要（见 11 号来源），置信度相应降低。
- 下列"原文"都是 WebFetch 按"逐字引用"要求返回的文本。

---

## SG — Merino Crew Neck Sweater (Long Sleeve)
- URL: https://www.uniqlo.com/sg/en/products/E450535-000/00
- 访问日期: 2026-10-13（WebFetch 成功；同日另一次请求 503）
- 原文：
  - 标题: "Men's Merino Crew Neck Sweater (Long Sleeve) | UNIQLO SG"
  - "Product ID: 486058"
  - Fit 行: **页面无**
  - 材质: "100% Wool"
  - Features: "Made with 19.5 micron extra-fine 100% Merino wool for a smooth touch and glossy sheen." / "Machine-washable with added pilling-resistant processing for easy care." / "*We recommend washing this item inside out in a mesh laundry bag." / "100% wool keeps you feeling fresh and comfortable." / "Variable ribbed knit at the sleeves and hem to prevent sagging."
  - Details: "Versatile, simple design." / "Wool is a natural material so it may emit an odor with water or moisture…"
  - 洗涤: "Machine wash cold, gentle cycle, Dry Clean, Do not tumble dry."
  - 产地: "Production: China" / "*The information on material production locations applies to products manufactured after 24FW."
  - 模特: "Model is 183 cm / Wearing size: L"；"Model is 185 cm / Wearing size: L"
  - 价格/评分: 静态文本中无

## UK — 100% Merino Crew Neck Jumper（同一款，UK 命名不同）
- URL: https://www.uniqlo.com/uk/en/products/E450535-000/00
- 访问日期: 2026-10-13
- 原文：
  - "Men's 100% Merino Crew Neck Jumper | UNIQLO UK"
  - "Product ID: 486058,478535,469395" / "Please note that this product may have different product ID, even if it is the same item."
  - 颜色: "GREY, BLACK, RED, DARK BROWN, OLIVE, BLUE, NAVY"；尺码 "XS S M L XL XXL 3XL"
  - "Fabric details: 100% Wool"
  - "Washing instructions: Machine wash up to 40 degrees, gentle cycle, Dry Clean, Not suitable for tumble-drying."
  - Production Information: "Country/Countries of Production: China, Cambodia" / "Fabric knitting and weaving: China, Cambodia" / "Fabric dyeing: Vietnam" / "Fabric production information applies to products manufactured after Autumn/Winter 2024."
  - 注意：**SG 页只写 China，UK 页写 China, Cambodia**——同款不同批次/市场可能产地不同，购买时需看实物洗标。

## SG — Cashmere Crew Neck Sweater (Long Sleeve)（Unisex）
- URL: https://www.uniqlo.com/sg/en/products/E450543-000/00
- 访问日期: 2026-10-13（WebFetch 成功）
- 原文：
  - 标题: "Unisex Cashmere Crew Neck Sweater (Long Sleeve) | UNIQLO SG"
  - "Product ID: 486074" / "Product ID: 486074,478543"
  - "Fit: Regular"
  - 材质: "100% Cashmere"
  - Features: "Luxurious 100% cashmere for a premium feel and exceptional comfort." / "Available in a choice of vibrant colors showcasing the exquisite cashmere yarn." / "Special pilling-resistant processing ensures the cashmere keeps its soft texture when hand-washed." / "Yarn thickness and knit tension have been perfected for a premium feel."
  - Details: "Sheer: Not Sheer(Only 01 Off white/40 Cream is slightly sheer)"
  - 洗涤: "Hand wash cold, Dry Clean, Do not tumble dry."（**不可机洗**）
  - 产地: "Production: China"（"applies to products manufactured after 24FW"）
  - 模特: "Model is 185 cm / Wearing size: L"；"Model is 183 cm / Wearing size: XL"
  - 纤维细度: **页面未写微米数**
- SG 类目页（直接 WebFetch，2026-10-13）: https://www.uniqlo.com/sg/en/men/knitwear/sweaters
  - 原文: "Cashmere Crew Neck Sweater (Long Sleeve)" / "Men, XS-3XL" / "$129.90" / "Unisex" / 评分 "4.9 (23)" / 链接 /sg/en/products/E450543-000/00?colorDisplayCode=27
  - 同页横幅: "10.10 Special Offers: Shop limited-time deals from $9.90 …"（未见针织类 Limited Offer 标签）
  - 注：类目页静态文本仅 3,893 字符，只渲染出这一张商品卡；其余商品卡由 JS 加载，读不到。

## SG — Extra Fine Merino V Neck Sweater (Long Sleeve)
- URL: https://www.uniqlo.com/sg/en/products/E450536-000/00
- 访问日期: 2026-10-13
- 原文：
  - 标题: "Men's Extra Fine Merino V Neck Sweater (Long Sleeve) | UNIQLO SG"
  - "Product ID: 486063"
  - Fit 行: 页面无
  - 材质: "100% Wool"
  - Features: 与 Merino Crew 完全相同（"Made with 19.5 micron extra-fine 100% Merino wool…" / "Machine-washable with added pilling-resistant processing for easy care." / "Variable ribbed knit at the sleeves and hem to prevent sagging."）
  - 洗涤: "Machine wash cold, gentle cycle, Dry Clean, Do not tumble dry."
  - 产地: "Production: Vietnam"
  - 模特: "Model is 183 cm / Wearing size: L"

---
## JP 官网产品页（SG 页 503 时的对照来源；商品编号全球通用，但**产地按市场/批次不同**）
访问日期均为 2026-10-13，WebFetch；价格在 JP 静态页中也不显示。

### JP — メリノクルーネックセーター（E450535，SG 的 Merino Crew Neck Sweater）
- URL: https://www.uniqlo.com/jp/ja/products/E450535-000/00
- 原文要点: 名称注明 **"旧名称：エクストラファインメリノクルーネックセーター(長袖)"**（→ 官方确认 Extra Fine Merino 已更名为 Merino）；商品番号 486058（タグ用 478535）；"100％ 毛"；"約19.5マイクロンの極細メリノウール"；"毛玉ができにくい特殊加工"；"洗濯機で洗える"；洗濯表示 "洗濯機可・ネット使用, ドライクリーニング可, 乾燥機不可"；**トップスフィット "普通"**（=Regular）；生産国 "カンボジア、ベトナム"；模特 186cm/L、185cm/L
- 防缩: 产品页"記載なし"（只在 Masterpiece 专题页提到 non-shrink treatment，见 20 号来源）

### JP — メリノVネックカーディガン（E450540）
- URL: https://www.uniqlo.com/jp/ja/products/E450540-000/00
- 原文要点: 商品番号 486067（另 478539）；"100％ 毛"；"約19.5マイクロンの「極細メリノウール」を100％使用"；"毛玉ができにくい特殊加工"；"洗濯機で洗えて、お手入れが簡単"；洗濯表示 "洗濯機可・ネット使用"；フィット "普通"；生産国 "中華人民共和国、ベトナム"；模特 184cm/XL、174cm/M

### JP — メリノニットポロセーター（E460939）
- URL: https://www.uniqlo.com/jp/ja/products/E460939-000/00
- 原文要点: "商品番号: 486064"（"486064,478537"）；"100% 毛"；"約19.5マイクロンの極細メリノウールを100％使用し"；"毛玉ができにくい特殊加工"；"洗濯機で洗えて"；"洗濯機可・ネット使用, ドライクリーニング可, 乾燥機不可"；"トップスフィット: 普通"；生産国 "中華人民共和国, ベトナム"；模特 180cm/L

### JP — カシミヤタートルネックセーター（E450544）
- URL: https://www.uniqlo.com/jp/ja/products/E450544-000/00
- 原文要点: 商品番号 486076（另 478544）；"100% カシミヤ"；微米数 記載なし；"特殊な加工で毛玉になりにくく"；洗濯表示 "手洗い可、ドライクリーニング可、乾燥機不可"；トップスフィット "普通"；生産国 "中華人民共和国、カンボジア、ベトナム"；模特 183cm/XL

### JP — ラムクルーネックセーター（E479832，SG 的 Lambswool Crew Neck Sweater）
- URL: https://www.uniqlo.com/jp/ja/products/E479832-000/00
- 原文要点: 商品番号 479832；"100% 毛"；微米数 **記載なし**（只写 "上質ウールを強めに撚っている"）；抗起球 記載なし；防缩 記載なし；洗濯表示 "手洗い可、ドライクリーニング可、乾燥機不可"；シルエット "リラックス感のある、ややボクシーなシルエット"、ドロップショルダー；**トップスフィット "ややゆったり"**（=Relaxed）；生産国 "ベトナム"；模特 188cm/L
- 注：旧款 "Premium Lambswool"（如 SG E460940、E450541）在搜索摘要中被描述为 "100% premium 19.5-micron wool"；FW2026 款名称已去掉 "Premium"，且页面不再写微米数。

### JP — エクストラファインメリノタートルネックセーター（長袖）（E450538）
- URL: https://www.uniqlo.com/jp/ja/products/E450538-000/00
- 原文要点: 商品番号 450538（旧番号体系，可能是往季库存款）；"100％ 毛"；"19.5マイクロンの極細メリノウールを100％使用"；**"素材特性上、毛玉が発生しやすい"**（官方页面自己提示易起球，提醒避免摩擦）；"洗濯機可・ネット使用"；"フィット感：普通"；生産国 "ベトナム"

### JP — カシミヤクルーネックセーター（メンズ）（E450543）
- URL: https://www.uniqlo.com/jp/ja/products/E450543-000/00
- 原文要点: 商品番号 489018（关联 486074, 478543, 469404）；"100% カシミヤ"；微米 記載なし；"特殊な加工で毛玉になりにくく、手洗いしても風合いが変化しにくい。"；"手洗い可, ドライクリーニング可, 乾燥機不可" / "単独で洗って下さい。"；"トップスフィット: 普通"；生産国 "中華人民共和国, カンボジア, ベトナム"
- 对照：SG 页同款写 "Production: China"；搜索摘要称 US 页写 "Viet Nam"。

### JP — ラムVネックカーディガン（E469402 / 478547）
- URL: https://www.uniqlo.com/jp/ja/products/E469402-000/00
- 原文要点: 商品番号 478547（タグ 478547,469402）；"100% 毛"；**"約19.5マイクロンのウールを100％使用"**；抗起球/防缩 記載なし；"手洗い可、ドライクリーニング可、乾燥機不可"；"トップスフィット: 普通"；生産国 "中華人民共和国, ベトナム"

### JP — スフレヤーンクルーネックセーター（男女兼用）（E471229，SG 的 Souffle Yarn Crew Neck Sweater）
- URL: https://www.uniqlo.com/jp/ja/products/E471229-000/00
- 原文: "57% アクリル, 32% ポリエステル, 8% 毛, 3% ポリウレタン ( 32% リサイクルポリエステル繊維を使用 )"；"手洗い可, ドライクリーニング可, 乾燥機不可"；"肩やボディにゆとりを持たせたシルエット"、"トップスフィット: ややゆったり"、丈 "短め"；"製品原産地（縫製・編立・組立）: ベトナム"
- SG 页（E471229）在搜索摘要中显示相同混纺比例（57/32/8/3），直接 WebFetch 返回 503。

### JP — スフレヤーンポロセーター（男女兼用）（E487939）
- URL: https://www.uniqlo.com/jp/ja/products/E487939-000/00
- 原文: "62% アクリル, 30% ポリエステル, 5% 毛, 3% ポリウレタン ( 30% リサイクルポリエステル繊維を使用 )"；"手洗い可"；"トップスフィット: 普通"；"カンボジア, ベトナム"

### JP — ウォッシャブルミラノリブクルーネックセーター（男女兼用）（E453754）
- URL: https://www.uniqlo.com/jp/ja/products/E453754-000/00
- 原文: 商品番号 490455（同一商品 486060, 481722, 478548, 474203, 470159）；**"39% 綿, 34% ポリエステル, 27% レーヨン ( 34% リサイクルポリエステル繊維を使用 )"——不含羊毛**；"洗濯機で簡単に洗える"；"洗濯機可・ネット使用, ドライクリーニング可, 乾燥機不可"；"トップスフィット: 普通"；"中華人民共和国, カンボジア, ベトナム"
- 搜索摘要显示 SG（E453754）、US、IN、AU、AT 页同为 39% 棉 / 34% 聚酯 / 27% 人造丝（或 viscose），**无羊毛**。

### JP — シングルブレストコート（E487328，US 称 "Men's Balmacaan Coat"）
- URL: https://www.uniqlo.com/jp/ja/products/E487328-000/00
- 原文要点: 表地 "ポリエステル57%、毛33%、ナイロン10%"（其中 40% 为再生聚酯）；裏地 "ポリエステル100%"；"適度な膨らみのあるウールブレンド素材"；"水洗い不可, ドライクリーニング可, 乾燥機不可"；"ややゆとりのあるレギュラーフィット"、丈 ひざ下；生産国 "カンボジア"；模特 183cm/L

### JP — シングルブレストコート（E478284，US/IN 称 "Unisex Balmacaan Coat"）
- URL: https://www.uniqlo.com/jp/ja/products/E478284-000/00
- 原文: 表地 "67% ポリエステル, 33% 毛 ( 50% リサイクルポリエステル繊維を使用 )"；裏地 "100% ポリエステル"；"やわらかく、チクチクしにくいウールブレンドのダブルフェイス素材"；"水洗い不可, ドライクリーニング可, 乾燥機不可"；"ほどよいゆとりのリラックスシルエット。"；"製品原産地（縫製・編立・組立）: 中華人民共和国"
- SG 有 "Unisex Balmacaan Coat"（E481241）页面，搜索摘要称表布 67% 聚酯 / 33% 羊毛、仅干洗；**SGD 价格未取得**。

---
## SG 产品页（第二轮，2026-10-13 稍后时段 WebFetch 成功）

### SG — Lambswool Crew Neck Sweater（E479832）
- URL: https://www.uniqlo.com/sg/en/products/E479832-000/00
- 原文: "Product ID: 479832"；**"Fit: Relaxed"**；"100% Wool"；"Premium wool, tightly twisted for softness and warmth. Mid-gauge ribbed knit creates a striped effect. Hand-washable."（**无微米数**）；"Hand wash cold, Dry Clean, Do not tumble dry."；"Production: China"（JP 同款写 ベトナム）；"Model is 188 cm / Wearing size: L"

### SG — Souffle Yarn Crew Neck Sweater（E471229）
- URL: https://www.uniqlo.com/sg/en/products/E471229-000/00
- 原文: "Product ID: 471229"；**"Fit: Relaxed"**；**"57% Acrylic, 32% Polyester, 8% Wool, 3% Spandex ( 32% Uses Recycled Polyester Fiber )"**；"Generous cut at the shoulders and body, complemented by a wide collar." "Short length." "Hand-washable."；"Hand wash cold, Dry Clean, Do not tumble dry."；"Production: China"

### SG — Washable Milano Ribbed Crew Neck Sweater（E453754）
- URL: https://www.uniqlo.com/sg/en/products/E453754-000/00
- 原文: "Product ID: 490455" / "Product ID: 490455,486060,481722,478548,474203"；Fit 行：无；**"39% Cotton, 34% Polyester, 27% Rayon ( 34% Uses Recycled Polyester Fiber )"——不含羊毛**；"Machine washable." "Crisp, contouring knit fabric for a comfortable fit."；"Machine wash cold, gentle cycle, Dry Clean, Do not tumble dry."；"Production: China, Indonesia"；模特 184cm/XL、186cm/L、174cm/M

### SG — Cashmere Turtleneck Sweater (Long Sleeve)（E450544）
- URL: https://www.uniqlo.com/sg/en/products/E450544-000/00
- 原文: 标题 "Men's Cashmere Turtleneck Sweater (Long Sleeve) | UNIQLO SG"；"Product ID: 486076"；**"Fit: Regular"**；"100% Cashmere"；"Special pilling-resistant processing ensures the cashmere keeps its soft texture when hand-washed." / "Yarn thickness and knit tension have been perfected for a premium feel."；"Hand wash cold, Dry Clean, Do not tumble dry."；"Production: China"；"Model is 183 cm / Wearing size: L"

### SG — Merino Knitted Polo Shirt (Long Sleeve)（E460939）
- URL: https://www.uniqlo.com/sg/en/products/E460939-000/00
- 原文: 标题 "Men's Merino Knitted Polo Shirt (Long Sleeve) | UNIQLO SG"；"Product ID: 486064"；Fit 行：无（JP 同款 "トップスフィット: 普通"）；"100% Wool"；"Made with 19.5 micron extra-fine 100% Merino wool for a smooth touch and glossy sheen."；"Machine wash cold, gentle cycle, Dry Clean, Do not tumble dry."；"Production: Vietnam"

### SG — Balmacaan Coat（Unisex，E481241）
- URL: https://www.uniqlo.com/sg/en/products/E481241-000/00
- 原文: "Product ID: 481241"；"Moderately roomy, relaxed silhouette."；**"Shell: 67% Polyester, 33% Wool ( 50% Uses Recycled Polyester Fiber )/ Lining: 100% Polyester/ Pocket Lining: 100% Polyester"**；"Double face, wool blend fabric is soft and non-itchy."；**"Do not wash, Dry Clean, Do not tumble dry."**；"Production: China"；"Model is 173 cm / Wearing size: L"

### SG — Merino Cardigan（E450540）
- URL: https://www.uniqlo.com/sg/en/products/E450540-000/00 → **HTTP 404**（2026-10-13）。SG 站可能未上架该款；JP 版数据见上文。

### SG — Lambswool V Neck Cardigan（E469402）
- URL: https://www.uniqlo.com/sg/en/products/E469402-000/00 — 未直接打开；搜索摘要称 "100% 19.5-micron wool"、"hand-washable"、页头 ID 478547。JP 同款页直接读到 "約19.5マイクロンのウールを100％使用"。

### SG — Wool Cashmere Chesterfield Coat（E478285）
- URL: https://www.uniqlo.com/sg/en/products/E478285-000/00
- 访问日期: 2026-10-13（WebFetch 成功）
- 原文: "Product ID: 478285"；Fit 行：无；**"Shell: 90% Wool, 10% Cashmere/ Lining: 100% Polyester/ Pocket Lining: 100% Polyester"**；"Elegant and soft wool blend." / "Straight silhouette with a non-constrictive waist and relaxed shoulders." / "Moderately wide lapel and two-button design…"；"Do not wash, Dry Clean, Do not tumble dry."；"Production: China"；模特 185cm/L、186cm/L
- 价格：静态文本无；SGD **未取得**。搜索摘要称 US 页 $149.90（https://www.uniqlo.com/us/en/products/E470082-000/00 ，置信度：低）。

### UK — Wool Blend Chesterfield Coat（E459631，往季款号）
- URL: https://www.uniqlo.com/uk/en/products/E459631-000/00
- 访问日期: 2026-10-13（WebFetch 成功）
- 原文: "Product ID: 459631"；"Fit: Regular"；"Shell: 90% Wool, 10% Cashmere/ Lining: 100% Polyester…"；"Do Not Wash, Dry Clean, Not suitable for tumble-drying."；"Country/Countries of Production: China"；**"30-Day Lowest Price: £29.90"**（清仓价，非常规价）

### SG — 男装外套类目页
- URL: https://www.uniqlo.com/sg/en/men/outerwear/coats — WebFetch 静态文本仅约 450 字符，无商品卡（"There are no results containing your search terms."）。
- 搜索摘要称 SG 有 "Wool Blend Short Coat" S$129.90（Unisex、Limited Store），成分未核实，置信度：低。
