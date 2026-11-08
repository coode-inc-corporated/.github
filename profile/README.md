```text
╭─────────────────── coode.inc ───────────────────╮
│  receipt photo → trusted data → useful insights  │
╰────────────────────────────────────────────────╯
```

Telegram-first platform for receipt scanning and expense intelligence.

```text
Telegram → TG service → Core → Qwen / Mistral OCR
                              ↓
User confirmation ← draft ← PostgreSQL
        ↓
normalize → product catalog → Open Food Facts
        ↓
embeddings → PostgreSQL + pgvector
```

`NestJS` · `PostgreSQL` · `pgvector` · `Qwen` · `Mistral`
