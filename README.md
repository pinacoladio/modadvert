# Modadvert

Лендинг рекламного агентства для малого бизнеса. Статический сайт без сборки и серверной части. Все изображения и шрифты хранятся в проекте. Контакт: [@pinacoladio](https://t.me/pinacoladio).

## Файлы

- `dist/index.html` — содержание страницы и контакты.
- `dist/styles.css` — оформление и адаптация под разные экраны.
- `dist/assets/` — изображение и шрифты.
- `.github/workflows/pages.yml` — публикация GitHub Pages после изменений в `main`.

## Локальный просмотр

```sh
python3 -m http.server 4173 --directory dist
```

Откройте http://localhost:4173.

## GitHub Pages

В Settings → Pages выберите Source → GitHub Actions. Отправка в ветку `main` запустит публикацию. Ожидаемый адрес для репозитория `pinacoladio/modadvert`: https://pinacoladio.github.io/modadvert/.

Репозиторий на бесплатном тарифе GitHub должен быть публичным. Все ссылки на ресурсы относительные, поэтому сайт работает и в подпапке `/modadvert/`.

## Материалы

- Manrope: SIL Open Font License 1.1, см. `dist/assets/OFL.txt`.
- Изображение для первого экрана создано с помощью ИИ для этого проекта.
- Аналитика, cookies и формы сбора персональных данных не подключены. Кнопки открывают Telegram.
