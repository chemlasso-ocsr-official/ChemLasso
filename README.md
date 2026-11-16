# ChemLasso

**Circle-to-Search Chemical Structures & Pricing**

**圈选即搜的化学结构识别与试剂价格查询**

[![Chrome Web Store](https://img.shields.io/badge/Chrome%20Web%20Store-Install-4285F4?logo=googlechrome&logoColor=white)](https://chromewebstore.google.com/detail/chemlasso-%E2%80%94-circle-to-sea/hdfcggkbgdldboapjiphdkihihhbipld)

[English](#english) | [中文](#中文)

<!-- TODO: 在此放一张主截图或演示 GIF，例如 docs/images/demo.gif -->
<!-- ![ChemLasso demo](docs/images/demo.gif) -->

---

## English

### What it does

ChemLasso is an offline tool for recognising chemical structures, with a 2D/3D studio, sample archiving, CAS lookup and reagent pricing.

It recognises 2D chemical diagrams from articles, patents and PDFs using an on-device vision model and a WebAssembly chemistry runtime. No Python, no server and no API key are needed.

### Features

- **Capture** — select a structure with a freehand lasso or a rectangle, or drag an image into the side panel.
- **On-device recognition** — WebGPU acceleration with CPU fallback.
- **2D Structure Studio** — edit or draw molecules, with live property updates.
- **3D viewer** — shows low-energy conformers.
- **Export** — chemistry files and high-resolution graphics.
- **Local sample archive** — recent sessions are stored locally; filter by substructure or formula, and star samples with lab notes.
- **Optional online mode** — when you unlock it and confirm a query, ChemLasso checks PubChem and Wikidata for CAS numbers and supplier links.

### Install

Open the [Chrome Web Store page](https://chromewebstore.google.com/detail/chemlasso-%E2%80%94-circle-to-sea/hdfcggkbgdldboapjiphdkihihhbipld) and click **Add to Chrome**.

<!-- TODO: Edge 加载项商店链接 -->

Available in English, Simplified Chinese and Traditional Chinese.

### Shortcuts

| Action | Windows | macOS |
| --- | --- | --- |
| Start capture | `Alt` + `S` | `Command` + `Shift` + `S` |

### Privacy

- Offline privacy mode is on by default.
- Captured images stay on your device.
- In the default offline mode, no outbound network requests are made during or after recognition.

Privacy policy: <https://sites.google.com/view/chemlasso-privacy>

### Support

- Open an [issue](../../issues) in this repository.
- Email: chemlasso.ocsr.official@gmail.com

---

## 中文

### 它能做什么

ChemLasso 是一款离线的化学结构识别工具，带有 2D/3D 工作室、样品存档、CAS 查询和试剂价格查询。

它使用本地视觉模型和 WebAssembly 化学运行时，识别文章、专利和 PDF 中的 2D 化学结构图。无需 Python、无需服务器、无需 API key。

### 功能

- **截取** —— 用自由套索或矩形框选结构，也可以把图片拖进侧边栏。
- **本地识别** —— WebGPU 加速，并可回退到 CPU。
- **2D 结构工作室** —— 编辑或绘制分子，性质实时更新。
- **3D 查看器** —— 显示低能构象。
- **导出** —— 化学文件和高分辨率图片。
- **本地样品存档** —— 近期记录保存在本地；可按子结构或分子式筛选，可为样品加星标并附实验备注。
- **可选的在线模式** —— 在你解锁并确认查询后，ChemLasso 通过 PubChem 和 Wikidata 查询 CAS 号与供应商链接。

### 安装

打开 [Chrome 应用商店页面](https://chromewebstore.google.com/detail/chemlasso-%E2%80%94-circle-to-sea/hdfcggkbgdldboapjiphdkihihhbipld)，点击 **添加至 Chrome**。

支持英文、简体中文和繁体中文。

### 快捷键

| 操作 | Windows | macOS |
| --- | --- | --- |
| 开始截取 | `Alt` + `S` | `Command` + `Shift` + `S` |

### 隐私

- 默认开启离线隐私模式。
- 截取的图片保留在你的设备上。
- 在默认的离线模式下，识别过程中及识别之后都不会发出网络请求。

隐私政策：<https://sites.google.com/view/chemlasso-privacy>

### 支持

- 在本仓库提交 [issue](../../issues)。
- 邮箱：chemlasso.ocsr.official@gmail.com
