# Hi, I'm Vahan Vardanyan

I build **AI automation for small businesses**: Telegram bots, integrations, LLM pipelines
and RAG. Based in Yerevan, Armenia. Open to remote work.

**How I work.** I design the system, write the requirements, and test the result. The code
is written with an AI coding assistant (Claude Code). I say this openly: AI-assisted
development is my method, and every project here has tests, CI and an honest
"Limitations" section, so you can check the result yourself.

## Projects

### [AI Business Operator](https://github.com/vardanyanvahan123321/ai-business-operator)
An AI operator for a small service business. It answers customers in Telegram, email and
a web form, books visits, issues PDF invoices, watches competitor prices and sends the
owner a morning report. When it is not sure, it hands the conversation to a human.

- The AI only fills validated schemas; every business rule is plain, tested Python
- RAG on PostgreSQL + pgvector: answers come only from the company's documents
- Nothing is lost and nothing happens twice: store-first queue, retries, idempotency
- 249 tests, 94% coverage, AI evals on 112 messages in three languages
- One-command demo with no API keys: `make demo`

`Python` `FastAPI` `PostgreSQL` `pgvector` `Redis` `Docker` `Gemini / Claude / OpenAI`

### [Telegram Booking Bot](https://github.com/vardanyanvahan123321/telegram-booking-bot)
A booking and FAQ bot for appointment-based businesses, configured with one YAML file.
Inline calendar, free time slots, reminders, owner notifications, three languages.

- Two clients can never get the same time slot (atomic transaction, tested)
- 108 tests, including end-to-end user journeys

`Python` `aiogram 3` `SQLite` `APScheduler` `Docker`

### Local Deep Research — in progress
A research agent that runs on a local LLM: it searches the web, reads the sources and
writes an answer with citations. Measured on a public benchmark. Publication planned for
21 November 2026.

## Languages

Armenian (native) · Russian (fluent) · English (B2, comfortable in writing)
