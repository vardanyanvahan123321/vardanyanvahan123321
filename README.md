# Hi, I'm Vahan Vardanyan

I build **AI automation for small businesses**: Telegram bots, integrations, LLM pipelines
and RAG. Based in Yerevan, Armenia. Open to remote work.

**How I work.** I design the system, write the requirements, and test the result. The code
is written with an AI coding assistant (Claude Code). I say this openly: AI-assisted
development is my method, and every project here has tests, CI and an honest
"Limitations" section, so you can check the result yourself.

## Projects

### [Deep Research Agent](https://github.com/vardanyanvahan123321/deep-research-agent)
A deep research agent that runs entirely on one home PC with a local open model (Qwen3.8-27B
in LM Studio), its own SearXNG and an offline knowledge base. It plans sub-questions, searches,
reads web pages, PDFs and scans, and writes a report with numbered citations. No cloud LLMs.

- Every claim carries a verbatim quote that code finds in the saved source text
- Blind runs on 6 unseen research tasks: every quote found verbatim, 1187 of 1187
- SimpleQA on unseen questions: 56 of 67 = 83.6% (95% interval 72.9–90.6%; small sample,
  an estimate, not a precise figure)
- 601 tests pass in CI (9 skipped), no model needed

`Python` `FastAPI` `SQLite` `PySide6` `LM Studio` `SearXNG` `Podman`

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

## Languages

Armenian (native) · Russian (fluent) · English (B2, comfortable in writing)

## Contact

Email: [vardanyanvahan123@gmail.com](mailto:vardanyanvahan123@gmail.com)

Open to remote roles in AI automation, written communication preferred.
