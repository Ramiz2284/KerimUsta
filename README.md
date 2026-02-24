# KlimaServis — Antalya Klima Tamiri

Сайт по ремонту, обслуживанию и установке кондиционеров в Анталии.

## Стек
- Чистый HTML / CSS / JS (без фреймворков)
- Одностраничное приложение (SPA)
- Двуязычный интерфейс: RU / TR

## Структура
```
index.html   — весь сайт в одном файле
vercel.json  — конфиг для Vercel
README.md    — этот файл
```

## Деплой на Vercel

1. Загрузите репозиторий на GitHub
2. Зайдите на [vercel.com](https://vercel.com) → New Project
3. Подключите репозиторий
4. Framework Preset: **Other**
5. Нажмите Deploy — сайт будет готов

## Деплой через Vercel CLI
```bash
npm i -g vercel
vercel
```

## Замена номера WhatsApp
В файле `index.html` найдите строку:
```js
const WA_NUMBER = '905527300257';
```
Замените на нужный номер.

## SEO
- H1, H2, H3 с ключевыми словами по Анталии
- Meta description и keywords
- FAQ-блок (Google любит)
- SEO-контент скрыт под аккордеоном — не мешает UX
