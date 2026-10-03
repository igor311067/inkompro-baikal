# ИнКомПро-Байкал — сайт

Статический сайт (без сборки). Публикуется на Netlify из GitHub.

## Деплой
1. Создайте репозиторий на GitHub и загрузите содержимое этой папки в корень (`git init`, `git add .`, `git commit`, `git push`).
2. Netlify → Add new site → Import an existing project → GitHub → выберите репозиторий.
3. Build command: пусто. Publish directory: `.` (настройки уже в `netlify.toml`). Deploy.
4. Домен: Site configuration → Domain management → Add domain `prommeh.ru`, затем пропишите DNS по подсказке Netlify. HTTPS включится автоматически.

## Формы
Две формы (`request`, `callback`) работают через Netlify Forms. После первого деплоя:
Forms → Form notifications → Add notification → Email → `info@inkompro.ru`.
Заявки также видны во вкладке Forms.

## Что заполнить
- `privacy.html` — черновик-шаблон, нужен реальный текст политики.
- `ambient.mp3` (необязательно) — если файла нет, включается синтезированный звук.
- Добавьте картинку для соцсетей и тег `og:image` в `index.html`.
