# OXWEB — статическая версия для GitHub Pages

Эта папка предназначена для самого простого просмотра дизайна через GitHub Pages.

## Как загрузить

1. В репозитории удалите старые неправильно загруженные файлы или создайте новый пустой репозиторий.
2. Загрузите в корень репозитория только содержимое этой папки:
   - `index.html`
   - папку `assets`
   - `.nojekyll`
   - `README_UPLOAD.md` можно оставить или удалить.
3. Откройте GitHub → Settings → Pages.
4. В Build and deployment выберите:
   - Source: Deploy from a branch
   - Branch: main
   - Folder: /root
5. Нажмите Save и подождите 1–3 минуты.

## Важно

Не загружайте сюда `App.tsx`, `main.tsx`, `styles.css`, `package.json`, `vite.config.ts` и другие исходники, если хотите быстрый просмотр без сборки. GitHub Pages не компилирует React/Vite сам в режиме Deploy from branch; он просто показывает статические файлы.
