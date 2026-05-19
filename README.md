# AI-инженер: Claude Code, MCP-серверы, AI-боты под ключ

> Помогаю русскоязычным SMB и indie-разработчикам автоматизировать рутину через AI-агенты, кастомные MCP-серверы и Telegram-ботов с AI-логикой. Работаю анонимно, по Kwork-escrow.

---

## 🎯 Что я решаю для клиента

| Задача клиента | Что я делаю | От |
|---|---|---|
| «Хочу подключить Claude/Cursor к моим данным» | MCP-сервер под твой источник (БД, API, файлы) | 3 500 ₽ |
| «Нужен Telegram-бот с AI-логикой» | Бот: входной поток → Claude/GPT → Telegram | 2 500 ₽ |
| «Слышал про Claude Code — настрой под меня» | Setup Claude Code + 3 кастомных субагента | 2 500 ₽ |
| «Сделай кастомного Claude Code субагента» | Узкоспециализированный субагент под workflow | 1 500 ₽ |

Все цены — для первых 3 клиентов под отзыв. Дальше — рыночные.

---

## ⏱ Как заказать

1. **Опиши задачу на Kwork** → [мой профиль](https://kwork.ru/user/agentforge_ru)
2. **Отвечаю в течение 2-4 часов** в рабочее время (МСК)
3. **Согласовываем scope → ТЗ → старт.** Аванс через Kwork-escrow

В каждый заказ входит: рабочий код в git, README, видео-демо (2-3 мин), 2 ревизии.

---

## 📦 Reference implementations (открытый код)

Это **не клиентские кейсы** — это production-ready референс-проекты на моём стеке. Используй как есть, форкни, или закажи кастомную версию под свою задачу.

### Для подключения Claude к твоим данным

- **[mcp-sqlite-server](https://github.com/agentforge-ru/mcp-sqlite-server)** — MCP-сервер для SQLite с safety guards. Read/write tools, защита от DROP/TRUNCATE. *Подойдёт если нужна локальная БД доступная Claude.*

- **[mcp-google-sheets](https://github.com/agentforge-ru/mcp-google-sheets)** — MCP-сервер для Google Sheets через service account. *Подойдёт если хочешь чтобы Claude читал/писал твои таблицы.*

### Для Telegram-автоматизации

- **[tg-news-digest-bot](https://github.com/agentforge-ru/tg-news-digest-bot)** — RSS-фиды → Claude ранжирует и саммаризует → утренний дайджест в Telegram. *Reference implementation для любого "контент-агрегатора с AI".*

### Для Claude Code

- **[opportunity-scout](https://github.com/agentforge-ru/opportunity-scout)** — Claude Code субагент для контрарианского market research через 6 методологий (Inversion, Pre-mortem, JTBD, Blue Ocean и др.)

- **[council-orchestrator](https://github.com/agentforge-ru/council-orchestrator)** — Meta-агент: запускает 3-5 специалистов параллельно, синтезирует консенсус + dissent.

- **[claude-readme-generator](https://github.com/agentforge-ru/claude-readme-generator)** — Субагент для генерации README с обязательной honesty-секцией Limitations.

---

## 🛠 Стек

**Languages:** Python 3.10+, SQL, Markdown, YAML
**AI:** Anthropic Claude (Haiku / Sonnet / Opus), OpenAI когда того требует клиент
**Claude tools:** Claude Code, Claude Desktop, MCP Python SDK
**Telegram:** aiogram, raw Bot API через httpx
**Data:** SQLite, PostgreSQL, Google Sheets API
**Ops:** Git/GitHub, gh CLI, Docker, setuptools

**Чего не делаю:** no-code платформы (n8n / Make / Zapier) без явного требования клиента, JS-heavy фронтенды, iOS/Android, дизайн, маркетинг.

---

## 🤝 Связь

- **Заказы:** [Kwork → agentforge_ru](https://kwork.ru/user/agentforge_ru)
- **Вопросы по существующим репо:** GitHub Issues в соответствующем репо
- **Hire-запросы:** issue с префиксом `[hire]` в любом репо — отвечаю в течение 24 часов

Работаю анонимно (текст и voice-over, без лица/имени). Общение на русском или письменный английский.

---

## 📜 Принципы работы

- **Честный scope.** Каждый проект — с явным «что входит / что НЕ входит». Без scope creep и скрытых доплат.
- **Safety-by-default.** Инструменты которые трогают данные — с refuse-on-destructive флагами. Writes выключены пока ты явно не включишь.
- **Открытый код.** Предпочитаю отдавать в публичный git (с sanitize'нутыми данными) чтобы ты мог переиспользовать подход. Приватные репозитории — по запросу.
- **Без vendor lock-in.** Каждый проект документирует как мигрировать с него, не только как пользоваться.

---

## 📊 Recent work

*(Обновляю после каждого завершённого заказа)*

— *Ничего не сдано пока. Профиль создан 2026-05-19.*
