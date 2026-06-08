# miranda-li.net 网站内容文档

> 修改流程：先在此文件改内容 → 再同步到对应 HTML 文件。
> 每个区块标注了对应的 HTML 文件路径和关键定位词，方便精准同步。

---

## 全站基础信息

| 项目 | 值 |
|------|-----|
| 域名 | miranda-li.net |
| 密码保护 | `miranda2026`（career / critical-thinking / wonderful-life 三页） |
| 主色调 | 黄 `#f5d200` / 黑 `#1c1c1c` |
| 字体 | Barlow（英文展示）· IBM Plex Mono（标签/细节）· Noto Sans SC（中文） |
| 版权年份 | 2026 |

---

## 页面目录结构

```
miranda-li.net/
├── index.html              封面（首页）        — 无密码
├── me/index.html           Me · 关于我         — 无密码
├── career/index.html       Career · 职业高光   — 密码保护
├── critical-thinking/      Critical Thinking   — 密码保护
│   ├── index.html
│   ├── fullerton/index.html        (文章页 EN)
│   └── fullerton-cn/index.html     (文章页 中文)
├── wonderful-life/index.html   Wonderful Life  — 密码保护
├── resume/cn/index.html        简历（中文）    — 无密码
└── resume/en/index.html        简历（英文）    — 无密码
```

---

## 页面 01 · 封面 `index.html`

**文件路径：** `index.html`

### 左栏 — 身份标语

```
大标题（display）：
MIRANDA
LI

副标题（lead）：
ESG & Sustainability Strategist.
Executive background across five industries —
now on the right side of the transition.
```

### 左栏底部信息条（3列）

| 左 | 中 | 右 |
|----|----|----|
| ESG · Sustainability / 2026 | Strategy & Transition | miranda-li.net |

### 右栏 — 导航卡片（Hub）

| 编号 | 标题 | 副标题 | 链接 |
|------|------|--------|------|
| 01 | Me | Who I Am | `me/` |
| 02 | Career | Track Record | `career/` |
| 03 | Critical Thinking | Research & Views | `critical-thinking/` |
| 04 | Wonderful Life | The Other Side | `wonderful-life/` |

---

## 页面 02 · Me `me/index.html`

**文件路径：** `me/index.html`
**密码保护：** 无

### Hero 区块

```
眉标（eyebrow）：01 · Me

大标题：ME

正文（hero-desc）：
I've sat in a lot of those rooms.
Aviation. Real estate. Energy. Finance. Defense.

The choice, when it came, was easy.
```

> **待填充区域：** 目前 me 页只有 Hero 和 Footer，没有 Section 内容。
> 后续可按计划增加：「How I Got Here」叙述 + CV 卡片入口。

### Footer

```
左：Miranda Li · Me
右：miranda-li.net · 2026
```

---

## 页面 03 · Career `career/index.html`

**文件路径：** `career/index.html`
**密码保护：** 是（密码 `miranda2026`）
**Hero 背景图：** `https://images.unsplash.com/photo-1436491865332-7a61a109cc05?w=1600&q=80`（飞机航空场景）

### Hero 区块

```
眉标：02 · Career

大标题：CAREER

副标题：Fifteen years. Five industries. Decisions that mattered.
```

### Section 01 · Track Record

**标签：** `01 · Track Record`
**标题：** `HIGHLIGHTS`

| 行业标签 | 内容 |
|---------|------|
| Aviation | Operated **ASPIRE** multi-sector green demonstration flight SQ11 (LAX → TYO → SIN) — **10,686 kg fuel saved, 33,769 kg CO₂ reduced** |
| Aviation | Led CAAC safety compliance overhaul — **4 operational systems** restructured; **1,200+ tonnes fuel saved annually**, ~**3,800 tonnes CO₂ reduced**; zero regulatory violations throughout tenure |
| Real Estate | ESG disclosure framework and green finance alignment across a **HK property group** — **19 properties + 3 hotels** |
| Real Estate | Spearheaded rooftop solar programme — **3,000+ panels, 8M kWh/yr** generation capacity |
| New Energy | **Green industry** investment & development — advanced materials venture with **15 patents**, sole-supplier status, **75% reduction** in production cycle; **RMB 100M** equity financing closed |
| New Energy | Initiated **hydrogen energy strategy in Xinjiang**; military-civil integration compliance across new energy portfolio |
| Investment | 18-month LP-led ESG transformation of sustainable materials supply chain — EU market **5 → 11 countries**; Sustainalytics upgraded to **ESG Low Risk**; add-on rate **+4.1%** |
| Governance | Cross-sector **ESG risk governance**, philanthropy fund operations, and CSR programme management |

### Section 02 · Industries

**标签：** `02 · Industries`
**标题：** `FIVE INDUSTRIES`

| 行业名称 | 描述 |
|---------|------|
| Aviation | Civil & commercial aviation, regulatory compliance, carbon management |
| Real Estate | Commercial & residential development, green assets, ESG reporting |
| New Energy | Hydrogen, solar, advanced materials, military-civil integration |
| Investment | Responsible investment, ESG risk governance, PE-stage financing |
| Defense-Civil | Military-civil fusion strategy, compliance, government liaison |

### Section 03 · On Paper（简历卡片）

**标签：** `03 · On Paper`
**标题：** `RESUME`
**正文：** `Full professional history in Chinese and English.`

| 卡片 | 标题 | 链接 |
|------|------|------|
| 中文版 | 李梦婷・ 简历 | `/resume/cn/` |
| English | Miranda Li ・ CV | `/resume/en/` |
| 中文版（信和版） | 李梦婷・ 简历 · 信和版 | `/career/resume/cn/` |
| English（Sino） | Miranda Li ・ CV · Sino | `/career/resume/en/` |

### Footer

```
左：Miranda Li · Career
右：miranda-li.net · 2026
```

---

## 页面 04 · Critical Thinking `critical-thinking/index.html`

**文件路径：** `critical-thinking/index.html`
**密码保护：** 是
**Hero 背景图：** `https://images.unsplash.com/photo-1455390582262-044cdead277a?w=1600&q=80`（书桌/笔记场景）

### Hero 区块

```
眉标：03 · Critical Thinking

大标题：CRITICAL
THINKING

副标题：Observations from different industries. Unfinished thinking.
```

### Section 01 · ESG in Practice

**标签：** `01 · ESG in Practice`
**标题：** `ESG IN PRACTICE`

| 日期 | 标题 | 标签 |
|------|------|------|
| Coming soon | — | |

### Section 02 · ESG Frameworks

**标签：** `02 · ESG Frameworks`
**标题：** `ESG FRAMEWORKS`

| 日期 | 标题 | 标签 |
|------|------|------|
| Coming soon | GRI vs ISSB — What's the Difference? | Frameworks |
| Coming soon | TCFD in Practice — A Field Guide | Climate Risk |
| Coming soon | GRESB for Real Estate — Key Metrics | Real Estate |
| Coming soon | CORSIA and Aviation Carbon Markets | Aviation |
| Coming soon | CDP Disclosure — What Actually Matters | Reporting |

### Section 03 · Sector Views

**标签：** `03 · Sector Views`
**标题：** `SECTOR VIEWS`

| 日期 | 标题 | 标签 | 链接 |
|------|------|------|------|
| 2026 | Fullerton — Where Next? | EN | `/critical-thinking/fullerton/` |
| 2026 | 富丽敦 · 下一站在哪里？ | 中文 | `/critical-thinking/fullerton-cn/` |
| Coming soon | Sino | | |
| Coming soon | Satellai | | |
| Coming soon | Donghai | | |
| Coming soon | YGTF | | |

### Section 04 · Notes

**标签：** `04 · Notes`
**标题：** `NOTES`

| 日期 | 标题 | 标签 |
|------|------|------|
| Coming soon | Thinking | |
| Coming soon | Noting | |

### Footer

```
左：Miranda Li · Critical Thinking
右：miranda-li.net · 2026
```

---

## 页面 05 · Wonderful Life `wonderful-life/index.html`

**文件路径：** `wonderful-life/index.html`
**密码保护：** 是
**Hero 背景图：** `https://images.unsplash.com/photo-1506905925346-21bda4d32df4?w=1600&q=80`（山景/旅行场景）

### Hero 区块

```
眉标：04 · Wonderful Life

大标题：WONDERFUL
LIFE

副标题：The things that exist outside the resume.
```

### Section 01 · Travel

**标签：** `01 · Travel`
**标题：** `TRAVEL`
**正文：** `Places that changed how I think.`
**内容：** Coming soon（占位符）

### Section 02 · Reading

**标签：** `02 · Reading`
**标题：** `READING`
**正文：** `Books, papers, and things worth a second read.`
**内容：** Coming soon（占位符）

### Section 03 · Moments

**标签：** `03 · Moments`
**标题：** `MOMENTS`
**正文：** `The rest of it.`
**内容：** Coming soon（占位符）

### Footer

```
左：Miranda Li · Wonderful Life
右：miranda-li.net · 2026
```

---

## 简历页（网页版）

### 中文简历 `resume/cn/index.html`

ESG 方向简历，公开访问。

### 英文简历 `resume/en/index.html`

ESG 方向简历（英文），公开访问。

### 中文简历（信和版）`career/resume/cn/index.html`

针对信和集团定制版本，密码保护页面下的链接跳转。

### 英文简历（信和版）`career/resume/en/index.html`

针对信和集团定制版本，密码保护页面下的链接跳转。

---

## 同步操作说明

修改此文档后，同步到网站步骤：

1. **找到对应 HTML 文件**（见每个页面的「文件路径」）
2. **定位要改的区块**，用各 section 的标签文字（如 `01 · Track Record`）搜索
3. **逐条替换文字内容**，保持 HTML 标签结构不变
4. **git commit & push** → GitHub Pages 自动部署（约 1-2 分钟生效）

> 图片 URL 修改：直接替换 `<img src="...">` 里的 Unsplash 链接即可，格式保持 `?w=1600&q=80`
