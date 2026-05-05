# OMS Design System

Дизайн-система ONE MORE STUDIO: токены (цвет, типографика, отступы) и набор атомов/компонентов (chip, numbered row, comp cell, stat, chrome bar) на чистом CSS.

## Содержимое

- `design-system/tokens.css` — CSS-переменные, `@font-face` для локальных шрифтов и утилитарные классы.
- `design-system/OMS Design System.html` — живая страница-витрина дизайн-системы.
- `design-system/fonts/` — локальные `.woff2` файлы Manrope и JetBrains Mono (subsets: latin, latin-ext, cyrillic, cyrillic-ext).

## Использование

Откройте `design-system/OMS Design System.html` в браузере или подключите `tokens.css` напрямую — шрифты подгрузятся локально, без обращения к Google Fonts CDN:

```html
<link rel="stylesheet" href="design-system/tokens.css">
```

При копировании `tokens.css` в свой проект перенесите рядом папку `fonts/` — пути в `@font-face` относительные (`./fonts/...`).

Шрифты: Manrope (300/400/500/600/700), JetBrains Mono (400/500/600). Сетка задизайнена под 1920×1080.
