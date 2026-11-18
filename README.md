# my-ttml-lyrics

> 个人制作与整理的 AMLL 逐字歌词仓库，统一采用 TTML 格式。

## 简介

本仓库用于存放本人制作、校对或收集的逐字歌词文件。歌词采用 **TTML**（Timed Text Markup Language）格式，兼容 AMLL（Apple Music Like Lyrics）生态，以及支持 Apple Music 风格逐字歌词显示的播放器。

## 歌词格式

- **扩展名**：`.ttml`
- **标准**：基于 W3C TTML 的 XML 时序文本，UTF-8 编码
- **时间码**：SMIL 时钟值，格式为 `HH:MM:SS.mmm`
- **支持能力**：
  - 逐字 / 逐词时间轴
  - 翻译与音译
  - 背景人声（`x-bg`）
  - 对唱 / 多人演唱者信息（`ttm:agent`）
  - 歌曲分段（`itunes:song-part`）
  - 注音（Ruby）标注

## 文件命名

约定格式：`创作者_歌手 - 歌名.ttml`（feat. 等信息可写入歌手字段）。

示例：

```
東京真中_初音未来 (初音ミク) - メモリ.ttml
```

## 收录列表

| 文件名 | 创作者 | 歌手 | 歌名 | 备注 |
| --- | --- | --- | --- | --- |
| 東京真中_初音未来 (初音ミク) - メモリ.ttml | 東京真中 | 初音未来（初音ミク） | メモリ | 39ch Originals，2026-11-11 发布 |

> 后续新增歌词按上表格式补充即可。

## 使用方法

1. 在仓库文件列表（或 Releases）中下载对应的 `.ttml` 文件；
2. 在支持 TTML 的播放器（如 AMLL Player）中，将歌词文件与同名音频一同加载；
3. 播放时即可显示逐字高亮，以及翻译 / 音译、背景人声等效果。

## 制作与编辑工具

| 工具 | 说明 | 地址 |
| --- | --- | --- |
| AMLL TTML Tool | 基于 React 的稳定版逐字歌词编辑器，支持内容编辑与打轴 | https://tool.amll.dev/ |
| AMLL Editor | 基于 Vue 的下一代编辑器，支持查找替换等功能 | https://editor.amll.dev/ |
| TTML 格式文档 | AMLL 官方 TTML 格式规范说明 | https://amll.dev/guides/lyric/ttml.html |
| AMLL 生态介绍 | 歌词库、编辑器、播放器等生态概览 | https://amll.dev/guides/overview/eco.html |

## 目录结构

```
my-ttml-lyrics/
├── README.md
└── <创作者>_<歌手> - <歌名>.ttml
```

## 版权与免责声明

- 歌词文本及相关音乐的版权归原词曲作者、创作者及发行方所有；
- 本仓库文件仅供个人学习、研究与打轴练习使用，请勿用于商业用途；
- 如内容涉及侵权，请联系删除相关文件。

## 许可证

歌词内容不适用开源协议；本仓库中的说明文档可按需参考。

> （注：部分内容由豆包 AI 生成）