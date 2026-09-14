# 🧠 Реестр Институциональной Памяти Студии (`docs/solutions/`)

> **Методология:** Compound Engineering (Continuous Learning Loop)  
> **Цель:** Исключить амнезию ИИ-агентов. Каждая инженерная сессия обогащает базу знаний.

---

## 📌 Реестр Решенных Задач и Платформенных Ловушек (001–011)

| ID | Название Урока | Стек / Компонент | Ключевой Инженерный Вывод |
| :-: | :--- | :--- | :--- |
| **001** | **Обход CORS для ES-модулей в Playwright** | Frontend / E2E / Node.js | Chromium блокирует `type="module"` по протоколу `file:///`. Решение: авто-запуск эфемерного HTTP-сервера на порту 0. |
| **002** | **Архитектура Ralph Agent Harness** | AI Scaffolding / Git | Устранение context rot через изолированные запуски с чистым контекстом, `prd.json` и атомарную фиксацию в Git. |
| **003** | **Калибровка Агентов по Карпатому** | AI Alignment / Code Quality | Устранение оверинжиниринга и мусора: Think First, Simplicity First, Surgical Changes, Goal-Driven. |
| **004** | **Универсальный Мастер-Цикл Реакции (v2.5)** | AI Alignment / Master Loop | 5-фазовый канонический цикл реакции на любые запросы: пробуждение памяти, маршрутизация, шлюз, верификация. |
| **005** | **Изоляция Тестов и Falsy-Фолбэки в Python** | Python / Testing | Запрет конструкции `arg or os.getenv()`, ломающей тесты при `arg=""`. Использовать `if arg is not None:`. |
| **006** | **Упаковка Web-приложений в .exe с иконкой на Панели Задач** | Desktop / .NET 10 / WebView2 | Регистрация AppUserModelID до старта UI, многослойный PNG-in-ICO и SingleFile без CORS. |
| **007** | **Устранение «кракозябр» (CP866 vs UTF-8) в Tauri / PowerShell** | Desktop / Rust / Windows | Решение бага кодировки консольных утилит (DISM/SFC): `chcp 65001` + синхронизация `OutputEncoding`. |
| **008** | **Блокировка файлов Cargo в папках OneDrive (os error 32)** | Desktop / Rust / Cargo / Windows | Перенаправление `CARGO_TARGET_DIR` в `$env:TEMP` устраняет sharing violation и ускоряет сборку в 3-4 раза. |
| **009** | **Ошибка «TaskDialogIndirect не найдена» в Tauri** | Desktop / Tauri 2 / Windows | В кастомный манифест обязательно добавлять зависимость от Common-Controls v6, иначе грузится `comctl32.dll` v5. |
| **010** | **TypeError: Client.__init__() unexpected 'app' в TestClient** | Backend / Python 3.14 / HTTPX | Использование `AsyncClient(transport=ASGITransport(app=app))` устраняет несовместимость с httpx 0.28+. |
| **011** | **Глобальный Триумвират Критиков и Скилл-Хантер (v2.6)** | AI Architecture / Multi-Agent | Устранение blind spots и AI-slop через Тройку Критиков (Скептик + Прагматик + Эксперт с авто-скиллами). |
