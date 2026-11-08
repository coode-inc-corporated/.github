```text
╭─────────────────── coode.inc ───────────────────╮
│       чек → данные → понятные расходы       │
╰────────────────────────────────────────────────╯
```

Создаём Telegram-платформу для распознавания чеков и умного учёта расходов.

```text
Фото → Telegram → Telegram-сервис → Core → Qwen / Mistral OCR
                                           ↓
Подтверждение ← проверка ← черновик ← PostgreSQL
      ↓
нормализация → каталог → Open Food Facts
      ↓
embeddings → PostgreSQL + pgvector
```

`NestJS` · `PostgreSQL` · `pgvector` · `Qwen` · `Mistral`
