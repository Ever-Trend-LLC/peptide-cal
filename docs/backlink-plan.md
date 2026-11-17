# 外链建设建议方案

站点：https://peptidecalculatorpro.org/  
数据来源：三份 Ahrefs 外链导出（`current-page-20261108-*.csv`），导出对象是竞品 **pathtopeptides.com**，不是本站。

## 1. 数据结论

- 共 253 条外链、228 个唯一域名。
- 其中约 200 个域名的来源页外链数超过 200 条（多数 3,000–5,000 条），标题和锚文本高度模板化，属于 PBN/链接农场，**不复制、不提交**。
- 只有 28 个域名是低外链数的真实内容站、工具站或社区。
- 这 28 个里，真正有公开提交入口的只有 **Wikipep** 和 **GLP1Chat**；其余只能做编辑外联或社区参与。
- 评论区外链基本是 `nofollow`，SEO 权重价值低，主要用于品牌曝光、引荐流量和建立编辑关系。优先级应放在编辑链接/客座投稿，而不是批量评论。

## 2. 已执行记录

| 站点 | 页面 | 类型 | 状态 |
|---|---|---|---|
| Robb Wolf | `/2024/01/13/semaglutide-psoriasis-magnesium-supplementation-thrr175/` | 博客评论 | 已提交，评论 ID `2624783`，待审核（11-17 复核：页面仍无该评论，WP REST API 显示该文已批准评论 0 条） |
| Dr. Kara Fitzgerald | `/2019/10/07/peptide-therapy-ready-for-prime-time-fxmed/` | 博客评论 | 已提交，评论 ID `113120`，待审核（11-17 复核：页面仍无该评论，WP REST API 显示该文已批准评论 0 条） |
| Dr. Jockers | `/episode-790-reverse-skin-aging-and-activate-longevity-genes-with-clinical-laser-therapy-at-home/` | 博客评论 | 已提交，评论 ID `2540873`，待审核（11-17 复核：页面仍无该评论，WP REST API 显示该文已批准评论 0 条） |
| Born Fitness | `/how-to-stay-fit-while-traveling/` | 博客评论 | 已提交，评论 ID `317026`，待审核（11-17 复核：页面仍无该评论，WP REST API 显示该文已批准评论 0 条） |
| GLP1Chat | https://glp1chat.com/account/signature | 论坛签名 | 已保存签名，含 `https://peptidecalculatorpro.org/`；nofollow |
| GLP1Chat | https://glp1chat.com/threads/new-guy.31122/ | 论坛回复 | 已在 Introduce Yourself 发计算类回复（纯文字、无链接、无剂量建议）。多数版块提示 `insufficient privileges`，需积累发帖数后再进技术版块 |
| Wikipep | https://wikipep.org/wiki/Special:CreateAccount | Wiki 账号 | 暂停：Turnstile 脚本可正常加载（302→200），但 widget 不渲染、隐藏字段恒为空，站方 sitekey 配置异常；无联系邮箱、无 `Special:RequestAccount`、匿名编辑强制登录，无绕过路径。另注：其 About 页外链指向 `groupbuykits.com` 与 `pepdex.app/vialdex/`，站点由 vendor/竞品体系运营，价值本身偏低 |
| GLP-1 Forum | https://glp1forum.com/register/ | 论坛账号 | 邮箱已确认，账号 `PepCalcPro2026` 可用。但 `/account/signature` 返回 Content Unavailable，账户设置页仅有用户名/邮箱/头像/横幅/生日/所在地，无签名字段也无 Website 字段，无法承载链接，仅能纯文字发言，暂停投入 |
| MESO-Rx | https://thinksteroids.com/community/account-details | 论坛资料 | 已填 Website `https://peptidecalculatorpro.org`、Location `Hong Kong`、Occupation `Peptide research and reconstitution math`，保存后重载验证通过；资料页外链为 nofollow |
| MESO-Rx | https://thinksteroids.com/community/threads/reconstitution-math-u-100-units-are-volume-not-mg.134451360/ | 论坛帖子 | 已在 Human Growth and Peptides 版块发帖，纯 U-100 体积换算内容，无链接、无剂量建议；账号用户名为 `vikiwu`，与品牌名不一致。11-17 复核：帖子存活，已有 1 条回复，无删除/限流标记 |

已跳过：

- **Ruled.me**：评论表单没有 Website 字段，无法放链接，只发纯评论没有外链价值。
- **Mark's Daily Apple**：已迁移到 Substack，评论必须登录 Substack 账号。

## 3. 可直接提交/注册

| 站点 | 入口 | 适用性 | 动作 |
|---|---|---|---|
| **Wikipep** | https://wikipep.org/wiki/Special:CreateAccount | 肽百科 MediaWiki，可编辑/新增条目 | 暂停：站方 Turnstile 配置异常，注册无法完成，详见 §2 |
| **GLP1Chat** | https://glp1chat.com/register/ | GLP-1 论坛，受众精准 | 完成邮箱确认后，先参与 2–3 个剂量/复溶/平台期讨论，再在资料或签名放链接；nofollow |
| **The Hive Index** | https://thehiveindex.com/submit/ | 只收社区/论坛 | 暂不适用；若未来上线社区/论坛再提交 |
| **HiveFindr** | https://hivefindr.com/sign-up | 只收 community listing | 同上 |
| **Machine Relations Index** | https://machinerelations.ai/index/domains/pathtopeptides.com | 人工索引，无公开提交入口 | 只能尝试联系，优先级低 |
| **ThePeptidesForum** | https://thepeptidesforum.org/register | 肽类论坛，XenForo 资料页含 Website 字段 | 注册后填资料；需人工审核，nofollow |
| **LongeCity** | https://www.longecity.org/forum/ucp.php?mode=register | 长寿/抗衰论坛，phpBB 资料页含 Website | 注册后填资料，nofollow |
| **SaaSHub** | https://www.saashub.com/submit | 通用软件目录 | 提交即可，多半 nofollow |
| **Show HN** | https://news.ycombinator.com/submit | Hacker News 展示 | 免费即发，账号需有一定活跃度 |

已关闭：

- **AlternativeTo**：提交需付费，放弃。
- **SciCrunch / RRID**：此前已提交过。
- **bio.tools**：条目 `peptide_calculator_pro` 已存在且字段完整（topics 为 Protein properties / Biochemistry / Chemistry，3 个 EDAM operation，3 条子页面链接），仅 `credit`、`publication` 空缺，`editPermission` 为 private，无需重复提交。
- **OMICtools**：域名已停用并转为垃圾页。
- **bioinformatics.ca** 链接目录：已 404 下线。

## 4. 外联目标

这些站点在竞品外链里出现，但链接大概率是编辑引用或付费合作，不能直接表单提交。按相关性和可执行性排序：

| 优先级 | 站点 | 联系方式 | 建议角度 | 目标落地页 |
|---|---|---|---|---|
| P0 | **ADW Diabetes** | writeforus@adwdiabetes.com / https://www.adwdiabetes.com/articles/write-for-us | GLP-1 用药者的剂量、复溶、units 换算 | 剂量页 / 复溶页 |
| P0 | **Yanre Fitness** | submit@yanrefitness.com / https://www.yanrefitness.com/write-for-us/ | 健身圈肽类使用趋势 + 复溶/剂量计算 | 首页 / 复溶页 |
| P0 | **Telehealth Ally** | https://telehealthally.com/contact | BPC-157/TB-500 指南补“剂量换算工具” | 剂量页 |
| P1 | **InCareNow** | https://www.incarenow.com/contact/ | CJC-1295 方案文章补 calculator 资源 | 剂量页 / 首页 |
| P1 | **Mantelligence** | editorial@mantelligence.com / https://mantelligence.com/write-for-us/ | 男性健康、健身恢复、循证肽类科普 | 首页 / 剂量页 |
| P1 | **Peptides Today** | https://peptidestoday.ca/contact/ | COA/剂量科普，偏编辑投稿 | 剂量页 |
| P1 | **Herbila** | https://herbilabs.co.uk/contact/ | 葡语复溶指南，可谈互链/客座 | 复溶页 |
| P1 | **PepFlow** | hi@pepflow.app | 肽类工具站，可谈工具互推 | 首页 |
| P2 | **Peptide Atlas** | https://peptideatlas.health/contact | 肽类科普库，可投稿 | 复溶页 / 剂量页 |
| P2 | **Peptides Made Clear** | https://peptidesmadeclear.com/about | 有编辑政策，走 guest/editorial pitch | 剂量页 |
| P2 | **Peptide News Digest** | https://peptidenewsdigest.org/about/ | 行业媒体，适合投稿而非外链 | 首页 |
| P2 | **Doserly / Peptidelit / Peptide Cortex** | 站内联系 | 剂量/计算器类站点，可谈合作 | 对应工具页 |

## 5. 明确不投

- **PBN/链接农场**：`100ranking.*`、`24rankings.info`、`backlinkbot.*`、大量 `*.shop`、赌场/体育/SEO 服务页，以及所有来源页外链数 3,000–5,000 的模板页。
- **供应商产品页**：SMolecule、RUO Peptide Labs、HK Peptide Store、Peptiva Sale、Ground Truth Peptides、PepRP、Peptide Purity Report。这些是商品页，不是外链渠道。
- **搜索引擎结果页**：`no.search.yahoo.com` 为抓取产物，不可提交。
- **无 Website 字段的评论区**：如 Ruled.me，只能留纯评论，不产生外链。

## 6. 锚文本与落地页

| 落地页 | 主锚文本 | 备用锚文本 |
|---|---|---|
| 首页 `/` | `peptide calculator` | `peptide calculator pro`、裸 URL |
| 剂量页 `/peptide-dosage-calculator/` | `peptide dosage calculator` | `peptide dose calculator`、`mg to units calculator` |
| 复溶页 `/peptide-reconstitution-calculator/` | `peptide reconstitution calculator` | `reconstitution calculator`、`how much BAC water` |
| BAC water 页 `/bac-water-calculator/` | `BAC water calculator` | `bacteriostatic water calculator` |
| mg-to-mL 页 `/mg-to-ml-calculator/` | `mg to mL calculator` | `mg to ml conversion` |
| 博客 | 品牌名 + 裸 URL | 长尾问题型锚文本 |

规则：

- 同一外联批次不要重复同一个精确匹配锚文本。
- 首页、剂量页、复溶页三个主力页各占外链的大头；BAC water 和 mg-to-mL 做辅助。
- 不复制竞品的 `Path to Peptides - CJC-1295...` 这类品牌+产品精确锚文本。

## 7. 执行节奏与验收

每周：

1. 发 2–3 封编辑/客座 pitch（P0 优先）。
2. 完成 1 个社区/论坛的有效参与（GLP1Chat 或 Wikipep）。
3. 记录新外链，4 周后复盘一次。

验收目标：

- 剂量页排名 4 周内从约 98 名进入前 30。
- GSC 曝光从 2 次增长到几十次。
- 新增至少 3 条真实编辑/客座外链（不是评论/PBN）。

追踪字段建议：日期、站点、页面 URL、外链类型、锚文本、落地页、`rel` 属性、状态、最终上线 URL。

## 8. 风险与备注

- 健康类内容属于 YMYL，稿件写成“计算/换算科普”，不要写成用药建议。
- 评论和论坛链接多为 `nofollow`，不要把排名目标押在评论上。
- 付费链接需遵守对方站点的 disclosure 要求；不确定是否 dofollow 的，上线后用浏览器或 Ahrefs 复核。
- 外链能否上线取决于编辑审核，本方案不保证每条都通过。

## 9. 专家引用平台（Qwoted / Featured / SourceBottle）

记者征集专家观点，被采用后通常能拿到正文里的编辑链接，单条价值高于评论。

| 平台 | 注册入口 | 提问可见性 | 费用 | 门槛 |
|---|---|---|---|---|
| Qwoted | https://app.qwoted.com/users/sign_up | 需登录（`/source_requests` 会跳登录） | 免费 Basic，2 次投稿/月 | 无持证要求；资料须用真实姓名 |
| Featured | https://featured.com/signup | 需登录（首页写明 “Log in to search, save, and respond to journalist requests”） | 免费版 3 次回答/月 | 无持证要求 |
| SourceBottle | https://www.sourcebottle.com/subscribe.asp | 公开可见：https://www.sourcebottle.com/industry-list.asp | 免费账户 | 要求“确有相关专业经验” |

执行建议：

- 身份用品牌名 + `dev@evetrend.com`，简介写 “free peptide reconstitution & dosage math tools”，避免写成医疗专家。
- 回答角度限定在换算与计算（mg/mL、U-100 units、doses per vial），不要给用药建议，符合 YMYL 安全边界。
- SourceBottle 以澳洲媒体为主，GLP-1 选题频率低；Qwoted 免费额度只有 2 次/月，只投最相关的题。

## 10. 资源页/工具页外链

已核实页面真实存在且确实列有外部站点，适合以“免费计算器工具”为由联系加挂。

| 优先级 | 站点 | 页面 | 页面现状 | 联系方式 |
|---|---|---|---|---|
| P0 | PeptideJournal | https://www.peptidejournal.org/reference/peptide-databases-research-resources | 已列 UniProt、PMC、ClinicalTrials.gov | 无公开邮箱，走站内表单 |
| P0 | Peptide Authority | https://peptideauthority.co.uk/tools/dosage-calculator | 已有 dosage calculator，正文引 PubMed/NHS | contact@peptideauthority.co.uk |
| P0 | PepFlow | https://pepflow.app/blog/best-peptide-calculator-apps/ | 榜单页，已列 pepcalc.app、dosii.app 等 | hi@pepflow.app |
| P1 | GLP-1 Collective | https://glp1collective.org/resources/ | 工具目录，列 glp1coach.app 等 | contact@glp1collective.org |
| P1 | BodyHackGuide | https://www.bodyhackguide.co/resources/ | 资源中心，列多个 subreddit | support@bodyhackguide.co |
| P1 | HighPeptides | https://highpeptides.com/compare/thepeptidelist-alternatives/ | 榜单页，列 PubMed、Examine 等 | contact@highpeptides.com |
| P2 | PepStack | https://www.pepstack.net/en | 免费工具区 | support@pepstack.net |
| P2 | Reta Support | https://retasupport.com/glp-1-protein-guide/ | 页末列 MedlinePlus、NIDDK、FDA | support@abxapps.com |

注意：Peptide Authority 和 PepFlow 本身也做剂量计算器，是竞品，谈互链要接受“工具对比/并列推荐”而不是唯一推荐。

## 11. Quora / Reddit 回答选题

先答后链，链接优先落到博客文章而不是首页，降低被判定为推广的概率。

| 平台 | 问题 | 落地页 | 备注 |
|---|---|---|---|
| Quora | https://www.quora.com/What-is-a-peptide | `/blog/what-is-a-peptide/` | 可先答后链，需披露关联 |
| Quora | https://www.quora.com/What-do-peptides-do | `/blog/what-are-peptides-used-for/` | 同上 |
| Quora | https://www.quora.com/How-much-peptide-sterile-water-do-you-add-using-a-100-unit-insulin-syringe-to-reconstitute-20mg-of-TIRZEPATIDE | `/blog/how-much-bac-water-to-add/`、`/bac-water-calculator/` | 只给计算示例，不回答“该打多少” |
| Reddit | r/Biohackers — What exactly are peptides and why do people use them | `/blog/what-is-a-peptide/` | 版规未核实，先纯文字 |
| Reddit | r/PeptideGuide — Bacteriostatic water question | `/blog/how-much-bac-water-to-add/` | 先纯文字 |
| Reddit | r/GLP1ResearchTalk — Reconstitution, how much BAC water? | `/blog/how-much-bac-water-to-add/` | 先纯文字 |
| Reddit | r/Peptides_for_Women — BAC water + dosage | `/blog/how-much-bac-water-to-add/` | 先纯文字 |
| Reddit | r/PeptideGuide — Is there no difference between BAC water and sterile water? | `/blog/bac-water/` | 先纯文字 |
| Reddit | r/Peptidesource — How many doses are in the vial? | `/blog/how-many-doses-per-vial/` | 先纯文字 |
| Reddit | r/PeptideForum — Question about GLP1 peptide amounts/dosage | `/blog/how-many-doses-per-vial/` | 先纯文字 |

Reddit 账号需先有 karma 才不易被删；建议先把前两个 Quora 回答写完，Reddit 用纯文字建立历史后再放链接。

## 12. 资源页 pitch 邮件草稿

发件人：`Peptide Calculator Pro <dev@evetrend.com>`。三条都按“免费工具、无商业诉求、可拒绝”的调性写，回复率高于一上来谈互链。

**A. Peptide Authority — contact@peptideauthority.co.uk**

Subject: Free peptide reconstitution calculator for your dosage tool page

Hi,

I run Peptide Calculator Pro (https://peptidecalculatorpro.org), a free browser-based calculator for peptide reconstitution and dose math.

I found your dosage calculator page at https://peptideauthority.co.uk/tools/dosage-calculator and noticed you reference ClinicalTrials.gov, PubMed and NHS guidance alongside the math. That is the same approach we take.

If it is useful for your readers, our reconstitution calculator (https://peptidecalculatorpro.org/peptide-reconstitution-calculator/) works backwards from a target syringe mark to the water volume, which is the step people most often get wrong. Happy to be listed as one alternative next to your own tool, not instead of it.

No obligation either way — thanks for publishing clear math in this space.

Peptide Calculator Pro
https://peptidecalculatorpro.org

**B. PepFlow — hi@pepflow.app**

Subject: Suggestion for your "best peptide calculator apps" roundup

Hi,

Came across your roundup at https://pepflow.app/blog/best-peptide-calculator-apps/ — the comparison by use case is more useful than most lists out there.

One candidate you may not have reviewed: https://peptidecalculatorpro.org. It is free, runs entirely in the browser, and focuses on three things your list calls out as deciding factors: reverse solving for water volume, multi-peptide blend vials, and doses-per-vial plus days of supply. No account, no paywall.

If it fits your criteria, I would appreciate a look. If it does not meet the bar, an honest reason would be genuinely helpful — we would rather fix the gaps than pitch again.

Peptide Calculator Pro
https://peptidecalculatorpro.org

**C. PeptideJournal — 站内表单**

Subject: Addition to your peptide databases & research resources page

Hi,

Your reference page (https://www.peptidejournal.org/reference/peptide-databases-research-resources) is one of the few that keeps the database list current. Thank you for maintaining it.

If you keep a tools section alongside the databases, we built a free sequence and vial calculator that may fit: https://peptidecalculatorpro.org/peptide-molecular-weight-calculator/ returns average and monoisotopic mass from a pasted sequence, and the reconstitution calculator handles mg/mL and U-100 unit conversions.

Entirely your call — I know the page is curated rather than a link list.

Peptide Calculator Pro
https://peptidecalculatorpro.org

## 13. Quora 回答草稿

规则：先给出完整可用的答案，链接放在最后一段并说明是自建工具；不要给剂量建议。

**Q1 — https://www.quora.com/What-is-a-peptide**

A peptide is a short chain of amino acids joined by peptide bonds. In regulatory and biochemical usage, anything up to roughly 40–50 amino acids counts as a peptide; beyond that the same chain is usually called a protein.

The practical difference is not just length. Proteins fold into complex three-dimensional shapes, which makes them fragile and too large to cross the skin or gut barrier intact. Peptides are short enough to stay stable and to bind receptors directly, which is why most of them work as signals rather than structure: insulin, GLP-1, oxytocin and glutathione are all peptides your body makes and uses every day.

A useful way to picture it: amino acids are letters, peptides are words, proteins are whole books. Same alphabet, different job.

I wrote a longer explainer with the bond chemistry and the peptide-vs-protein comparison table here if you want the details: https://peptidecalculatorpro.org/blog/what-is-a-peptide/ (full disclosure: that is my site).

**Q2 — https://www.quora.com/What-do-peptides-do**

Most peptides act as messengers, not building material. They bind a specific receptor on a target cell and tell that cell to do something — release a hormone, start collagen synthesis, open a glucose channel.

The categories people usually mean when they ask this:

- **Cosmetic peptides** mimic collagen fragments (signal peptides), carry copper into skin (GHK-Cu), or soften expression lines (argireline).
- **Metabolic peptides** are the GLP-1 class — semaglutide and tirzepatide are engineered versions of a gut hormone that slows gastric emptying and signals satiety.
- **Recovery peptides** like BPC-157 and TB-500 have animal data but limited human trials and are banned by WADA.
- **Collagen peptides** in supplements are simply hydrolysed protein — food, not signalling.

One honest caveat: "peptide" is a chemical class, not a safety category. A moisturiser peptide and an injectable hormone analogue sit under the same word and carry completely different risk.

I put the evidence and the approved-drug table together here: https://peptidecalculatorpro.org/blog/what-are-peptides-used-for/ (my site).

**Q3 — 20 mg tirzepatide, 100-unit syringe, how much water**

The water volume is your choice — it does not change how much peptide is in the vial, it only changes how concentrated each mL is. So the answer depends on the dose your prescriber gave you.

The math:

- concentration = mg in vial ÷ mL of water
- volume per dose (mL) = dose in mg ÷ concentration
- units on a U-100 syringe = mL × 100

With a 20 mg vial:

| Water added | Concentration | 2.5 mg dose | 5 mg dose | 10 mg dose |
|---|---|---|---|---|
| 2 mL | 10 mg/mL | 0.25 mL = 25 units | 0.5 mL = 50 units | 1.0 mL = 100 units |
| 4 mL | 5 mg/mL | 0.5 mL = 50 units | 1.0 mL = 100 units | 2.0 mL = 200 units |
| 8 mL | 2.5 mg/mL | 1.0 mL = 100 units | 2.0 mL (exceeds syringe) | — |

Two things worth flagging: pick a volume that keeps your actual dose comfortably inside the syringe barrel (a 100-unit syringe holds 1 mL, so the 4 mL option pushes larger doses past the limit), and use the volume you actually measured, not the one you planned.

Also, U-100 "units" are volume marks — 100 units = 1 mL — not international units of drug.

I built a free calculator that does this both ways, including solving for the water volume from a target syringe mark: https://peptidecalculatorpro.org/bac-water-calculator/ (my site, no account needed). But please confirm the dose itself with whoever prescribed it — that part is not a math question.

## 14. WikiPep 现状

`https://wikipep.org/api.php?action=query&list=users&ususers=PeptideCalculatorPro` 返回 `"missing"`，账号仍未创建。Cloudflare Turnstile 在自动化浏览器里不渲染，只能人工在浏览器完成一次注册；建好后可补条目并回填本节。

## 15. 竞品 pepuniversity.com 数据与 disavow 清单

来源：`current-page-20261116-225840.csv`（100 行）、`current-page-20261116-230115.csv`（31 行）、`disavow_20261116*.txt`（100 / 200 / 261 条递进版本）。

**CSV 结论**：131 条里 130 条是外链数 3,000–5,000 的 PBN（`*.shop`、`*.site`、`*.online`、`bloggazza/onesmablog/ampblogs` 一类日志农场）。唯一真实渠道是：

- **glp1forum.com** — `https://glp1forum.com/threads/cerebrolysin-first-cycle.8620/page-9`（快照外链数 13，真实论坛讨论帖）。性质与 GLP1Chat 类似，可注册后参与剂量/复溶讨论，属于新增社区渠道。

**disavow 结论**：这份清单是 semrush 导出，261 条里混合了两类，**不能整份照抄**：

- PBN 部分（`theforbestimes`、`missburrg`、`mydailyhero`、`uncledspizza`、`*.shop`、SEO 模板路径 `/outreach-directory/`、`/link-juice-directory/` 等）——这部分可直接作为我们的负面筛除规则。
- 真实内容站部分——被一并 disavow 属于过度清洗，对我们反而是**候选目标名单**：

| 类型 | 站点 | 可谈角度 |
|---|---|---|
| 竞品计算器 | `peptidescalculator.org`、`truepeptidesource.com/calculators/cost-supply`、`doserly.com`、`peptidecortex.com/dosing` | 工具并列推荐/互链，接受“对比”而非唯一推荐 |
| 内容站可 pitch | `oneskin.mom`、`biotechresearch.co.uk`、`peptidevox.com`、`thepeptidetoolkit.com`、`maylene.uk`、`peptijournal.com`、`peptifact.com`、`findpeptideclinics.com`、`researchknowledgehub.com`、`onpeps.com`、`peptpath.com` | 科普文里补“计算/换算工具”引用 |
| 复溶类长尾 | `peptidesvietnam.com`（how much BAC water for 50mg GHK-Cu）、`pepuralabs.ca`（how to reconstitute retatrutide）、`peptidesmadeclear.com` | 与现有复溶页直接对口 |
| 已有目标 | `telehealthally.com`、`peptideatlas.health`、`peptidelit.com` | 见第 4 节 P0/P2 |

**待筛除**：`vialfiles.com`、`peptidecompass.net`、`pepsavvy.com`、`pepteca.com`、`pepnex.cc`、`peply.cc`、`peplux.cc`、`pepiteverte.com`、`pepecatcher.com` 这类内容极薄或路径为随机字符串的站，疑似同一批程序化建站，不作为外联目标。

## 16. 其他上传文件

- `342e2c4cd7fc435da2e1681771645397.xlsx`：评论/个人资料页外链机会表，目标站为 `sprunki-game.io`、`basketballrandom.com`、`leveldevilgame.com` 等游戏站，与肽站无关。可借鉴的只有字段模板（Type / URL / Discovered From / Has Captcha / Link Strategy / Link Format / Has URL Field）。
- `StyleMirror_AI_HK300_Pitch_final.pptx`：服装 AI 试穿产品路演（stylemirrorai.com，HK$100k 预算），与本站无关。
