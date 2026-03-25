[English](../readme.md) | [中文](README.zh.md) | [Español](README.es.md) | [Русский](README.ru.md) | [日本語](README.ja.md) | [한국어](README.ko.md)

# Lunar
**系统与网络开发者 | C/C++, Go, Rust, JavaScript/TypeScript, Zig**

专注于构建底层工具、协议绑定以及跨平台应用。在代理基础设施、加密网络以及原生桌面应用开发方面拥有丰富经验。能够根据项目需求，在全栈各层级中灵活切换并高效工作。

- 邮箱: [lunarlifeburst+work@gmail.com](mailto:lunarlifeburst+work@gmail.com)
- Telegram: [@retrolunar](https://t.me/retrolunar)
- GitHub: [https://github.com/lunardoesdev](https://github.com/lunardoesdev)

### 全球远程工作
- 时区: GMT+10
- 语言: 英语，俄语

## 核心技能
- **系统编程:** Go, Rust, C/C++, CMake/Make, 交叉编译, 静态链接, WASM (Emscripten)
- **网络与基础设施:** 代理协议 (VMess/SS/Hysteria), WireGuard, Docker/Podman, CI/CD (GitHub Actions)
- **Web开发:** Node.js, TypeScript, Vite, Tailwind, Tauri
- **数据库:** SQLite (支持 FTS5), MySQL, 缓存策略
- **脚本语言:** Python, Bash, Nim

## 精选项目

**Mintfused** — 基于 Linux Mint 的自定义 Linux 发行版
（由于 GitHub 免费账户的限制，ISO 缺失，但详细描述了创建过程）。
[GitHub](https://github.com/lunardoesdev/mintfused)

**Singerbox** — sing-box 代理引擎的 Go 语言绑定
支持从任何分享链接（VLESS, VMess, Shadowsocks, Hysteria）创建进程内实例。零配置默认设置，干净安全的内存释放。易于嵌入，无需启动子进程。
[GitHub](https://github.com/lunardoesdev/singerbox)

**Radihypn** — 带有托盘图标的 C++/GTK3 网络电台
轻量级的 Linux 原生桌面应用。支持流媒体播放、系统托盘集成，占用极少的系统资源。
[GitHub](https://github.com/radihypn/radihypn)

## 精选出版物

**POSIX C/C++ 构建中环境变量的详细指南**
在 POSIX 系统上构建 C 和 C++ 项目时使用环境变量的实用指南。
[阅读](https://lunardoesdev.github.io/posts/2026-03-10-posix-environment-variables.html)

**不同平台的交叉编译器和工具链**
用于目标化不同平台的交叉编译器和工具链集合。
[阅读](https://lunardoesdev.github.io/posts/2026-03-11-crosscompilers-for-platforms.html)

## 开源贡献
- **i2pd 生态系统:** 维护 i2pd-tools 的持续构建集成，提交了 dinit 服务配置（已合并至上游），以及实现了全自动静态链接的 Rust 绑定。
- **PurpleI2P/i2pd:** 成功合并了 Pull Request [#2338](https://github.com/PurpleI2P/i2pd/pull/2338)。
- **libi2pd:** 为动态链接库打包编写了构建脚本。
- **MSX 交叉编译:** 实现了可重现的 C/ASM ROM 构建。
- **niqlite:** 封装了 SQLite 且支持 FTS5 扩展的 Nim 库。
  [Nimble Directory](https://www.nimble.directory/pkg/niqlite)
- **notetask** (分支): 强制设定所需的日期和时间格式。
  [GitHub](https://github.com/lunardoesdev/notetask)

## 商业项目经验
**PHP 开发者 — 约 1.5 年 (2015–2016, 签署了保密协议)**
负责后端功能开发、SQL 优化与缓存策略。确保在项目截止日期前完成交付。这是早期的工作经历，目前的重心已转移至系统与网络工具开发。

## 脚本与工具
**lunardoesnix** — 我的 NixOS 配置，比其他的更容易部署到 NixOS 安装环境中，无需将其复制到 /etc/nixos。
[GitHub](https://github.com/lunardoesdev/lunardoesnix)

**Yggdrahost** — 一种通过模块化可挂载应用在单个 bun js 进程中托管多个网站、机器人和应用程序的方法。
[GitHub](https://github.com/lunardoesdev/yggdrahost)

**@mawetherbotoboto_bot** — 可以显示天气的 Telegram 机器人。
[源代码](https://github.com/lunardoesdev/yggdrahost/blob/main/modules/bots/weatherbot101.ts)

**backup-my-git** — 用于备份 Git 仓库的 Guile 脚本。
[GitHub](https://github.com/lunardoesdev/backup-my-git)

**yt-dlp-tools** — 方便下载播客和音频的 yt-dlp 包装器
（非常适合 MP3 播放器，支持内嵌封面和智能命名方案）。
[GitHub](https://github.com/lunardoesdev/yt-dlp-tools)

**file2doc** — 将文本文件转换为 bash 脚本的实用工具，该脚本能在相同路径下重新生成这些文件。
[GitHub](https://github.com/lunardoesdev/file2doc)

## 实验性项目
**Fruit Friction** — 基于 Kaplay.js 的物理引擎解谜游戏，形状与摩擦力是通关的关键。
[GitHub](https://github.com/lunardoesdev/fruit-friction)

**Tilemap World Loader** — 从 Tiled 格式中高效渲染瓦片地图，是实现无限滚动效果的基础框架。
[GitHub](https://github.com/lunardoesdev/infinite-world-generator)
