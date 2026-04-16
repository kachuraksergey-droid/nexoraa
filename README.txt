NEXORA AI — Deploy Package
==========================

Структура:
  index.html          — головний файл сайту
  fonts/              — шрифти TT Firs Neue (7 файлів)
  og-image.jpg        — TODO: створи 1200×630px і додай сюди
  apple-touch-icon.png — TODO: створи 180×180px і додай сюди

Деплой:
  Netlify / Vercel — просто перетягни папку deploy/ у браузер
  cPanel           — завантаж вміст папки deploy/ у public_html/
  GitHub Pages     — запушируй вміст deploy/ у gh-pages гілку

Після деплою:
  1. Перевір PageSpeed:   https://pagespeed.web.dev
  2. Перевір OG-превью:   https://opengraph.xyz
  3. Підстав реальні URL соцмереж у футері (TODO-коментарі в index.html)
  4. Підключи GA4 і Meta Pixel (заглушки вже є в <head>)
  5. Підключи форму: Formspree або власний endpoint (коментар у handleCtaSubmit)
