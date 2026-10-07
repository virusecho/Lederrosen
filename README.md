# Lederrosen — оверрайд теми

Основний файл стилів: [`lederrosen-theme.css`](lederrosen-theme.css).

Посилання для Shopware:

```text
https://cdn.jsdelivr.net/gh/virusecho/Lederrosen@main/lederrosen-theme.css
```

У налаштуваннях зі скріншота виберіть **CSS-Datei laden → ja** і вставте це посилання в **CSS-Datei**. Якщо поле вже містить незмінний префікс `https://`, вставте лише:

```text
cdn.jsdelivr.net/gh/virusecho/Lederrosen@main/lederrosen-theme.css
```

**JavaScript-Datei laden** залиште **nein** — JavaScript-файл не потрібен.

У [`google-site-verification.html`](google-site-verification.html) збережено наданий meta-тег Google Search Console. Його потрібно додати до HTML `<head>` сайту через налаштування теми або інтеграцію заголовка. CSS не може додати HTML meta-тег.

Імпорт Google Fonts розташований на початку CSS-файлу, як того вимагає синтаксис CSS.
