```text
╭─────────────────── coode.inc ───────────────────╮
│       чек → расходы → понятная статистика      │
╰────────────────────────────────────────────────╯
```

### Расходы - без ручного ввода, ваш личные бухгалтер 

<img src="https://scontent-cph2-1.xx.fbcdn.net/v/t1.6435-9/82087151_1051225251886071_7824077679002386432_n.jpg?stp=dst-jpg_tt6&amp;cstp=mx1000x678&amp;ctp=s1000x678&amp;_nc_cat=104&amp;ccb=1-7&amp;_nc_sid=127cfc&amp;_nc_ohc=zf9UcvkHNYwQ7kNvwGqIoFl&amp;_nc_oc=Adp16qIsGTfEuQNByU82eWdl4Sswjap-sHQWiL8Qp167uz28zkqonxIUb3XPxurGGg8&amp;_nc_zt=23&amp;_nc_ht=scontent-cph2-1.xx&amp;_nc_gid=Iq7R5WaGnQ_bHXdLv9U5wA&amp;_nc_ss=7a2a8&amp;oh=00_AQQ00G2PiSCVsHVjbs8sotjAN74Nbw5OJYm8FlB0OAGCSg&amp;oe=6B181F3C" alt="Ваш личный бухгалтер" width="480">

Бесплатный Telegram-бот, который превращает фотографию чека в готовую запись о покупке: распознаёт товары и цены, помогает исправить неточности, раскладывает расходы по категориям и собирает понятную статистику.

> Проект бесплатный. Если бот сэкономил вам время, нас можно угостить кофе ☕

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
