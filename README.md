# Сайт Олексія Савченка — Meta Ads

Одностраничный сайт performance-маркетолога. Чистый HTML/CSS/JS, без сборки и зависимостей.

- `index.html` — весь сайт: разметка, стили и скрипты в одном файле
- Шрифты подключаются с Google Fonts: Sofia Sans Extra Condensed, Playfair Display, Manrope, IBM Plex Mono

## Локальный просмотр

    python3 -m http.server 8000

Затем открыть http://localhost:8000

## Публикация

GitHub Pages: Settings → Pages → Source: Deploy from a branch → ветка `main`, папка `/ (root)`.

## Что ещё нужно сделать

- [ ] Заменить `href="#contact"` на реальные ссылки Telegram и WhatsApp
- [ ] Поставить настоящие фото вместо заглушек (блок «Обо мне» и коллаж)
- [ ] Добавить скриншоты отзывов в блок «Что говорят клиенты»
- [ ] Украинская версия (тексты готовы)
- [ ] Подключить аналитику: Meta Pixel, GA4
