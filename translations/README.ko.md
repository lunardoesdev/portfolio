[English](../readme.md) | [中文](README.zh.md) | [Español](README.es.md) | [Русский](README.ru.md) | [日本語](README.ja.md) | [한국어](README.ko.md)

# Lunar
**시스템 및 네트워크 개발자 | C/C++, Go, Rust, JavaScript/TypeScript, Zig**

로우레벨 도구, 프로토콜 바인딩, 크로스 플랫폼 애플리케이션을 개발하고 있습니다. 프록시 인프라, 암호화된 네트워크 통신, 네이티브 데스크톱 앱 개발에 대한 풍부한 경험을 보유하고 있으며, 프로젝트의 요구사항에 따라 스택의 모든 계층에서 원활하게 작업할 수 있습니다.

- 이메일: [lunarlifeburst+work@gmail.com](mailto:lunarlifeburst+work@gmail.com)
- Telegram: [@retrolunar](https://t.me/retrolunar)
- GitHub: [https://github.com/lunardoesdev](https://github.com/lunardoesdev)

### 글로벌 원격 근무
- 시간대: GMT+10
- 구사 언어: 영어, 러시아어

## 핵심 기술
- **시스템:** Go, Rust, C/C++, CMake/Make, 크로스 컴파일, 정적 링킹, WASM (Emscripten)
- **네트워크 및 인프라:** 프록시 프로토콜 (VMess/SS/Hysteria), WireGuard, Docker/Podman, CI/CD (GitHub Actions)
- **웹:** Node.js, TypeScript, Vite, Tailwind, Tauri
- **데이터베이스:** SQLite (FTS5 지원), MySQL, 캐싱 전략
- **스크립트:** Python, Bash, Nim

## 주요 프로젝트

**Singerbox** — sing-box 프록시 엔진을 위한 Go 바인딩
임의의 공유 링크(VLESS, VMess, Shadowsocks, Hysteria)에서 단일 프로세스 내의 인스턴스를 생성합니다. 설정 없는(Zero-config) 기본값과 깔끔한 종료 처리를 지원합니다. 서브 프로세스가 없어 시스템 임베딩에 적합합니다.
[GitHub](https://github.com/lunardoesdev/singerbox)

**Radihypn** — 트레이 아이콘을 지원하는 C++/GTK3 인터넷 라디오
가벼운 리눅스 네이티브 데스크톱 애플리케이션입니다. 스트리밍 재생, 시스템 트레이 통합 기능과 함께 최소한의 리소스만 차지합니다.
[GitHub](https://github.com/radihypn/radihypn)

## 오픈소스 기여
- **i2pd 생태계:** i2pd-tools를 위한 지속적인 빌드 구성, dinit 서비스 구성(업스트림에 병합됨), 자동 정적 링킹이 포함된 Rust 바인딩 개발.
- **PurpleI2P/i2pd:** 풀 리퀘스트 [#2338](https://github.com/PurpleI2P/i2pd/pull/2338) 성공적 병합 완료.
- **libi2pd:** 공유 라이브러리 패키징을 위한 빌드 스크립트 작성.
- **MSX 크로스 컴파일:** 재현 가능한 C/ASM ROM 빌드 환경 구성.
- **niqlite:** FTS5를 지원하는 SQLite용 Nim 래퍼(Wrapper) 라이브러리.
  [Nimble Directory](https://www.nimble.directory/pkg/niqlite)
- **notetask** (포크): 원하는 날짜/시간 형식으로 강제 설정 기능 추가.
  [GitHub](https://github.com/lunardoesdev/notetask)

## 상업용 개발 경험
**PHP 개발자 — 약 1.5년 (2015–2016, NDA 체결)**
백엔드 기능 개발, SQL 최적화, 캐싱 작업 등을 담당했으며, 마감 기한 내에 성공적으로 제품을 출시했습니다. 과거의 경험이며, 현재는 시스템 및 네트워크 도구 개발에 집중하고 있습니다.

## 스크립트 및 유틸리티
**backup-my-git** — Git 저장소를 백업하기 위한 Guile 스크립트.
[GitHub](https://github.com/lunardoesdev/backup-my-git)

**yt-dlp-tools** — 팟캐스트 및 오디오의 편리한 다운로드를 위한 yt-dlp 래퍼
(MP3 플레이어에 적합하며 커버 이미지 삽입 및 스마트한 네이밍 규칙 지원).
[GitHub](https://github.com/lunardoesdev/yt-dlp-tools)

## 실험적인 프로젝트
**Fruit Friction** — Kaplay.js로 제작된 물리 기반 퍼즐 게임으로, 모양과 마찰력이 게임의 핵심 요소입니다.
[GitHub](https://github.com/lunardoesdev/fruit-friction)

**Tilemap World Loader** — Tiled 형식의 타일맵을 효율적으로 렌더링하여 무한 스크롤의 기반이 되는 시스템입니다.
[GitHub](https://github.com/lunardoesdev/infinite-world-generator)
