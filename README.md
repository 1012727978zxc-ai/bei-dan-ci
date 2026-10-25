<div align="center">

<img src="docs/assets/banner.jpg" alt="词光 Word Atlas：一词一画，点亮雅思" width="100%">

# 词光 · Word Atlas

**一词一画，点亮雅思。**<br>
7,298 个雅思核心词 · 每个词一幅原创插画 · 14,596 条原创例句 · 英美发音 · FSRS 间隔复习

[**打开词光 →**](https://0xlei.tech/words/) &nbsp;·&nbsp; [下载词库](data/) &nbsp;·&nbsp; [English](README.en.md)

![MIT](https://img.shields.io/badge/code-MIT-1E2640) ![CC BY 4.0](https://img.shields.io/badge/content-CC%20BY%204.0-C4573A) ![words](https://img.shields.io/badge/words-7%2C298-7F9B77) ![FSRS](https://img.shields.io/badge/scheduler-FSRS%206-D9A03A) ![no login](https://img.shields.io/badge/login-not%20required-6F93AE)

</div>

---

背单词最难的不是“看过”，而是“想得起来”。

词光给每个词一幅画、两句话和一套刚刚好的复习节奏：先看见，再想起，在快要忘记的时候刚好重逢。你学会的每一个词，都会在自己的词汇星图上点亮一颗星。

免费，打开网页就能用。没有账号，没有广告，进度只留在你自己的设备上。

<p align="center"><a href="docs/assets/demo.mp4"><b>▶ 看 30 秒演示</b></a> · <a href="https://0xlei.tech/words/">在线使用</a></p>

<img src="docs/assets/today-desktop.jpg" alt="今日" width="100%">

<img src="docs/assets/mosaic.jpg" alt="7,298 幅插画里的一小部分" width="100%">

## 每个词都有什么

| | |
|---|---|
| 🖼 **一幅插画** | 统一的复古图鉴画风，画面讲的就是第一条例句里的事。抽象词也用具体场景表达。 |
| 🔊 **英美发音** | 英音、美音分别合成，日常例句也配朗读（AI 语音，ElevenLabs）。 |
| ✍️ **两条原创例句** | 一条日常短句帮你记住，一条雅思语境长句（教育、环境、科技、城市……）帮你会用。都配自然的中文翻译。 |
| 📚 **释义与英文释义** | 最多 3 个常用义项，按雅思使用频率排序，附简明英文解释。 |
| 🧩 **搭配、词族、近反义** | 高频搭配带中文，词族之间可以互相跳转。 |
| 💡 **一条提示** | 易混词、用法陷阱或记忆方法，不编造词源。 |
| 🏷 **难度与话题** | CEFR A1–C2 分级，19 个雅思高频话题分类。 |

## 词汇星图

7,298 个词就是 7,298 颗星。19 个雅思话题各成一条旋臂，简单的词在星系中心，难的在外缘。还没学的是星尘，学习中的会发光，掌握了的会燃成白色。每结束一轮学习，你会看着今天学会的词一颗颗亮起来。

拖动旋转，滚动缩放，点击任意一颗星打开它的词卡。星图用 WebGL2 自定义着色器渲染，在不支持的设备上会自动降级。

## 怎么帮你记住

- **主动回忆**：看义选词、看图补句、听音辨词、拼写，四种题型从“认得”走到“会写”。
- **FSRS 间隔复习**：和 Anki 新版同款的开源记忆算法，只在你快要遗忘时安排复习，目标记忆率可调。
- **首次作答才计分**：答错的词会在本轮换个题型再练，但重试不会抬高正确率，统计诚实。
- **从你的水平开始**：选择 A2 / B1 / B2 / C1 起点，跳过已经熟悉的词。
- **打字工作室**：单词、例句抄写、整句听写三种模式，WPM 与准确率独立统计，不污染记忆数据。
- **分享卡片**：任何一个词、每天的学习成果，都能一键生成精美图片。
- **声音设计**：每个操作都有温和的木琴、纸张与铃声音效；一段星空音乐和 6 段可循环的环境声（雨天图书馆、清晨海岸、林间早晨、夜晚壁炉、远航船舱、安静咖啡馆）陪你专注，读单词时会自动压低。
- **开屏仪式**：星尘汇聚成“词光”，点击后大门打开，“欢迎打开雅思大门”。每天一次，可在设置里关闭。
- **离线可用**：看过的词、插画和音频会缓存在本地，没网也能复习。

<table>
<tr>
<td width="62%"><img src="docs/assets/atlas-desktop.jpg" alt="图鉴"></td>
<td><img src="docs/assets/word-mobile.jpg" alt="手机词卡"></td>
</tr>
</table>

## 一份可以自由使用的词库

`data/` 目录里是完整词库，内容采用 **CC BY 4.0**，署名即可自由使用、修改、商用：

- [`data/word-atlas.json`](data/word-atlas.json)：完整结构化数据
- [`data/word-atlas.csv`](data/word-atlas.csv)：表格版，可直接导入 Excel / Anki
- `public/atlas/img/`：7,298 幅 512px WebP 插画（另有 256px 缩略图）
- `public/atlas/audio/`：英音 / 美音单词发音与例句朗读 MP3

```json
{
  "id": "principle",
  "w": "principle",
  "uk": "/ˈprɪnsəpəl/",
  "us": "/ˈprɪnsəpəl/",
  "senses": [{ "pos": "n.", "zh": "原则；行为准则", "en": "A belief or rule that guides decisions and behaviour." }],
  "ex": [
    { "en": "I refused the extra money as a matter of principle.", "zh": "出于原则，我拒绝了那笔额外的钱。" },
    { "en": "The principle of equal opportunity should guide policies designed to improve access to higher education.", "zh": "…" }
  ],
  "col": ["in principle｜原则上", "basic principle｜基本原则"],
  "fam": ["principled (adj.)"],
  "tip": "principle 是原则；principal 是校长、主要的。",
  "cefr": "B2",
  "topic": "thinking"
}
```

字段说明见 [docs/dataset.md](docs/dataset.md)。可以拿它做 Anki 牌组、背词小程序、浏览器插件、AI 应用的评测集，或者你自己的研究。

## 本地运行

需要 Node.js 20+。

```bash
npm ci
npm run dev
```

打开 `http://localhost:5188`。同一 Wi-Fi 下的手机可以访问终端里显示的 Network 地址。

```bash
npm test            # 单元测试
npm run check:atlas # 校验词库结构与媒体文件
npm run build       # 生产构建，输出到 dist/
```

部署就是把 `dist/` 放到任意静态托管。子路径部署用 `ATLAS_BASE=/words/ npm run build`；仓库自带 GitHub Pages 工作流，见 [docs/deployment.md](docs/deployment.md)。

## 内容是怎么做出来的

词表来自常见的雅思阅读核心词（去重后 7,298 个词条）。词条内容全部是本项目新写的：大语言模型按统一的词典编写规范生成释义、例句、搭配和提示；插画由图像模型按统一画风逐词绘制；发音由 ElevenLabs 合成。生成脚本在 [`scripts/atlas/`](scripts/atlas)，流程见 [docs/pipeline.md](docs/pipeline.md)。

**诚实说明**：内容经过了结构、引用和一致性的自动校验，但没有逐条人工审校，可能有个别不准确的释义、例句或插画。发现问题欢迎提 Issue，或者直接修改 `data/` 提 PR，这正是开源的意义。这不是官方雅思词表，也不保证提分。

## 参与贡献

- 纠错：在 Issue 里写清楚词条 id 和问题，或者直接提 PR。
- 新功能：先开 Issue 讨论，保持“无账号、本地优先、安静好看”的方向。
- 代码风格：TypeScript 严格模式，`npm test` 和 `npm run check:atlas` 需要通过。

详见 [CONTRIBUTING.md](CONTRIBUTING.md)。

## 授权

- 代码：[MIT](LICENSE)
- 词库文本、插画、录音：[CC BY 4.0](CONTENT_LICENSE.md)，署名 “Word Atlas contributors”（词光）
- 字体 Fraunces：SIL Open Font License；记忆算法 [ts-fsrs](https://github.com/open-spaced-repetition/ts-fsrs)：MIT

如果词光帮到了你，点一颗 ⭐️，也算帮它点亮一颗星。
