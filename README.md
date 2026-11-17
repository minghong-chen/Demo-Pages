<div align="center">

<img src="docs/assets/hero.webp" alt="风吹过的地方，藏着15个小世界" width="100%">

# 小&陈的 Demo 收藏夹 · 夏日画廊

**风吹过的地方，藏着15个小世界。**

一间收藏交互式 Web Demo 的小屋。每一张卡片都是一个单文件页面，点开就能在浏览器里走进去。

[**🌿 在线访问**](https://minghong-chen.github.io/Demo-Pages/) · [查看源码](docs/)

</div>

---

## 15个小世界

由不同 AI 写出的作品，按模型分成三章；作者不详的放在第四章。

### 第一章 · Claude Fable 5.2 · 9个故事

| Demo | 简介 |
| --- | --- |
| [赤龍 Crimson Loong](https://minghong-chen.github.io/Demo-Pages/demos/crimson-loong/) | 暗夜中的巨龙缓缓苏醒，点击屏幕唤醒它。网格、贴图与音符都由代码生成。 |
| [彩绘山谷 Painted Valley](https://minghong-chen.github.io/Demo-Pages/demos/painted-valley/) | 手绘质感的山谷漫游。WASD 行走，Shift 奔跑，V 切换第一人称，T 调整时刻。 |
| [鹈鹕的漫漫归途 Pelican Riding a Bicycle](https://minghong-chen.github.io/Demo-Pages/demos/pelican-riding-a-bicycle/) | 一只鹈鹕骑着自行车踏上旅途，像一部实时渲染的小短片。 |
| [盐线：雨港迷航 Saltline](https://minghong-chen.github.io/Demo-Pages/demos/saltline/) | 雨夜港口，终端逐行亮起，一段在盐雾与灯光中展开的互动叙事。 |
| [深海花园 Abyssal Garden](https://minghong-chen.github.io/Demo-Pages/demos/abyssal-garden/) | 在浏览器里潜进梦一样的海底：摇曳的海藻林、穿水而下的光柱、沉船与蝠鲼，全由 WebGPU 代码生成。 |
| [羽毛 Feather](https://minghong-chen.github.io/Demo-Pages/demos/feather/) | 一只紫喉宝石蜂鸟停在青苔小枝上，上万片羽毛根根可见；会眨眼、抖羽、转头盯你，点一下撒颗种子它会去啄。 |
| [步行大楼 Walking Block](https://minghong-chen.github.io/Demo-Pages/demos/walking-block/) | 一座长着八条机械腿的苏联板楼，在蓝色暮色的湿地旷野上缓缓行走；几何、纹理与着色器全由 three.js 程序化生成。 |
| [萤光群岛 Lumen Isles](https://minghong-chen.github.io/Demo-Pages/demos/lumen-isles/) | 月夜里的一场飞行：群岛上长满会发光的蘑菇、棕榈和蕨，湖水、瀑布和藤蔓都泛着微光。 |
| [隐藏层 Hidden Layers](https://minghong-chen.github.io/Demo-Pages/demos/hidden-layers/) | 一只飞不出温室的玻璃翼蝶，和它底下的六层。 |

### 第二章 · Claude Opus 5.5 · 2段骑行

| Demo | 简介 |
| --- | --- |
| [鹈鹕骑遇记 Pelican Pedal Tales](https://minghong-chen.github.io/Demo-Pages/demos/pelican-pedal-tales/) | 戴头盔、围红围巾的白鹈鹕沿海岸追鱼：IK 骨骼、布料围巾、Gerstner 海浪与昼夜循环。 |
| [夏日骑行 Summer Cycle](https://minghong-chen.github.io/Demo-Pages/demos/summer-cycle/) | 夏日午后的公路骑行，风景像纸卷一样在眼前缓缓展开。 |

### 第三章 · Deepseek V4.1 Flash · 1座云上小镇

| Demo | 简介 |
| --- | --- |
| [风铃湾 Wind Bell Bay](https://minghong-chen.github.io/Demo-Pages/demos/wind-bell-bay/) | 一座漂在云端的 3D 箱庭小镇：昼夜流转，火车环岛，风车与飞鸟。 |

> 💡 第三章里藏着一个小彩蛋，记得去点一点。

### 第四章 · 佚名之作 · 不知哪阵风吹来的

| Demo | 简介 |
| --- | --- |
| [流浪地球 Earth Migration](https://minghong-chen.github.io/Demo-Pages/demos/earth-migration/) | 万台行星发动机点火，镜头从地表一路飞出太阳系，直到整条银河。可看 2 分半的电影自动播放，也能自由漫游。 |
| [凤凰 Phoenix Flame](https://minghong-chen.github.io/Demo-Pages/demos/phoenix-flame/) | 一只火焰凤凰在天空里振翅飞行，可追随或环绕观看，天色在黎明、白昼、黄昏和夜晚间切换；连点它三下试试。 |
| [蛛网 Tension](https://minghong-chen.github.io/Demo-Pages/demos/tension/) | 两根细枝间挂着一张缀满露珠的圆网，有四种天气可切换；拉一根丝再松手，蜘蛛会循着丝跑过来，拉太狠丝会断。 |

## 首页的小细节

- 🎨 **吉卜力水彩首图**：AI 生成后超分辨率放大，配合滚动与鼠标视差。
- 🎹 **背景音乐「听听风」**：一首原创钢琴小曲，用 Web Audio 实时合成，没有任何音频文件，右下角可以开关。
- 🍃 **光影与落叶**：卡片上有树叶漏下的光斑，页面里飘着几片叶子。
- 📱 **手机友好**：手机和微信内置浏览器也能完整浏览；系统开启“减少动态效果”时会自动收起动画。

## 本地运行

纯静态页面，无需构建：

```bash
git clone https://github.com/minghong-chen/Demo-Pages.git
cd Demo-Pages/docs
python3 -m http.server 8000
# 打开 http://localhost:8000
```

## 目录结构

```
docs/
├── index.html      # 画廊首页（GitHub Pages 从 docs/ 发布）
├── assets/         # 首图、缩略图、动画与音效
└── demos/          # 15个 Demo，每个一个文件夹
```

## 致谢

- 舞狮大肥鱼动画来自 [PC2005-cloud/dsh-pet](https://github.com/PC2005-cloud/dsh-pet)，MIT 许可，许可文本见 [`docs/assets/dafeiyu-wushi.LICENSE.txt`](docs/assets/dafeiyu-wushi.LICENSE.txt)。
- 第一章「羽毛 Feather」来自 Theo Tillberg 的 [ttillberg/codevember-2026](https://github.com/ttillberg/codevember-2026)（Codevember 2026 第 12 天，作者注明由 Claude Fable 5.2 与 Opus 5.5 协作完成），MIT 许可，许可文本见 [`docs/demos/feather/LICENSE.txt`](docs/demos/feather/LICENSE.txt)。
- 彩蛋音效来自柚子社《千恋万花》中芳乃的“Ciallo～”，版权归原作者所有。

## 免责声明

- 本仓库仅作为个人技术学习、研究与欣赏，不用于任何商业用途。
- 站内收录的所有 Demo（`docs/demos/` 下的 HTML 文件）均来源于**网络**，**版权均属于原作者**；本站只做收集与展示，未对其内容做修改。
- 首页引用的第三方素材（舞狮大肥鱼动画、“Ciallo～”音效等）版权同样归原作者所有，出处见上方致谢。
- 如果原作者认为本仓库侵犯了您的权益，请通过 GitHub Issue 联系我，我会立刻删除相关文件。
