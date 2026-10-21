# EPlayerX 彩色资源徽章

> 为 EPlayerX 制作的轻量级资源信息徽章配置：彩色描边 SVG、动态范围推荐提示、分辨率、视频格式、音频格式、片源和声道信息。

[![配置文件](https://img.shields.io/badge/配置-JSON-3273dc)](https://raw.githubusercontent.com/MiaoWaa/EPlayerX-Badges/main/badges-recommend-regex-v2.json) ![徽章数量](https://img.shields.io/badge/徽章规则-24-26a269) ![状态](https://img.shields.io/badge/版本-正式版-27ae60)

## 效果预览

以下使用**正式版实际 SVG 素材**组合展示，不是另外制作的概念效果图。实际显示数量、顺序和匹配结果以 EPlayerX 获取的资源信息及页面布局为准。

| 场景示例 | 徽章展示 |
| :--- | :--- |
| 推荐 · DV / HDR10+ | <img src="icons/range-recommend.svg" alt="range-recommend" height="24" /> <img src="icons/v4-4k.svg" alt="v4-4k" height="24" /> <img src="icons/v4-dv.svg" alt="v4-dv" height="24" /> <img src="icons/v4-atmos.svg" alt="v4-atmos" height="24" /> <img src="icons/v4-remux.svg" alt="v4-remux" height="24" /> <img src="icons/v5-7-1.svg" alt="v5-7-1" height="24" /> |
| 良好 · HDR / HDR10 | <img src="icons/range-good.svg" alt="range-good" height="24" /> <img src="icons/v4-4k.svg" alt="v4-4k" height="24" /> <img src="icons/v4-hdr10.svg" alt="v4-hdr10" height="24" /> <img src="icons/v4-dts-x.svg" alt="v4-dts-x" height="24" /> <img src="icons/v5-7-1.svg" alt="v5-7-1" height="24" /> |
| 普通 · SDR | <img src="icons/range-standard.svg" alt="range-standard" height="24" /> <img src="icons/v4-1080p.svg" alt="v4-1080p" height="24" /> <img src="icons/v5-aac.svg" alt="v5-aac" height="24" /> <img src="icons/v5-5-1.svg" alt="v5-5-1" height="24" /> |

### 全部徽章

| 类别 | 预览 |
| --- | --- |
| 推荐提示 | <img src="icons/range-recommend.svg" alt="range-recommend" height="24" /> <img src="icons/range-good.svg" alt="range-good" height="24" /> <img src="icons/range-standard.svg" alt="range-standard" height="24" /> |
| 分辨率 | <img src="icons/v4-4k.svg" alt="v4-4k" height="24" /> <img src="icons/v4-1080p.svg" alt="v4-1080p" height="24" /> <img src="icons/v4-720p.svg" alt="v4-720p" height="24" /> |
| 动态范围 | <img src="icons/v4-dv.svg" alt="v4-dv" height="24" /> <img src="icons/v4-hdr10plus.svg" alt="v4-hdr10plus" height="24" /> <img src="icons/v4-hdr10.svg" alt="v4-hdr10" height="24" /> <img src="icons/v4-hdr.svg" alt="v4-hdr" height="24" /> |
| 音频格式 | <img src="icons/v4-atmos.svg" alt="v4-atmos" height="24" /> <img src="icons/v4-dts-x.svg" alt="v4-dts-x" height="24" /> <img src="icons/v4-dts.svg" alt="v4-dts" height="24" /> <img src="icons/v5-truehd.svg" alt="v5-truehd" height="24" /> <img src="icons/v5-ddp.svg" alt="v5-ddp" height="24" /> <img src="icons/v5-ac3.svg" alt="v5-ac3" height="24" /> <img src="icons/v5-dtshdma.svg" alt="v5-dtshdma" height="24" /> <img src="icons/v5-dtshd.svg" alt="v5-dtshd" height="24" /> <img src="icons/v5-aac.svg" alt="v5-aac" height="24" /> <img src="icons/v5-flac.svg" alt="v5-flac" height="24" /> |
| 片源 | <img src="icons/v4-webdl.svg" alt="v4-webdl" height="24" /> <img src="icons/v4-remux.svg" alt="v4-remux" height="24" /> |
| 声道 | <img src="icons/v5-5-1.svg" alt="v5-5-1" height="24" /> <img src="icons/v5-7-1.svg" alt="v5-7-1" height="24" /> |

## 一键导入地址

将下面的完整链接复制到 EPlayerX 的**自定义资源徽章 / 徽章配置 URL**位置：

```text
https://raw.githubusercontent.com/MiaoWaa/EPlayerX-Badges/main/badges-recommend-regex-v2.json
```

[打开正式版 JSON](https://raw.githubusercontent.com/MiaoWaa/EPlayerX-Badges/main/badges-recommend-regex-v2.json) · [查看配置文件](badges-recommend-regex-v2.json)

### 导入步骤

1. 打开 EPlayerX，进入设置中的**资源徽章**相关页面。
2. 开启资源徽章功能，选择添加或编辑自定义 JSON 配置。
3. 粘贴上面的 Raw JSON 地址，保存并启用。
4. 打开资源详情页，检查徽章是否正确显示。
5. 如同时启用了其他徽章配置，建议先关闭它们，避免重复显示或不易比较。

> 不同 EPlayerX 版本的设置名称可能略有差异；配置文件需能通过网络访问 GitHub Raw 地址。

## 推荐等级说明

推荐提示**仅依据资源名称或可匹配文本中的动态范围标记**，不是对视频码率、压制质量、片源真实性或实际画质的综合评分。

| 等级 | 触发条件 | 说明 |
| --- | --- | --- |
| <img src="icons/range-recommend.svg" alt="range-recommend" height="24" /> | DV / DoVi / Dolby Vision 或 HDR10+ | 标记为「推荐」 |
| <img src="icons/range-good.svg" alt="range-good" height="24" /> | HDR10 / HDR，且未命中更高等级 | 标记为「良好」 |
| <img src="icons/range-standard.svg" alt="range-standard" height="24" /> | 明确标注 SDR，且未命中 HDR / DV | 标记为「普通」 |
| 不显示等级 | 未识别动态范围信息 | 不推测、不补造等级 |

同一资源还可能显示 4K、Atmos、REMUX、7.1 等独立徽章。配置对部分动态范围标签设置了互斥匹配，以减少重复标注。

## 支持的 24 种徽章

- **推荐提示（3）**：推荐、良好、普通。
- **分辨率（3）**：4K、1080P、720P。
- **动态范围（4）**：DV、HDR10+、HDR10、HDR。
- **音频格式（10）**：Atmos、DTS:X、DTS、TrueHD、DD+、AC3、DTS-HD MA、DTS-HD、AAC、FLAC。
- **片源（2）**：WEB-DL、REMUX。
- **声道（2）**：5.1、7.1。

为保持显示紧凑，本正式版**不包含 H.264 / HEVC 等视频编码徽章**。

## 常见问题

**为什么没有显示某个徽章？** 规则只能匹配 EPlayerX 提供给配置的文本字段。若资源信息没有对应关键字，或字段格式不同，就可能无法命中。

**为什么预览和实际详情页数量不同？** 两处可能使用不同的示例或资源字段，也可能受到屏幕宽度、徽章排列方式等因素影响。不要将某一条资源显示的数量视为固定上限。

**为什么没有「推荐」等级？** 未标注 DV、HDR10+、HDR 或 SDR 的资源不会强行分级。

**颜色或图标无法加载怎么办？** 请确认能访问 `raw.githubusercontent.com`，并检查自定义 JSON 配置是否启用。SVG 素材与 JSON 都托管在本仓库。

**为什么只保留这一份配置？** 当前 `main` 分支只维护已选定的正式版，减少实验文件和无用素材带来的混淆。

## 仓库结构

```text
.
├── README.md
├── badges-recommend-regex-v2.json   # 正式版配置（24 条规则）
└── icons/                          # 正式版引用的 24 个 SVG
```

## 说明

- 本项目为个人制作的 EPlayerX 自定义徽章配置，**非 EPlayerX 官方项目**。
- 图标仅用于资源信息提示，不保证媒体格式检测的绝对准确性。
- 若更新配置，建议保留原 Raw 链接以便已有用户继续使用。
