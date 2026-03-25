[English](../readme.md) | [中文](README.zh.md) | [Español](README.es.md) | [Русский](README.ru.md) | [日本語](README.ja.md) | [한국어](README.ko.md)

# Lunar
**システム＆ネットワーク開発者 | C/C++, Go, Rust, JavaScript/TypeScript, Zig**

低レイヤーのツール、プロトコルバインディング、クロスプラットフォームアプリケーションの開発を専門としています。プロキシインフラストラクチャ、暗号化ネットワーク、ネイティブデスクトップアプリのバックグラウンドを持っています。プロジェクトの要件に応じて、技術スタックのあらゆる層で柔軟に対応できます。

- メール: [lunarlifeburst+work@gmail.com](mailto:lunarlifeburst+work@gmail.com)
- Telegram: [@retrolunar](https://t.me/retrolunar)
- GitHub: [https://github.com/lunardoesdev](https://github.com/lunardoesdev)

### フルリモート勤務
- タイムゾーン: GMT+10
- 言語: 英語、ロシア語

## コアスキル
- **システム:** Go, Rust, C/C++, CMake/Make, クロスコンパイル, 静的リンク, WASM (Emscripten)
- **ネットワーク・インフラ:** プロキシプロトコル (VMess/SS/Hysteria), WireGuard, Docker/Podman, CI/CD (GitHub Actions)
- **Web:** Node.js, TypeScript, Vite, Tailwind, Tauri
- **データ:** SQLite (FTS5対応), MySQL, キャッシュ戦略
- **スクリプト:** Python, Bash, Nim

## 主要プロジェクト

**Mintfused** — Linux Mint ベースのカスタム Linux ディストリビューション
（GitHubの無料アカウントの制限によりISOはありませんが、作成プロセスは
詳細に記載されています）。
[GitHub](https://github.com/lunardoesdev/mintfused)

**Singerbox** — sing-boxプロキシエンジンのGoバインディング
任意の共有リンク（VLESS, VMess, Shadowsocks, Hysteria）から同一プロセス内でインスタンスを生成。ゼロコンフィグなデフォルト設定とクリーンな終了処理。サブプロセス不要で、システムへの組み込みが容易。
[GitHub](https://github.com/lunardoesdev/singerbox)

**Radihypn** — トレイアイコン付きC++/GTK3インターネットラジオ
軽量なLinux向けネイティブデスクトップアプリ。ストリーミング再生、システムトレイ連携、最小限のリソース消費を実現。
[GitHub](https://github.com/radihypn/radihypn)

## 主な出版物

**POSIX C/C++ ビルドの環境変数に関する詳細ガイド**
POSIX システムで C および C++ プロジェクトをビルドする際の環境変数の使用に関する実践的なガイド。
[読む](https://lunardoesdev.github.io/posts/2026-03-10-posix-environment-variables.html)

**様々なプラットフォーム向けのクロスコンパイラとツールチェーン**
様々なプラットフォームをターゲットにするためのクロスコンパイラとツールチェーンのコレクション。
[読む](https://lunardoesdev.github.io/posts/2026-03-11-crosscompilers-for-platforms.html)

## オープンソースへの貢献
- **i2pdエコシステム:** i2pd-toolsの継続的ビルドの構築、dinitサービス設定の追加（アップストリームにマージ済）、自動静的リンク付きのRustバインディングの開発。
- **PurpleI2P/i2pd:** プルリクエスト [#2338](https://github.com/PurpleI2P/i2pd/pull/2338) が正常にマージされました。
- **libi2pd:** 共有ライブラリのパッケージング用ビルドスクリプトの作成。
- **MSX クロスコンパイル:** 再現性のあるC/ASM ROMビルド。
- **niqlite:** FTS5をサポートするSQLiteのNimラッパーライブラリ。
  [Nimble Directory](https://www.nimble.directory/pkg/niqlite)
- **notetask** (フォーク): 任意のフォーマットで日時を強制的に設定。
  [GitHub](https://github.com/lunardoesdev/notetask)

## 業務経験
**PHPデベロッパー — 約1.5年 (2015–2016, NDA締結済み)**
バックエンドの機能開発、SQLの最適化、キャッシュ処理を担当。厳しい期限内での製品リリースを達成しました。過去の経歴であり、現在の焦点はシステムおよびネットワークツールにあります。

## スクリプトとユーティリティ
**lunardoesnix** — 私の NixOS 設定。他のものより NixOS インストール環境への展開が簡単で、/etc/nixos にコピーする必要はありません。
[GitHub](https://github.com/lunardoesdev/lunardoesnix)

**Yggdrahost** — モジュール式のマウント可能なアプリを使用して、単一の bun js プロセスで複数のサイト、ボット、アプリをホストするアプローチ。
[GitHub](https://github.com/lunardoesdev/yggdrahost)

**@mawetherbotoboto_bot** — 天気を表示できるTelegramボット。
[ソースコード](https://github.com/lunardoesdev/yggdrahost/blob/main/modules/bots/weatherbot101.ts)

**backup-my-git** — GitリポジトリをバックアップするためのGuileスクリプト。
[GitHub](https://github.com/lunardoesdev/backup-my-git)

**yt-dlp-tools** — ポッドキャストやオーディオの便利なダウンロードのためのyt-dlpラッパー
（MP3プレーヤーに最適で、カバー画像の埋め込みやスマートな命名規則をサポート）。
[GitHub](https://github.com/lunardoesdev/yt-dlp-tools)

**file2doc** — テキストファイルを、同じパスにそれらのファイルを再現するbashスクリプトに変換するユーティリティ。
[GitHub](https://github.com/lunardoesdev/file2doc)

## 実験的なプロジェクト
**Fruit Friction** — Kaplay.jsで作られた物理ベースのパズルゲーム。形状と摩擦が鍵となります。
[GitHub](https://github.com/lunardoesdev/fruit-friction)

**Tilemap World Loader** — Tiledフォーマットからの効率的なタイルマップレンダリング。無限スクロールの基礎として機能します。
[GitHub](https://github.com/lunardoesdev/infinite-world-generator)
