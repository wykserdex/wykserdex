# wykse

<img src="shadowfiend.jpg" alt="shadowfiend" width="400">

Python / Go — Telegram Security & OSINT. аххахАХАХХА

Clean Architecture · human approval by default · rate limits · idempotency · evidence, not hype.

## Stack

`Python 3.11+` `Go` `TypeScript` `FastAPI` `SQLAlchemy 2.0` `PostgreSQL (GIN / trigram)` `Telethon` `Next.js` `Drizzle` `Ollama` `Docker` `Alembic`

## Core

| Repo | Что это |
|---|---|
| [korus](https://github.com/wykserdex/korus) | OSINT intel-graph по Telegram: GIN-триграммы, HMAC blind-index, граф одним SQL CTE |
| [otklik](https://github.com/wykserdex/otklik) | Outreach по вакансиям: скоринг, персональные драфты, аппрув человеком, лимиты |
| [yadro](https://github.com/wykserdex/yadro) | Ядро мультитул-бота: категории-плагины, параллельный мультиаккаунт, SQLite-задачи |
| [campaign-graph](https://github.com/wykserdex/campaign-graph) | Корреляционный граф UntilSec: сводит Secret / Leak / Phish в одну кампанию |
| [aether-250](https://github.com/wykserdex/aether-250) | Своя локальная LLM 250M с нуля: Gated Retention, чистый PyTorch |
| [wedra](https://github.com/wykserdex/wedra) | Оркестратор цепочек на Go: YAML-пайплайны, гейты аппрува, журнал ранов |

> Старые имена реп GitHub редиректит автоматически.

## Принципы

- ничего не уходит человеку без аппрува
- FloodWait уважаем, а не обходим
- `.env` и `*.session` никогда не коммитятся
- вердикт только с доказательствами

## UntilSec family

`wykse` (антискам) + `untilphish` (антифишинг) + `keywatch` (утёкшие секреты) + `leakeye` (утечки) → все сливаются в `campaign-graph`.

## Контакт

Telegram: [@nerunes](https://t.me/nerunes) · GitHub: [@wykserdex](https://github.com/wykserdex)
