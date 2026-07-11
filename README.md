# AutoPost — TikTok App Site

Максимально простой статический сайт для приложения автопостинга видео в TikTok.
Содержит главную страницу, Terms of Service и Privacy Policy.

## Файлы

- `index.html` — главная страница
- `terms.html` — Terms of Service
- `privacy.html` — Privacy Policy
- `style.css` — стили (светлая/тёмная тема)

## Деплой на Vercel

Сборка не нужна — это чистая статика.

**Через веб-интерфейс:** импортируйте репозиторий на [vercel.com/new](https://vercel.com/new).
Framework Preset — **Other**, build/output настраивать не нужно.

**Через CLI:**

```bash
npm i -g vercel
vercel        # предпросмотр
vercel --prod # прод
```

Страницы доступны по адресам `/`, `/terms.html`, `/privacy.html`.

## Перед публикацией

Замените плейсхолдеры: `support@example.com`, название приложения `AutoPost`
и дату «Last updated» — на свои реальные данные.
