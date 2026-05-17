[Русский](./README.ru.md) | English

# Dostaffkin — сервис доставки посылок

Живой сайт: https://roman-mikhaylov.github.io/dostaffkin/

Этот репозиторий содержит мою реализацию веб‑приложения **Dostaffkin** — сервиса для оформления и отслеживания доставки посылок по стране и по миру. Приложение написано на **Angular** и развёрнуто на **GitHub Pages**.

## Возможности

- Лендинг с описанием сервиса доставки
- Экран оформления заказа с формой отправки посылки
- Экран трекинга, где можно проверить статус по номеру отправления
- Базовая валидация ключевых полей формы

## Технологии

- Angular (standalone‑компоненты)
- TypeScript
- HTML, CSS
- GitHub Pages как хостинг статического билда

## Живой демо‑сайт

Приложение доступно по адресу:

https://roman-mikhaylov.github.io/dostaffkin/

## Локальный запуск

```bash
git clone https://github.com/roman-mikhaylov/dostaffkin.git
cd dostaffkin
npm install
npm start        # или: ng serve
```

После этого открыть в браузере:

http://localhost:4200

## Сборка и деплой

Продакшн‑сборка создаётся через Angular CLI:

```bash
npm run build    # или: ng build
```

Собранные статические файлы деплоятся на GitHub Pages и доступны по адресу:

https://roman-mikhaylov.github.io/dostaffkin/
