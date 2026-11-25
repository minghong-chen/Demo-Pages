# AGENTS.md · 给接手维护的 AI

这是「小&陈的 Demo 收藏夹 · 夏日画廊」的网站仓库，GitHub Pages 从 `docs/` 发布：
<https://minghong-chen.github.io/Demo-Pages/>

## 整体风格：吉卜力

整个网站是**吉卜力风格的夏日手绘画廊**，以后任何改动都要守住这个风格：

- **画面**：首图、卡片缩略图和新增的任何插画，都用吉卜力式手绘水彩——蓝天积云、草地野花、红屋顶小屋、暖光与微风感；不要写实照片、3D 渲染、赛博或扁平矢量风。
- **配色**：沿用页面里的 CSS 变量（纸色 `--paper`、墨色 `--ink`、苔绿 `--moss`、屋顶红 `--roof` 等），不要引入冲突的新主色。
- **质感**：纸张颗粒、拍立得式卡片加胶带、轻微倾斜、藤蔓分隔线、树叶光斑和飘叶，都是这个风格的一部分。
- **动效**：轻柔、慢、像风吹过；不要炫技、闪烁或机械感的效果。
- **文案**：温柔、有画面感的中文短句（如“风吹过的地方，藏着16个小世界”）。

拿不准一个改动是否合适时，就问自己：它放进一部吉卜力电影的夏日午后里会不会突兀。

## 相关地址

| 用途 | 地址 | AI 权限 |
| --- | --- | --- |
| 案例源仓库 Demo（克隆下来读取） | <https://github.com/minghong-chen/Demo>（克隆：`https://github.com/minghong-chen/Demo.git`） | **只读** |
| 本网站仓库 Demo-Pages | <https://github.com/minghong-chen/Demo-Pages> | 可修改 |
| 线上网站 | <https://minghong-chen.github.io/Demo-Pages/> | — |

## 最重要的一条：源仓库只读

所有案例都来自维护者自己的 **Demo 仓库**：<https://github.com/minghong-chen/Demo>

- 这个仓库**只由维护者本人维护，AI 一律不许改动**：不提交、不推送、不开分支、不开 PR/Issue、不改设置，只能克隆下来读取。
- 维护者新增、删除或修改案例时，只会改 Demo 仓库，然后让 AI **根据 Demo 仓库更新本网站**。
- 本仓库（Demo-Pages）才是 AI 可以修改的地方。

## 源仓库 → 网站 的对应关系

Demo 仓库里**一个文件夹 = 一个模型 = 网站上的一章**，文件夹里**一个 `.html` = 一个案例**，文件名格式为 `English Name · 中文名.html`。

| Demo 仓库文件 | 网站路径 | 缩略图 | 章节 |
| --- | --- | --- | --- |
| `Claude Fable 5.2/Crimson Loong · 赤龍.html` | `docs/demos/crimson-loong/index.html` | `t-loong.webp` | 第一章 |
| `Claude Fable 5.2/Painted Valley · 彩绘山谷.html` | `docs/demos/painted-valley/index.html` | `t-valley.webp` | 第一章 |
| `Claude Fable 5.2/Pelican Riding a Bicycle · 鹈鹕的漫漫归途.html` | `docs/demos/pelican-riding-a-bicycle/index.html` | `t-pelican.webp` | 第一章 |
| `Claude Fable 5.2/Saltline · 盐线：雨港迷航.html` | `docs/demos/saltline/index.html` | `t-saltline.webp` | 第一章 |
| `Claude Fable 5.2/Abyssal Garden · 深海花园.html` | `docs/demos/abyssal-garden/index.html` | `t-abyssal.webp` | 第一章 |
| `Claude Fable 5.2/Feather · 羽毛.html` | `docs/demos/feather/index.html`（旁边保留 `LICENSE.txt`，MIT） | `t-feather.webp` | 第一章 |
| `Claude Fable 5.2/Walking Block · 步行大楼.html` | `docs/demos/walking-block/index.html` | `t-walking.webp` | 第一章 |
| `Claude Fable 5.2/Lumen Isles · 萤光群岛.html` | `docs/demos/lumen-isles/index.html` | `t-lumen.webp` | 第一章 |
| `Claude Fable 5.2/Butterfly · 蝴蝶.html` | `docs/demos/butterfly/index.html` | `t-butterfly.webp` | 第一章 |
| `Claude Opus 5.5/Pelican Pedal Tales · 鹈鹕骑遇记.html` | `docs/demos/pelican-pedal-tales/index.html` | `t-pedal.webp` | 第二章 |
| `Claude Opus 5.5/Summer Cycle · 夏日骑行.html` | `docs/demos/summer-cycle/index.html` | `t-summer.webp` | 第二章 |
| `Deepseek-V4.1-Flash-1017/Wind Bell Bay · 风铃湾.html` | `docs/demos/wind-bell-bay/index.html` | `t-windbell.webp` | 第三章（Deepseek V4.1 Flash） |
| `Claude Opus 5.6/The Tea Ride · 茶旅.html` | `docs/demos/the-tea-ride/index.html` | `t-tearide.webp` | 第四章 |
| `佚名/Earth Migration · 流浪地球.html` | `docs/demos/earth-migration/index.html` | `t-earth.webp` | 第五章（佚名之作） |
| `佚名/Phoenix Flame · 凤凰.html` | `docs/demos/phoenix-flame/index.html` | `t-phoenix.webp` | 第五章（佚名之作）；作者要求不写致谢 |
| `佚名/Tension · 蛛网.html` | `docs/demos/tension/index.html` | `t-tension.webp` | 第五章（佚名之作） |

- 网站上的案例文件与 Demo 仓库**逐字节相同**，只是改名放进各自文件夹。**不要修改案例本身的代码**。
- 作者不详（不知是哪个 AI 还是人做的）的案例统一放最后一章「佚名之作」，副标题“不知哪阵风吹来的”，导航叫“佚名”；首页“由不同 AI 写出”的说法不要改。Demo 仓库里对应文件夹叫 `佚名`。
- slug 取英文名转小写、空格换 `-`（如 `Wind Bell Bay` → `wind-bell-bay`）。

## 同步流程（维护者说“根据 Demo 仓库更新网站”时）

1. 只读克隆：`git clone --depth 1 https://github.com/minghong-chen/Demo.git /tmp/Demo`
2. 对照上表找出**新增 / 删除 / 内容变化**的案例（变化用 `cmp` 比较）。
3. **新增案例**
   - 复制为 `docs/demos/<slug>/index.html`，不做任何改动。
   - 画一张 4:3 缩略图：**不是截图**，而是用 AI 生图画一张**吉卜力风格的手绘水彩插画**，内容画这个案例里的主角和场景（先打开案例看清楚再画）。风格要和现有缩略图、首图一致：柔和水彩、暖光、夏日感，画面里不要文字和 UI。导出 900×672，存为 `docs/assets/t-<短名>.webp`（质量约 80），`alt` 写画面内容。
   - 在 `docs/index.html` 对应章节的 `.grid` 里加一张卡片，照抄已有卡片结构：`<a class="card reveal" style="--r:±1deg" href="demos/<slug>/">`，`.tag` 写 slug，`h4` 写“中文名<small>English Name</small>”，`p` 写一句介绍（打开案例看过再写，不要编）。`--r` 的倾斜角正负交替。
   - 来自**新文件夹**（新模型）时：新建一章 `<section class="chapter" id="chN">`，章节标题用模型名，副标题写“N 个……”的小短语；导航栏 `.nav` 加对应链接。
4. **删除案例**：删掉对应 demos 文件夹、缩略图和卡片；章节空了就整章和导航链接一起删。
5. **内容变化**：重新复制覆盖即可；主角或场景变了时，按上面的风格重画缩略图。
6. **更新所有数量**：
   - 首屏标题 `藏着16个小世界` 里的数字（维护者要求用阿拉伯数字，2026-11-16）；
   - `data-count` 统计（案例数、模型数）；
   - 每章副标题（如“6个故事”，数字用阿拉伯数字）；
   - `README.md` 顶部标语、章节表格；
   - 本文件的对应关系表。
7. 本地预览：`cd docs && python3 -m http.server 8000`，桌面和手机宽度都看一遍。
8. 提交并推送 `main`，提交信息写清楚加了 / 删了哪些案例。

## 不要动的东西（维护者已经定下的）

- **首屏**：白天用高清静态图 `docs/assets/hero.webp`，黑夜用同构图的夜景 `docs/assets/hero-night.webp`（导航栏按钮切换，夜里首屏自动放烟火、花瓣变萤火虫；点击放烟火在白天试过被否决）。WebGL 扭曲“动起来”和 AI 图生视频动态壁纸都试过，被否决（太假 / 太糊）。
- **页脚**：只写“Demo Gallery · 由 GitHub Pages 托管”，不放署名；致谢统一写在 `README.md`。
- **舞狮大肥鱼（第三章彩蛋）**：素材来自 [PC2005-cloud/dsh-pet](https://github.com/PC2005-cloud/dsh-pet)（MIT），必须保留 `docs/assets/dafeiyu-wushi.LICENSE.txt` 和 README 致谢。桌面用透明 webm，手机 / 微信用动图 webp（微信不支持透明 webm）。**不要懒加载、不要再压缩**。头顶有“点我 ✨”提示，点过后用 localStorage 记住不再显示。
- **点击音效**：`docs/assets/ciallo.mp3`，柚子社《千恋万花》芳乃的“Ciallo～”原声，已剪成只剩一声（约 0.9 秒）。不要换成合成音，大肥鱼不要再加别的音效。
- **烟火音效**：夜间烟火有 Web Audio 实时合成的音效（升空嘶声、闷响、余烬噼啪），访客第一次点击/按键后才出声，切走标签页时静音。
- **背景音乐「听听风」**：Web Audio 实时合成的原创钢琴曲，不要换成有版权的音乐。
- **已否决的效果**：紫色樱花瓣、云影。保留树叶光斑和偶尔飘落的绿叶。
- 改动较大（视觉、交互、新增效果）时，先给维护者看预览，确认后再推送。

## 其他约定

- 纯静态页面，无构建步骤；`docs/.nojekyll` 不要删。
- 维护者用中文交流，文案也用中文。
- 静态资源改了内容但文件名不变时，在引用处加 `?v=N` 防缓存。
