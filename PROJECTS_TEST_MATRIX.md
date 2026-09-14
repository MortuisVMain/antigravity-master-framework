# 📊 Сводная Инженерная Матрица Тестирования Проектов

В данной таблице зафиксированы результаты аудита, тестирования и модернизации всех 6 софтверных проектов студии **MortuisVMain Production Hub** и системного движка **The Critic Triad** по стандарту **Antigravity Master Framework v2.6**.

---

## 📋 Таблица Тестирования Компонентов и Стек Технологий

| # | Проект / Компонент | Среда & Где работал | Что делали (Функционал & Модернизация) | Что использовали (Стек, API, Библиотеки) | Статус & Метод Верификации |
| :-: | :--- | :--- | :--- | :--- | :-: |
| **01** | **Cashflow Hub & Shorts Factory** | `Ideas/Cashflow_Hub/`<br/>Windows 11, Python 3.11 venv | Автоматизированная фабрика вирусных Shorts/Reels про личные финансы, инвестиции и акции. **Апгрейд:** генератор караоке-субтитров в стиле Apple (`generate_apple_style_ass`), флаг `--apple-style` в CLI `run.py script produce`, исправление бага falsy-фолбэка API в `stock_fetcher.py`. | Python 3.11, Edge-TTS (нейроозвучка), MoviePy (видеомонтаж), SQLite, Rich CLI, Pydantic, AlphaVantage/YahooFinance API, ASS-субтитры с анимацией караоке и SF Pro. | ✅ `pytest tests/`<br/>**16/16 PASS (1.89s, exit code 0)** |
| **02** | **ScreenDimmer Pro** | `Ideas/ScreenDimmer/`<br/>Windows 11, .NET 10.0 / 8.0 SDK | Аппаратное и программное управление яркостью мониторов. **Апгрейд:** полное преображение HUD яркости `BrightnessHud.cs` в дизайн **macOS Sequoia Dynamic Island** (парящая пилюля 240x64px, скругления 20px, матовое стекло Space Black `#121216`, динамические иконки ☀️/🌤️/🌘/🌑, слайдер Apple Blue). | C# 12 / .NET, Win32 Interop (`dxva2.dll`, `PhysicalMonitor`, `SetPhysicalMonitorBrightness`), WMI (`WmiMonitorBrightnessMethods`), WPF/WinForms GDI+ рендеринг, глобальные хуки `WH_KEYBOARD_LL`. | ✅ `dotnet build -c Release`<br/>**0 ошибок, 0 пред. (exit code 0)** |
| **03** | **Open Steam Idler** | `Ideas/open-steam-idler/`<br/>Windows 11, Node.js 20+, Electron 33 | Фарм коллекционных карточек Steam и накрутка часов без установки самих игр. **Апгрейд:** внедрение токенов Apple Cupertino в `src/renderer/src/styles/globals.css` (тема Space Black `#0a0a0c`, матовый сайдбар, светодиод Apple Green `#30d158`, типографика SF Pro с табличными цифрами `tnum`). | Electron 33, React 18, Vite, TypeScript 5, Tailwind CSS, протокол SteamKit (`steam-user`), безопасный IPC-мост `contextBridge`. | ✅ `npm run typecheck`<br/>**0 ошибок типов (exit code 0)** |
| **04** | **Power Management Suite** | `Ideas/Scripts/`<br/>Windows 11, Python 3, PyInstaller | Виджет таймера выключения ПК. **Апгрейд:** разработка флагманского виджета `ApplePowerSuite.py` в стиле macOS Control Center (безрамочный интерфейс, светофор окон macOS, сегментированные кнопки режимов, таймер SF Pro, 60-секундный аудиосигнал, отмена по Win32 API) в дополнение к стимпанк-версии. | Python 3, Tkinter GUI, Win32 API (`winsound.PlaySound`, `SetWindowLong`), системные утилиты `shutdown.exe /s /t`, сборка в PyInstaller EXE. | ✅ `python -m py_compile`<br/>**Байткод чист (exit code 0)** |
| **05** | **Wallpaper Turbo Downloader** | Браузер (Tampermonkey / Violentmonkey), веб-каталоги GoodFon, Wallhaven | Пакетный сборщик полноразмерных HD/4K обоев. **Апгрейд:** редизайн плавающей панели `#gf-turbo-dock` в стиль Apple Dynamic Island с пружинными микроинтеракциями (v3.7.0). | JavaScript ES2024, HTML5 Canvas, алгоритм визуального хэширования dHash (64-бит отсев дубликатов), JSZip (упаковка архива на лету в браузере), Tampermonkey API (`GM_download`, `GM_xmlhttpRequest`). | ✅ `node -c`<br/>**Синтаксис валиден (exit code 0)** |
| **06** | **Video Turbo Downloader** | Браузер (Tampermonkey / Violentmonkey), видеоплатформа SxyPrn | Перехватчик защищенных видеопотоков и пакетный экспорт. **Апгрейд:** трансформация панели `#sxy-turbo-dock` в центрированную пилюлю Apple Control Center с размытием матового стекла и тактильными кнопками. | JavaScript ES2024, HTML5 Video API, перехват XHR/Fetch, экспорт очереди прямых ссылок в Aria2 JSON-RPC (16 потоков), генератор Windows `.bat` скриптов с `curl.exe`, экспорт в IDM. | ✅ `node -c`<br/>**Синтаксис валиден (exit code 0)** |
| **07** | **The Critic Triad Engine** | Глобально `~/.gemini/`, все воркспейсы, Antigravity IDE | Ликвидация амнезии и AI-slop через Коллегию Трёх Критиков (Скептик Red-Team, Прагматик Карпати, Профильный Эксперт) с **автоматическим сканированием 94+ навыков**. | Multi-Agent Review Triad, Reflexion, 8 универсальных доменов, YAML SKILL.md спецификации, Мастер-Цикл `GEMINI.md` v2.6. | ✅ `docs/solutions/`<br/>**Урок 011 зафиксирован** |

---

## 🔍 Детальный Разбор Механик по Проектам

### 1. Cashflow Hub & Shorts Factory
* **Ядро генерации:** Принимает финансовую тему (акции, дивиденды, крипта) ➔ генерирует сценарий с хуком ➔ синтезирует голос через Edge-TTS ➔ собирает ASS субтитры с точностью до слова ➔ накладывает вертикальное видео 1080x1920 и генерирует MP4.
* **Apple ASS Subtitles:** Реализованы в `core/subtitles.py` (`generate_apple_style_ass`). Шрифт `SF Pro Display`, цвет `#f5f5f7`, мягкая черная тень `rgba(0,0,0,0.85)`, активное караоке-слово подсвечивается акцентным Apple Blue `#0071e3`.
* **Урок изоляции тестов (Solution 005):** Конструкция `api_key or os.getenv(...)` заменена на `api_key if api_key is not None else ...`, предотвращая утечку реальных переменных окружения в mock-тесты.

### 2. ScreenDimmer Pro
* **DDC/CI Протокол:** Прямая отправка VCP-команд (Virtual Control Panel) через шину I2C видеокарты на монитор (`VCP Code 0x10` для яркости). Не искажает цветовую гамму матрицы, в отличие от программных оверлеев.
* **macOS Dynamic Island HUD:** Окно `BrightnessHud.cs` без рамки с `WS_EX_TOOLWINDOW` и `WS_EX_TOPMOST`. Плавное появление, показ текущего значения (0-100%) и автоскрытие через 1.8 секунды после последнего нажатия горячих клавиш.

### 3. Open Steam Idler
* **Архитектура Electron + Vite:** Разделение на главный процесс Node.js (управление аккаунтом через SteamKit) и процесс рендерера React (UI).
* **Стиль Space Black:** Вся палитра привязана к глубокому черному фону `#0a0a0c`, полупрозрачным карточкам `rgba(26,26,30,0.72)` и шрифтам SF Pro с табличным выравниванием чисел `tnum`.

### 4. Power Management Suite
* **ApplePowerSuite.py:** Чистый Python + Tkinter без тяжелых внешних зависимостей. Создает безрамочное окно с эмуляцией кнопок управления окном macOS («светофор»), сегментированным селектором таймера (15м, 30м, 1ч, 2ч, Свой) и обратным отсчетом.
* **Безопасность:** За 60 секунд до выключения раздается предупреждающий звуковой сигнал. Кнопка «Отмена» немедленно выполняет `shutdown.exe /a`.

### 5. Wallpaper Turbo Downloader
* **dHash Алгоритм:** Сжимает изображение в Canvas до сетки 9x8, переводит в градации серого и сравнивает соседние пиксели, генерируя 64-битный хэш. Позволяет мгновенно находить и пропускать дубликаты разных разрешений без перегрузки CPU.
* **JSZip In-Browser:** Все выбранные обои упаковываются в единый ZIP-архив в памяти браузера без отправки на промежуточные серверы.

### 6. Video Turbo Downloader
* **Перехват потоков:** Перехватывает вызовы `fetch` и `XMLHttpRequest`, извлекая прямые URL к MP4/HLS потокам высочайшего качества (1080p/4K).
* **Мульти-экспорт:** Генерирует готовые команды для параллельного скачивания в 16 потоков через локальный Aria2 RPC демон или создает переносимый `.bat` скрипт для Windows.
