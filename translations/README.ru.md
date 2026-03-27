[English](../readme.md) | [中文](README.zh.md) | [Español](README.es.md) | [Русский](README.ru.md) | [日本語](README.ja.md) | [한국어](README.ko.md)

# Lunar
**Разработчик системного и сетевого ПО | C/C++, Go, Rust, JavaScript/TypeScript, Zig**

Специализируюсь на создании низкоуровневых утилит, биндингов протоколов и кроссплатформенных приложений. Имею опыт работы с прокси-инфраструктурой, шифрованием трафика и нативной разработкой под десктоп. Готов взять на себя задачи на любом уровне стека, если того требует проект.

- Email: [lunarlifeburst+work@gmail.com](mailto:lunarlifeburst+work@gmail.com)
- Telegram: [@retrolunar](https://t.me/retrolunar)
- GitHub: [https://github.com/lunardoesdev](https://github.com/lunardoesdev)

### Удалённая работа по всему миру
- Часовой пояс: GMT+10
- Языки: английский, русский

## Ключевые навыки
- **Системное программирование:** Go, Rust, C/C++, CMake/Make, кросс-компиляция, статическая линковка, WASM (Emscripten).
- **Сети и инфраструктура:** прокси-протоколы (VMess/SS/Hysteria), WireGuard, Docker/Podman, CI/CD (GitHub Actions).
- **Web:** Node.js, TypeScript, Vite, Tailwind, Tauri.
- **Базы данных:** SQLite (с FTS5), MySQL, стратегии кэширования.
- **Скрипты:** Python, Bash, Nim.

## Основные проекты

**Mintfused** — Свой Linux-дистрибутив на основе Linux Mint.
(ISO отсутствует ввиду ограничений бесплатного аккаунта GitHub,
но процесс создания описан детально).
[GitHub](https://github.com/lunardoesdev/mintfused)

**Singerbox** — Go-биндинги для прокси-движка sing-box.
Запуск инстанса внутри текущего процесса из любой ссылки (VLESS, VMess, Shadowsocks, Hysteria). Работает «из коробки» без сложной настройки, корректно завершает работу. Легко встраивается, не требует создания дочерних процессов.
[GitHub](https://github.com/lunardoesdev/singerbox)

**Radihypn** — Интернет-радио на C++/GTK3 с иконкой в трее.
Легковесное нативное десктопное приложение для Linux. Воспроизведение потокового аудио, интеграция в системный трей, минимальное потребление ресурсов.
[GitHub](https://github.com/radihypn/radihypn)

## Избранные публикации

**Подробное руководство по переменным окружения для сборки C/C++ в POSIX**
Практическое руководство по использованию переменных окружения при сборке проектов C и C++ в системах POSIX.
[Читать](https://lunardoesdev.github.io/posts/2026-03-10-posix-environment-variables.html)

**Кросс-компиляторы и тулчейны для различных платформ**
Коллекция кросс-компиляторов и тулчейнов для таргетинга на различные платформы.
[Читать](https://lunardoesdev.github.io/posts/2026-03-11-crosscompilers-for-platforms.html)

## Вклад в Open Source
- **Экосистема i2pd:** настройка CI/CD для i2pd-tools, конфигурация сервиса для dinit (принята в апстрим), Rust-биндинги с автоматической статической линковкой.
- **PurpleI2P/i2pd:** успешный pull request [#2338](https://github.com/PurpleI2P/i2pd/pull/2338).
- **libi2pd:** скрипты сборки для создания shared libraries.
- **Кросс-компиляция для MSX:** воспроизводимые сборки C/ASM ROM.
- **niqlite:** Nim-обертка для SQLite с поддержкой полнотекстового поиска (FTS5).
  [Nimble Directory](https://www.nimble.directory/pkg/niqlite)
- **notetask** (форк): принудительное применение заданного формата даты и времени.
  [GitHub](https://github.com/lunardoesdev/notetask)

## Коммерческий опыт
**PHP-разработчик — ~1.5 года (2015–2016, под NDA)**
Разработка бэкенда, оптимизация SQL-запросов, кэширование. Строгое соблюдение дедлайнов. Это мой прошлый опыт, сейчас я полностью сфокусирован на системном и сетевом программировании.

## Скрипты и Утилиты
**lunardoesnix** — Моя конфигурация NixOS. Её проще развернуть при установке, чем другие; не нужно копировать в /etc/nixos.
[GitHub](https://github.com/lunardoesdev/lunardoesnix)

**Yggdrahost** — Подход к хостингу множества сайтов, ботов и приложений в едином процессе Bun JS с использованием модульных монтируемых приложений.
[GitHub](https://github.com/lunardoesdev/yggdrahost)

**@mawetherbotoboto_bot** — Telegram-бот для отображения погоды.
[Исходный код](https://github.com/lunardoesdev/yggdrahost/blob/main/modules/bots/weatherbot101.ts)

**backup-my-git** — Guile-скрипт для бэкапа Git-репозиториев.
[GitHub](https://github.com/lunardoesdev/backup-my-git)

**yt-dlp-tools** — Обертки над yt-dlp для удобного скачивания подкастов и аудио
(идеально для MP3-плееров, с обложками и умной схемой именования).
[GitHub](https://github.com/lunardoesdev/yt-dlp-tools)

**file2doc** — Утилита, которая конвертирует текстовые файлы в bash-скрипт, воссоздающий эти файлы по тем же путям.
[GitHub](https://github.com/lunardoesdev/file2doc)

**ytdla** — Opinionated скрипт для скачивания аудио с YouTube на базе yt-dlp.
[GitHub](https://github.com/lunardoesdev/ytdla)

**file2sh** — Утилита, которая читает файл и генерирует shell-скрипт, воссоздающий этот файл.
[GitHub](https://github.com/lunardoesdev/file2sh)

**examplenv** — Утилита для генерации безопасного .env.example из вашего .env, перезаписывающая секретные значения на тестовые.
[GitHub](https://github.com/lunardoesdev/examplenv)

## Эксперименты
**Fruit Friction** — Физическая головоломка на движке Kaplay.js, где всё зависит от формы объектов и силы трения.
[GitHub](https://github.com/lunardoesdev/fruit-friction)

**Tilemap World Loader** — Эффективный рендеринг тайловых карт из формата Tiled, основа для реализации бесконечного скроллинга.
[GitHub](https://github.com/lunardoesdev/infinite-world-generator)
