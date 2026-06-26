# lendtovar
# Лендінг товару

## Зміна ціни

Відкрийте файл `config.json` та змініть значення:

```json
"product": {
  "price": "590",
  "oldPrice": "790"
}
```

---

## Зміна номера телефону

```json
"contacts": {
  "phone": "+380955313888"
}
```

Якщо номер використовується в тексті сайту, він оновиться автоматично.

---

## Зміна посилання Telegram

```json
"telegram": "https://t.me/username"
```

---

## Зміна посилання Viber

```json
"viber": "viber://chat?number=%2B380955313888"
```

---

## Публікація змін

Після зміни `config.json`:

1. Збережіть файл.
2. Зробіть Commit.
3. Зміни автоматично опублікуються на сайті через Netlify (1–2 хвилини).

---

## Важливо

Не змінюйте назви полів (`price`, `oldPrice`, `phone`, `telegram`, `viber`), змінюйте лише їх значення.

Приклад правильного файлу:

```json
{
  "product": {
    "price": "590",
    "oldPrice": "790"
  },
  "contacts": {
    "phone": "+380955313888",
    "telegram": "https://t.me/username",
    "viber": "viber://chat?number=%2B380955313888"
  }
}
```
