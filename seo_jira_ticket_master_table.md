# SEO Jira Ticket 总表（2026-08-18）

> 层级规则：板块 → Epic → Ticket → Sub-ticket（需单独拉评审才拆）；一次评审 = 一个 Ticket
> 新建 Ticket：标题英文，内容先英再中；标签：Business Area = UG - SEO ｜ Dependency Scope = Dev ｜ Dependency Status = To Be Scheduled
> 状态列 = **更新后的应有状态**；标注「🔄」的表示需要动手更新，直接按此修改
> 优先级：P0 = 进行中/高影响（开发、推全、异常需跟、DDL 临近）｜P1 = 待排期/重要｜P2 = 待调研/一般

---

## 🎯 FY27 业务目标（UC-105）

| Ticket | 标题 | 说明 |
|--------|------|------|
| UC-105 | SEO — FY27 Goal | D-AB2 43 → 180（4.2x）；FY27 Q4 目标 D-UV 71,251 / D-AB 373 / UV→AB 0.5% / AB→AB2 48.3%；季度/月度拆解见 ticket 描述；保持 UC-104 父级 |

---

## Epic 1：[🥗 Diet 做减法（UC-376）](https://visable.atlassian.net/browse/UC-376)

| Ticket | 标题 | 优先级 | Reporter | Assignee | Dependency Status | Dependency Scope | 说明 |
|--------|------|--------|----------|----------|---------------|---------|------|
| ARISE-1112 | 一期-缩减 filter（剔内链+剔 sitemap） | P0 | Xiaoyu Dou | Zhichen Bi | 灰度中 | Dev | 保持；上线后 → Done |
| ARISE-1251 | 移除低效 SERP URL | P1 | Xiaoyu Dou | Zhichen Bi | Closed | Dev | 保持；同时覆盖 W32 索引膨胀（CSERP 部分） |
| UC-277 | 移除低质 CPP URL | P0 | Jolyne Zhang | Xiaoyu Dou | To Be Scheduled | Dev | 🔄 上线后 → Done |
| ARISE-1248 | 有曝光垃圾词下线（301） | P1 | Zhichen Bi | - | Closed | Dev | 保持；覆盖 W32 蚕食治理（301 部分） |
| ARISE-1253 | 二期-filter 强信号 canonical | P1 | Xiaoyu Dou | Zhichen Bi | 待排期 | Dev | 保持 |
| ARISE-1254 | 二期-缩减分页 | P2 | Xiaoyu Dou | - | 待排期 | Dev | 保持 |


## Epic 2：[📈 Growth 拓词 · 词库（UC-137）](https://visable.atlassian.net/browse/UC-137)

| Ticket | 标题 | 优先级 | Reporter | Assignee | Dependency Status | Dependency Scope | 说明 |
|--------|------|--------|----------|----------|---------------|---------|------|
| ARISE-1092 | 一期+二期新增关键词 | P0 | Xiaoyu Dou | Zhichen Bi | 推全中（二期：待分析） | Dev | 保持；二期目标更新为 2w/月/站 |
| UC-381 | EP 优化专项 · ep.it 聚合（Copy of ARISE-1277） | P0 | Temitope Longe | Zhichen Bi | To Be Scheduled | Dev | ✅ 已迁移（普通 Task，UC 无 Story 类型）；挂 UC-137；原票 Zhichen To Be Scheduled |
| UC-382 | EP 优化专项 · ep.fr 聚合（Copy of ARISE-1279） | P0 | Temitope Longe | Zhichen Bi | To Be Scheduled | Dev | ✅ 已迁移（普通 Task）；挂 UC-137；原票 Zhichen To Be Scheduled |
| ├ UC-391 | City CSERP 1,085 旧 URL 内链更新 + sitemap 清理（Copy of ARISE-1278） | P0 | Temitope Longe | Xiaoyu Dou | To Be Scheduled | Dev | ✅ 已迁移（Subtask）；Xiaoyu；挂 UC-381；原票 To Do |
| ├ UC-392 | 首页无关链接移除，替换为合格 B2B 链接（Copy of ARISE-1281） | P0 | Temitope Longe | Xiaoyu Dou | To Be Scheduled | Dev | ✅ 已迁移；Xiaoyu；挂 UC-381；原票 In Progress |
| ├ UC-393 | CPP Similar/Popular 推荐模块修复（Copy of ARISE-1285） | P1 | Temitope Longe | Yunyi Xie | To Be Scheduled | Dev | ✅ 已迁移；Yunyi；挂 UC-381；原票 To Do |
| ├ UC-394 | 索引层覆盖分析 Indexation Coverage（Copy of ARISE-1287） | P1 | Temitope Longe | Temitope Longe | To Be Scheduled | Dev | ✅ 已迁移；Tope；挂 UC-382；原票 In Progress |
| ├ UC-395 | 新旧 CPP URL 去重合并（Copy of ARISE-1288） | P1 | Temitope Longe | Xiaoyu Dou | To Be Scheduled | Dev | ✅ 已迁移；Xiaoyu；挂 UC-382；原票 To Do |
| ├ UC-396 | Winner CPP 标题优化（地区+供应商搜索意图）（Copy of ARISE-1289） | P1 | Temitope Longe | Xiaoyu Dou | To Be Scheduled | Dev | ✅ 已迁移；Xiaoyu；挂 UC-382；原票 To Do |
| **新建** | `[SEO] Backlinks Phase 2: Merchant Program Execution` | P1 | Jolyne Zhang | - | To Be Scheduled | Self | ✅ 已建 UC-379（挂 UC-137）；🔄 原「Anna Review」改为**直接执行外链二期**（10 商家项目，PRD+设计已 ready，解决商家招募门槛）；业务 PRD 阶段，未到排期 |
| **新建** | `[SEO] Showroom New Hot Products Launch (X new/month + Y keyword dedup)` | P1 | Jolyne Zhang | - | To Be Scheduled | External | ✅ 已建 UC-380（挂 UC-137）；含商品质 量（合格/精品/定向/新热）+ 180 万增量品评估（已合并于此）；业务 PRD 阶段，未到排期；与发品团队联评 |
| UC-406 | 拓词来源质量提升（AB2 +0.5） | P0 | Jolyne Zhang | - | In Progress | Self | ✅ 已建（盘点补录）；漏斗表 CTR 列；@芷晨@大桔；8/18 盘点补录 |
| UC-407 | 核心词改写（AB2 +0.5） | P1 | Jolyne Zhang | - | In Progress | Self | ✅ 已建（盘点补录）；漏斗表 CTR 列；@芷晨@大桔；8/18 盘点补录 |
| UC-408 | 多语言词库质量（AB2 +0.5） | P1 | Jolyne Zhang | - | In Progress | Self | ✅ 已建（盘点补录）；漏斗表 CTR 列；@芷晨@大桔；8/18 盘点补录 |
| UC-409 | 多语言词库映射 | P1 | Jolyne Zhang | - | In Progress | Self | ✅ 已建（盘点补录）；漏斗5月表 P1；@技术；8/18 盘点补录 |
| UC-410 | 拓B类词/本本词（AB2 +1） | P0 | Jolyne Zhang | - | In Progress | Self | ✅ 已建（盘点补录）；漏斗表 UV-AB% 列；@芷晨@Tope；8/18 盘点补录 |
| UC-411 | 新频道页、新工具页（AB2 +1） | P1 | Jolyne Zhang | - | In Progress | Self | ✅ 已建（盘点补录）；漏斗表新渠道列；@晓宇@大桔；8/18 盘点补录 |
| UC-412 | 新站点（AB2 +1） | P1 | Jolyne Zhang | - | In Progress | Self | ✅ 已建（盘点补录）；漏斗表新渠道列；@Tope；8/18 盘点补录 |

## Epic 3：[🖱 CTR & On-Page 页面优化（UC-89）](https://visable.atlassian.net/browse/UC-89)

| Ticket | 标题 | 优先级 | Reporter | Assignee | Dependency Status | Dependency Scope | 说明 |
|--------|------|--------|----------|----------|---------------|---------|------|
| ARISE-1063 | TDH 文案分层优化 | P0 | Xiaoyu Dou | Xiaoyu Dou | 推全中 | Dev | 保持；覆盖 W32 CTR（TD 模板，+2115） |
| UC-228 | CPP/PDP H1 改版 | P0 | Jolyne Zhang | Zhichen Bi | 🔄 **To Be Scheduled**（原 To Be Scheduled） | Dev | ✅ 类型已修正（Epic → Task，8/18 已执行）；已在开发，状态必须更新 |
| UC-267 | CPP 有机→QDR 转化率分析（询盘漏斗） | P1 | Jolyne Zhang | Utkarsha Saraf | To Be Scheduled | Dev | ✅ 你确认归入 Epic 3；CPP 32% UV 仅 17% AB（QDR 占 94%），与 ARISE-1252 分析联动 |
| UC-131 | SERP 改版（商卡+底部 longtext）＝商卡信息透传 | P1 | Jolyne Zhang | - | To Be Scheduled（8.27 评审） | Dev | ✅ 已确认即「商卡信息透传」（策略表 #12，+0.5）；保持 |
| ARISE-1043 | Detail 页改版（PDP&CPP） | P0 | Yunyi Xie | Temitope Longe | 推全中 | Dev | 保持 |
| ARISE-1252 | Longtext 优化 | P1 | Xiaoyu Dou | Zhichen Bi | 待分析 | Dev | 保持；分析完成后评审再拆 Sub-ticket |

| UC-413 | 用户搜推相关性优化（UV-AB% +22%，AB2 +8） | P0 | Jolyne Zhang | - | In Progress | Self | ✅ 已建（盘点补录）；漏斗表最大增量项；@朱博@winnie@Ray；8/18 盘点补录 |
| UC-441 | 用户询盘体验优化（UV-AB% +11%，AB2 +4） | P0 | Jolyne Zhang | - | In Progress（大部分已上线） | Dev | @utkarsha；UG Update 7月评论：UV→AB 体验举措几乎全部 live（除 QDR with AI）；PRD：[QDR funnel](https://visable.atlassian.net/wiki/pages/viewpage.action?pageId=63340704) · [RFQ form/funnel](https://visable.atlassian.net/wiki/pages/viewpage.action?pageId=63340728) · [RFQ with AI](https://visable.atlassian.net/wiki/pages/viewpage.action?pageId=63340820) · [QDR with AI](https://visable.atlassian.net/wiki/pages/viewpage.action?pageId=296550416) |
| UC-442 | 用户二回询盘体验优化（AB2 +6） | P0 | Jolyne Zhang | - | In Progress（部分已上线） | Dev | @utkarsha；部分 live 部分 in progress；PRD：[Reminder Notification](https://visable.atlassian.net/wiki/pages/viewpage.action?pageId=63340593) · [Message Center Experience](https://visable.atlassian.net/wiki/pages/viewpage.action?pageId=63340607) · [Message Center with AI](https://visable.atlassian.net/wiki/pages/viewpage.action?pageId=63340781) · [PCG Polaris Roadmap](https://visable.atlassian.net/jira/polaris/projects/PCG/ideas/view/e86df0cd-b77f-4ea3-94e8-50ae38246577) |

## Epic 4：[🏭 PDP 增长计划（含 GMC & 结构化）（UC-377）](https://visable.atlassian.net/browse/UC-377)

| Ticket | 标题 | 优先级 | Reporter | Assignee | Dependency Status | Dependency Scope | 说明 |
|--------|------|--------|----------|----------|---------------|---------|------|
| **新建** | `[SEO] PDP P0: Double Eligible PDP Volume (3.5-score threshold, +52 AB)` | P0 | Jolyne Zhang | - | To Be Scheduled | External | ✅ 已建 UC-383（挂 UC-377）；wlw 41w / ep 增投 47w；若 P0-P2 一次评审全覆盖 → 合 1 票拆 4 Sub-ticket |
| **新建** | `[SEO] PDP P1: Quality Score to 4.5 (add text / dedupe / image alt)` | P1 | Jolyne Zhang | - | To Be Scheduled | External | ✅ 已建 UC-384（挂 UC-377）；17.6k→35k；图片 alt 由 SEO 团队负责 |
| **新建** | `[SEO] PDP P2: Core Keyword SV into Scoring (DSV +10%)` | P2 | Jolyne Zhang | - | To Be Scheduled | External | ✅ 已建 UC-385（挂 UC-377）；关键词质量；业务 PRD 阶段  ，未到排期 |
| **新建** | `[SEO] PDP P1: Structured Field Presentation (AB CVR +10%)` | P1 | Jolyne Zhang | - | To Be Scheduled | External | ✅ 已建 UC-386（挂 UC-377）；字段结构化呈现；业务 PRD 阶段，未到排期 |
| **新建** | `[SEO] GMC Enablement: Upload Priced PDPs (Shopping Organic, +1 AB2)` | P1 | Jolyne Zhang | - | To Be Scheduled | External | ✅ 已建 UC-387（挂 UC-377）；策略表 #16；前置 UC-351/352/362；业务 PRD 阶段，未到排期；原「GMC 独立 Epic」已并入本 Epic |
| UC-250 | PDP related products image url | P1 | Chao Wang | Zhenyu Liu | ✅ **To Be Scheduled**（已更新） | Dev | ✅ 类型已修正（Epic → Task，8/18 已执行）+ 已挂 UC-377；开发中 |
| UC-127 | 结构化数据（SEMrush review） | P2 | Jolyne Zhang | Jolyne Zhang | To Be Scheduled | Dev | 保持；关联到本 Epic |

## Epic 5：[🛡 Defense 防守（UC-179）](https://visable.atlassian.net/browse/UC-179)

| Ticket | 标题 | 优先级 | Reporter | Assignee | Dependency Status | Dependency Scope | 说明 |
|--------|------|--------|----------|----------|---------------|---------|------|
| ARISE-1173 | 前端性能优化 S1 | P1 | Temitope Longe | Zhenyu Liu | 5/7 已上线 | Dev | 保持 |
| **新建** | `[SEO] Botify Purchase Evaluation (≤$35k, budget request by end of Sep)` | P0 | Jolyne Zhang | - | To Be Scheduled | Self | ✅ 已建 UC-388（挂 UC-179）；9 月底 DDL；AB2 +2；当前调研阶段 |
| **新建** | `[SEO] wap2app Channel Goal Split` | P2 | Jolyne Zhang | - | To Be Scheduled | Self | ✅ 已建 UC-389（挂 UC-179）；业务在 align 目标（依赖牧可）；非开发 ticket，未到排 期 |
| UC-414 | url 优化 | P2 | Jolyne Zhang | - | To Be Scheduled | Self | ✅ 已建（盘点补录）；主要是要审查一下还有没有url问题；8/18 盘点补录 |

## Epic 6：[🔬 SEO 数据与 Agent 建设（UC-132，已改名复用）](https://visable.atlassian.net/browse/UC-132)

| Ticket | 标题 | 优先级 | Reporter | Assignee | Dependency Status | Dependency Scope | 说明 |
|--------|------|--------|----------|----------|---------------|---------|------|
| DAN-785 | SEO AB 周报数据异常（7/10 无法归因） | P0 | Muke Zhang | Olga Hincu | 🔴 需跟 | Dev | 数据侧工单，关联挂到本 Epic（原在技术 SEO Epic） |
| ARISE-1265~1273 | UV&AB 监控体系（全链路）+ 1276（APP）+ 1295（服务端） | P1 | Xiaoyu Dou | Xiaoyu Dou | 已完成/Backlog | Dev | 全部关联到本 Epic |
| ARISE-1189/1099/1108/1192 等 | SEO Agent 巡检/修复（30 条） | P1 | Xiaoyu Dou | Xiaoyu Dou | 已完成/进行中 | Dev | 全部关联到本 Epic |
| UC-29 | Spam Agent Workflow | P2 | Artur Iliasov | Artur Iliasov | Completed | Dev | 关联到本 Epic |
| **新建** | `[SEO] AB & AB2 Analysis Agent` | P1 | Jolyne Zhang | - | To Be Scheduled（待评审） | Dev | ✅ 已建 UC-390（挂 UC-132）；新增需求：SEO AB 和 AB2 分析 agent |

## Epic 7：[⚖️ 合规 · 风控（UC-214，已改名复用）](https://visable.atlassian.net/browse/UC-214)

| Ticket | 标题 | 优先级 | Reporter | Assignee | Dependency Status | Dependency Scope | 说明 |
|--------|------|--------|----------|----------|---------------|---------|------|
| UC-214 | 合规/风控专项 | P0 | Jolyne Zhang | Iris Napp | In Progress | Dev | 保持；关联到本 Epic |

---

## 待办汇总

| 类别 | 数量 | 明细 |
|------|------|------|
| 🏗 建 Epic | 7 | ✅ 全部就位：UC-376 Diet / UC-137 Growth（改名复用）/ UC-89 CTR-OnPage（改名复用）/ UC-377 PDP增长 / UC-179 Defense（改名复用）/ UC-132 数据与Agent（改名复用）/ UC-214 合规风控（改名复用） |
| 🔧 类型修正 | 2 | ✅ UC-228、UC-250：Epic → Task（8/18 已执行） |
| 🔗 关联工单 | 76 | ✅ 已关联：ARISE 固定 14 + Agent 群 62（含 1265~1295）+ DAN-785 + UC-127 + UC-131↔UC-89；UPR-43~46 原已有 Relates |
| 🎫 新建 Ticket | 29 | ✅ 已建：UC-379~390（12）+ UC-406~414（9 补录）+ UC-391~396（6 Subtask）+ UC-441~442（2 产品侧） |
| 🔄 状态更新 | 5 | ✅ 已执行：UC-228、UC-250、UC-89、UC-132、UC-137、UC-179、UC-214 → To Do；UC-277 → 上线后 Done（待上线） |
| 📋 盘点补录 | 11 | 漏斗表盘点补录（8/18，删 2 项；AI 可爬性已移至 GEO、品牌已移至 GEO）：拓词质量×3 + 多语言词库映射 + 拓B类词 + 新频道/工具页 + 新站点 + 搜推相关性（+8）+ 询盘体验×2（+4/+6）+ url优化；合计 AB2 +22.5；❌ 已删：页面主体相关性丰富度（ARISE-1043 已覆盖，Artur 离职）、站内体验（无对应项目）；⚠️ sitemap 已由 ARISE-1251/1238 覆盖、蚕食聚簇已由 ARISE-1248 覆盖，不重复建；✅ 已建 UC-406~414（9 项，8 项 In Progress Scope=Self + url 优化 P2 Triage）+ UC-441~442（2 项 In Progress，产品侧管理） |
| ✅ 已覆盖不新建 | 6 | 索引膨胀×2 / 新页索引 / 内链传导 / CTR-TD / 蚕食 |
| 📊 P0 高优 | 18 | 全量 P0（进行中/高影响）：ARISE-1112、UC-277、ARISE-1092、UC-381/382/391/392、ARISE-1063、UC-228、ARISE-1043、UC-413、询盘体验×2、PDP P0、UC-406/410、Botify、DAN-785、UC-132 |

> 附：UC-250（已修正为 Task）、UC-89（TDH and Longtext）已在开发，状态已更新为排期中（对应 Epic 3/4 内，按开发负责人当天更新原则处理）。
