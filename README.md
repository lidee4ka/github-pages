# BEANABOX · продуктовый отчёт · апр–сен 2026

Готовый пакет для **GitHub Pages**.

## Содержимое

- `index.html` — отчёт (Gilroy + Chart.js)
- `fonts/` — локальные шрифты Gilroy
- `ai-visibility.svg` — инфографика видимости в нейросетях (съём 02.10.2026)

## Как выложить

1. Создайте пустой репозиторий на GitHub (например `beanabox-report-2026-09`).
2. Залейте содержимое этой папки в корень репозитория:

```bash
cd github-pages
git init
git add .
git commit -m "Publish BEANABOX product report Apr–Sep 2026"
git branch -M main
git remote add origin https://github.com/<USER>/<REPO>.git
git push -u origin main
```

3. GitHub → **Settings → Pages** → Source: **Deploy from a branch** → Branch: `main` / `/ (root)` → Save.
4. Через 1–2 минуты отчёт будет по адресу `https://<USER>.github.io/<REPO>/`.

## Важно

- В пакет **не** входят API-ключи, дампы Strapi и сырые JSON.
- Шрифт Gilroy — локальный; при публичной выкладке убедитесь, что лицензия позволяет веб-использование.
