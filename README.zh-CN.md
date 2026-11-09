# Awesome IINA

[IINA](https://github.com/iina/iina) 插件、浏览器扩展、工具与资源的精选列表。

🌐 在线网页版：<https://cxwx.github.io/awesome-iina/>

[English](README.md) | 简体中文

> **说明**：中文翻译为手动维护、暂无自动化同步，更新可能滞后于[英文原版](README.md)，如有出入请以英文版为准。欢迎提 PR 帮助同步翻译 🙏

> 条目中的 `⭐` 星数与 `🗓` 最近推送时间每周自动更新；💤 表示超过一年未更新，🗄️ 表示仓库已归档。

[IINA](https://iina.io) 是 macOS 上的现代视频播放器：基于 [mpv](https://mpv.io)，使用 Swift 编写，拥有原生 macOS 设计、画中画，以及一套 JavaScript 插件系统。

## 目录

- [官方资源](#官方资源)
- [安装](#安装)
- [插件](#插件)
  - [官方插件](#官方插件)
  - [媒体服务器与在线播放](#媒体服务器与在线播放)
  - [字幕](#字幕)
  - [播放与控制](#播放与控制)
  - [视频与音频处理](#视频与音频处理)
  - [播放列表与媒体库](#播放列表与媒体库)
  - [弹幕](#弹幕)
  - [语言学习](#语言学习)
  - [观看记录同步](#观看记录同步)
- [浏览器扩展](#浏览器扩展)
- [启动器集成](#启动器集成)
- [工具与脚本](#工具与脚本)
- [Fork 版本](#fork-版本)
- [插件开发](#插件开发)
- [社区与资源](#社区与资源)
- [参与贡献](#参与贡献)

## 官方资源

- [iina.io](https://iina.io) — 官方网站。
- [iina/iina](https://github.com/iina/iina) — IINA 源代码。 `⭐ 47062 · 🗓 2026-11`
- [Plugin Center](https://iina.io/plugins/) — 官方插件目录，可在 IINA 的插件管理器中直接安装。
- [docs.iina.io](https://docs.iina.io/) — 官方插件 API 文档。
- [GitHub Discussions](https://github.com/iina/iina/discussions) — 问答、功能讨论与版本反馈。
- [GitHub Releases](https://github.com/iina/iina/releases) — 官方更新日志。
- [iina-cli](https://github.com/iina/iina/tree/master/iina-cli) — 内置命令行工具：从终端打开媒体、附加到运行中的实例、透传 mpv 选项。
- [Crowdin](https://crowdin.com/project/iina) — 参与 IINA 翻译。

## 安装

- 从[官网](https://iina.io/download/)或 [GitHub Releases](https://github.com/iina/iina/releases) 下载最新版本。
- 通过 Homebrew 安装：

```bash
brew install --cask iina
```

## 插件

插件使用 JavaScript 编写，打包为 `.iinaplgz`，在 IINA 的 设置 → 插件 中安装（可从 Plugin Center 安装，也可通过"从 GitHub 安装"输入 `owner/repo`）。

### 官方插件

- [iina/plugin-opensub](https://github.com/iina/plugin-opensub) — 在 opensubtitles.com 搜索并下载字幕。 `⭐ 21 · 🗓 2026-04`
- [iina/plugin-more-seeking](https://github.com/iina/plugin-more-seeking) — 增加更多快进快退选项。 `⭐ 14 · 🗓 2025-05` 💤
- [iina/plugin-online-media](https://github.com/iina/plugin-online-media) — 通过 yt-dlp 播放在线视频，支持实时切换分辨率。 `⭐ 48 · 🗓 2026-08`
- [iina/plugin-userscript](https://github.com/iina/plugin-userscript) — 在 IINA 中加载 userscript。 `⭐ 61 · 🗓 2026-04`

### 媒体服务器与在线播放

- [ada-bee/jellyfin-iina](https://github.com/ada-bee/jellyfin-iina) — 浏览并观看 Jellyfin 服务器上的内容。 `⭐ 31 · 🗓 2026-10`
- [ada-bee/youtube-iina](https://github.com/ada-bee/youtube-iina) — 在侧边栏浏览并观看 YouTube 视频。 `⭐ 10 · 🗓 2026-02`
- [Arnav12S/iina-contentplay](https://github.com/Arnav12S/iina-contentplay) — 搜索电影/剧集，通过 Stremio 解析 Real-Debrid 链接，整季作为播放列表播放。 `⭐ 5 · 🗓 2026-11`
- [DTTerastar/iina-plugin-channels](https://github.com/DTTerastar/iina-plugin-channels) — IPTV 频道浏览器：M3U 播放列表，支持搜索、分组和 XMLTV 节目单。 `⭐ 6 · 🗓 2026-11`
- [mhajder/iina-jellyfin](https://github.com/mhajder/iina-jellyfin) — Jellyfin 媒体浏览器侧边栏，支持自动下载字幕。 `⭐ 90 · 🗓 2026-11`
- [ozykhan/iina-airplay](https://github.com/ozykhan/iina-airplay) — 通过 AirPlay 将当前视频投到 Apple TV，IINA 变身遥控器。 `⭐ 40 · 🗓 2026-11`
- [qydxyx/iina-webdav](https://github.com/qydxyx/iina-webdav) — 连接 WebDAV 服务器，浏览媒体并将文件或文件夹加入播放列表。 `⭐ 0 · 🗓 2026-10`

### 字幕

- [bbeny123/iina-save-subs-with-delay](https://github.com/bbeny123/iina-save-subs-with-delay) — 保存字幕时把当前延迟一并写入。 `⭐ 2 · 🗓 2026-02`
- [Robpol86/iina-file-name-search](https://github.com/Robpol86/iina-file-name-search) — 在可配置的网站上搜索当前播放的文件名。 `⭐ 2 · 🗓 2025-09` 💤
- [isparkyou-github/iina-realtime-speech-translator](https://github.com/isparkyou-github/iina-realtime-speech-translator) — 实时语音转写与翻译。 `⭐ 5 · 🗓 2026-06`
- [janwee-sha/SubTandem](https://github.com/janwee-sha/SubTandem) — 实时 AI 双语字幕翻译。 `⭐ 5 · 🗓 2026-10`
- [wilbeibi/iina-plugin-assrt](https://github.com/wilbeibi/iina-plugin-assrt) — 从 assrt.net（伪射手）搜索并自动下载中文字幕，支持 alass 时间轴校正。 `⭐ 0 · 🗓 2026-07`
- [yuxiqian/whisperina](https://github.com/yuxiqian/whisperina) — 使用 OpenAI Whisper 模型在本地生成字幕。 `⭐ 14 · 🗓 2025-06` 💤

### 播放与控制

- [alexkuang0/iina-key-binding-youtube](https://github.com/alexkuang0/iina-key-binding-youtube) — 仿 YouTube 的键盘快捷键方案。 `⭐ 11 · 🗓 2023-08` 💤
- [aminozuur/iina-thumbnails](https://github.com/aminozuur/iina-thumbnails) — 为每个视频显示可点击的缩略图。 `⭐ 4 · 🗓 2026-10`
- [bbeny123/iina-jump-to-frame](https://github.com/bbeny123/iina-jump-to-frame) — 按帧号精确跳转。 `⭐ 15 · 🗓 2026-02`
- [D0CA/iina-cinemode](https://github.com/D0CA/iina-cinemode) — 全屏暂停遮罩、跳过片头，以及可选的 Stremio 下一集快捷键。 `⭐ 4 · 🗓 2026-10`
- [glechic/iina-bilingual-audio](https://github.com/glechic/iina-bilingual-audio) — 左右声道分离播放两条音轨，双语观看。 `⭐ 2 · 🗓 2026-07`
- [leo-mathurin/iina-nightshift-fs](https://github.com/leo-mathurin/iina-nightshift-fs) — 全屏播放时自动关闭 macOS 的 Night Shift。 `⭐ 2 · 🗓 2026-05`
- [nastarandarjani/iina-pip-toggle](https://github.com/nastarandarjani/iina-pip-toggle) — 在画中画与全屏之间切换。 `⭐ 9 · 🗓 2026-04`
- [pangziqiang/iina-auto-skip](https://github.com/pangziqiang/iina-auto-skip) — 通过拖拽标记自动跳过片头片尾。 `⭐ 4 · 🗓 2026-10`
- [pparanoiidd/iina-skip-intro](https://github.com/pparanoiidd/iina-skip-intro) — 检测并跳过片头、回顾和 Staff 片尾。 `⭐ 21 · 🗓 2026-10`
- [Tommy12356F/iina-hold-to-speed](https://github.com/Tommy12356F/iina-hold-to-speed) — 按住空格以 2 倍速播放，就像 YouTube 一样。 `⭐ 15 · 🗓 2026-10`
- [treehog2/iina-absave-plugin](https://github.com/treehog2/iina-absave-plugin) — 保存 AB 循环。 `⭐ 5 · 🗓 2025-11` 💤
- [Zain-Imam/iina-episode-info](https://github.com/Zain-Imam/iina-episode-info) — 暂停时显示 TMDB 剧集/电影信息，内置字幕搜索。 `⭐ 12 · 🗓 2026-10`

### 视频与音频处理

- [5thDimensionalVader/recorder-iina](https://github.com/5thDimensionalVader/recorder-iina) — 使用 ffmpeg 剪辑视频片段。 `⭐ 13 · 🗓 2026-07`
- [bbeny123/iina-hdr-screenshot](https://github.com/bbeny123/iina-hdr-screenshot) — 使用 ffmpeg 截取 HDR 截图。 `⭐ 5 · 🗓 2026-02`
- [Fhlisherman/iina-video-upscaler](https://github.com/Fhlisherman/iina-video-upscaler) — GPU 加速超分辨率放大。 `⭐ 24 · 🗓 2026-04`
- [Gabe-LS/iina-audio-normalize](https://github.com/Gabe-LS/iina-audio-normalize) — 自动音量标准化（峰值与 EBU R128 响度两种模式）。 `⭐ 5 · 🗓 2026-05`
- [karthisnk/multi-cutter-iina](https://github.com/karthisnk/multi-cutter-iina) — 用 ffmpeg 剪出多段片段，支持批量剪辑、竖屏裁剪、格式选择与预览。 `⭐ 14 · 🗓 2026-01`
- [lenadweb/iina-plugin-keystone](https://github.com/lenadweb/iina-plugin-keystone) — 投影仪垂直/水平梯形校正，可实时调整。 `⭐ 2 · 🗓 2026-09`
- [yorkyang2333/iina-AnimeEnhancer](https://github.com/yorkyang2333/iina-AnimeEnhancer) — 通过侧边栏管理 Anime4K 与 AnimeJaNai 着色器，实时动画超分。 `⭐ 37 · 🗓 2026-10`
- [fetzu/iina-plugin-vr2d](https://github.com/fetzu/iina-plugin-vr2d) — 把 VR 3D 视频（180°/360°、左右/上下、等距圆柱或鱼眼）转为可平移缩放的平面 2D 画面观看。 `⭐ 4 · 🗓 2026-08`

### 播放列表与媒体库

- [CatCodeDanix/iina-playlist-pro](https://github.com/CatCodeDanix/iina-playlist-pro) — 管理本地与在线播放列表。 `⭐ 16 · 🗓 2026-10`
- [dotWee/iina-playlist-sortings](https://github.com/dotWee/iina-playlist-sortings) — 更多播放列表排序方式。 `⭐ 9 · 🗓 2026-08`
- [HowDidTheCatGetSoFat/iina-detached-playlist](https://github.com/HowDidTheCatGetSoFat/iina-detached-playlist) — 把播放列表放进独立的悬浮窗口。 `⭐ 8 · 🗓 2026-07`
- [icsarisakal/iina-playlist-searchbox](https://github.com/icsarisakal/iina-playlist-searchbox) — 按歌名和歌手搜索当前播放列表。 `⭐ 0 · 🗓 2026-08`
- [qktechies/iina-plugin-file-viewer](https://github.com/qktechies/iina-plugin-file-viewer) — 收藏文件夹、浏览目录结构，无需离开 IINA 即可播放文件。 `⭐ 23 · 🗓 2026-02`
- [roboloop/media-manager](https://github.com/roboloop/media-manager) — 在播放器里直接给媒体文件打标签、做整理。 `⭐ 4 · 🗓 2026-04`
- [thepushkarp/iina-metadata](https://github.com/thepushkarp/iina-metadata) — 通过 TMDB/TVmaze 识别电影和剧集，把元数据与封面写入 MKV/MP4（兼容 Kodi/Infuse）。 `⭐ 0 · 🗓 2026-11`
- [wyattowalsh/iina-plugin-bookmarks](https://github.com/wyattowalsh/iina-plugin-bookmarks) — 保存并管理视频书签（时间点）。 `⭐ 20 · 🗓 2026-04`

### 弹幕

- [karappo-yu/iina-plugin-danmaku-cosmos](https://github.com/karappo-yu/iina-plugin-danmaku-cosmos) — Niconico/Bilibili/DanDanPlay 弹幕，CSS 与 Canvas 双渲染，支持 Comment Art 与样式预设。 `⭐ 17 · 🗓 2026-11`
- [xjbeta/iina-plugin-danmaku](https://github.com/xjbeta/iina-plugin-danmaku) — 在画面上叠加弹幕。 `⭐ 24 · 🗓 2026-09`

### 语言学习

- [afn478/iinatan](https://github.com/afn478/iinatan) — 在 IINA 里查词典、挖 Anki 生词卡。 `⭐ 9 · 🗓 2026-10`
- [AkihaZhang/hoshitan](https://github.com/AkihaZhang/hoshitan) — 实验性字幕查词与 Anki 制卡。 `⭐ 4 · 🗓 2026-06`
- [alyssabedard/mpv2anki](https://github.com/alyssabedard/mpv2anki) — 用于 Anki 制卡的 mpv 脚本：自动截取字幕、音频片段和截图。 `⭐ 20 · 🗓 2025-10` 💤
- [kerim/iina-clickable-subtitles](https://github.com/kerim/iina-clickable-subtitles) — 点击字幕中的单词，用 macOS"查询"取词。 `⭐ 16 · 🗓 2025-11`
- [polyscript-app/polyplugin-release](https://github.com/polyscript-app/polyplugin-release) — PolyScript：双字幕、悬停词典与 AI 辅助翻译。 `⭐ 3 · 🗓 2026-10`
- [s4ysolutions/iina-verba](https://github.com/s4ysolutions/iina-verba) — 选中字幕里的单词按 A，加入你的 Verba 生词本。 `⭐ 0 · 🗓 2026-10`

### 观看记录同步

- [ethanndickson/iina-lastfm](https://github.com/ethanndickson/iina-lastfm) — 把 IINA 播放的音乐 scrobble 到 Last.fm 的 mpv 脚本。 `⭐ 48 · 🗓 2025-02` 💤
- [gridness/anilist-sync](https://github.com/gridness/anilist-sync) — 本地动画看到 85% 后自动同步到 AniList。 `⭐ 0 · 🗓 2026-10`
- [i3p9/iina-trakt-scrobbler](https://github.com/i3p9/iina-trakt-scrobbler) — Trakt.tv scrobbler。 `⭐ 5 · 🗓 2026-05`
- [kevllarco/iina-plex-sync](https://github.com/kevllarco/iina-plex-sync) — 把本地播放进度和已看状态同步到 Plex。 `⭐ 1 · 🗓 2026-10`
- [notfire/iina-listenbrainz](https://git.notfire.cc/notfire/iina-listenbrainz) — 把音乐 scrobble 到 ListenBrainz。

## 浏览器扩展

- [Open In IINA（Chrome）](https://chromewebstore.google.com/detail/open-in-iina/pdnojahnhpgmdhjdhgphgdcecehkbhfo) — 用 IINA 打开网页中的视频和音频，替代浏览器内建播放。
- [Open In IINA（Firefox）](https://addons.mozilla.org/firefox/addon/open-in-iina/) — 官方扩展的 Firefox 版本。
- [IINAplex（Chrome）](https://chromewebstore.google.com/detail/iinaplex/epjfaegeibjoigkenalmdagpbmelemik) — 用 IINA 打开 Plex 媒体。
- [n3d1117/plex-to-iina](https://github.com/n3d1117/plex-to-iina) — 用于播放 Plex 内容的 Safari 应用扩展。 `⭐ 42 · 🗓 2022-02` 💤
- Safari："Open in IINA" 内置于 IINA.app — 在 Safari → 设置 → 扩展 中启用。

官方扩展的源码位于主仓库的 [`browser/`](https://github.com/iina/iina/tree/master/browser) 目录。

## 启动器集成

- [eutialia/open-in-iina](https://github.com/eutialia/open-in-iina) — 从 Alfred 或 Raycast 直接用 IINA 打开链接。 `⭐ 19 · 🗓 2020-12` 💤

## 工具与脚本

- [kjtsune/embyToLocalPlayer](https://github.com/kjtsune/embyToLocalPlayer) — 让 Emby/Jellyfin/Plex 调用本地播放器（含 IINA）播放，并回传播放进度。 `⭐ 1460 · 🗓 2026-11`
- [LuckyPuppy514/external-player](https://github.com/LuckyPuppy514/external-player) — 浏览器油猴脚本，把网页视频投递到外部播放器。 `⭐ 382 · 🗓 2025-11`
- [n3d1117/acestream-iina](https://github.com/n3d1117/acestream-iina) — 在 macOS 上用 IINA 播放 Ace Stream。 `⭐ 30 · 🗓 2019-11` 💤
- [fullmetalsheep/mpv-iina-scripts](https://github.com/fullmetalsheep/mpv-iina-scripts) — 为 IINA 制作/魔改的 mpv Lua 脚本合集。 `⭐ 19 · 🗓 2018-10` 💤
- [wpdevelopment11/remote_mpv](https://github.com/wpdevelopment11/remote_mpv) — 通过 HTTP 远程控制 mpv/IINA 播放，手机或其他电脑均可。 `⭐ 5 · 🗓 2026-06`

## Fork 版本

- [xjbeta/iina-plus](https://github.com/xjbeta/iina-plus) — 增强弹幕支持（bilibili 等）的 IINA 分支。 `⭐ 1393 · 🗓 2026-09`

## 插件开发

- [Plugin API 文档](https://docs.iina.io/) — IINA 插件 API 官方文档。
- [iina/iina-plugin-template](https://github.com/iina/iina-plugin-template) — 使用 iina-cli 创建插件的官方模板。 `⭐ 8 · 🗓 2025-07` 💤
- [iina/iina-plugin-definition](https://github.com/iina/iina-plugin-definition) — 插件 API 的 TypeScript 类型定义（npm 包：`iina-plugin-definition`）。 `⭐ 27 · 🗓 2026-11`
- [iina/deps-buildscripts](https://github.com/iina/deps-buildscripts) — 1.5.0 起 IINA 依赖（mpv、ffmpeg 等）的构建脚本。 `⭐ 1 · 🗓 2026-11`
- [iina/homebrew-mpv-iina](https://github.com/iina/homebrew-mpv-iina) — IINA 定制 mpv/ffmpeg 的 Homebrew tap（已停止维护）。 `⭐ 20 · 🗓 2026-09` 🗄
- [plugins.json](https://github.com/iina/iina/blob/develop/plugins.json) — Plugin Center 的索引文件；向 `develop` 分支提 PR 即可收录你的插件。

## 社区与资源

- [IINA（维基百科）](https://en.wikipedia.org/wiki/IINA) — 背景与历史。
- [mpv 手册](https://mpv.io/manual/master/) — IINA 的高级设置暴露了大部分 mpv 选项，mpv 手册是权威参考。
- [yt-dlp](https://github.com/yt-dlp/yt-dlp) — IINA 在线播放及许多插件的底层依赖。 `⭐ 206362 · 🗓 2026-11`

## 参与贡献

欢迎参与！请先阅读[贡献指南](CONTRIBUTING.md)（英文）。

- 新增插件：在对应分区加一行链接该仓库的条目，提 PR 即可。
- 想被 IINA 官方 Plugin Center 收录：向 iina/iina 仓库 `develop` 分支的 [`plugins.json`](https://github.com/iina/iina/blob/develop/plugins.json) 提 PR。
- 中英文 README 请保持同步。

## 许可证

[MIT](LICENSE)
