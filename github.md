# Как загрузить проект на GitHub

1. Создайте репозиторий: github.com → «New repository» → имя (например, `karta-dnya`) → Public → Create repository.
2. На странице репозитория: «Add file» → «Upload files».
3. Распакуйте архив и перетащите в окно загрузки содержимое папки «карта-дня»: `index.html`, `cards-data.js`, `README.md` и папку `cards` целиком.
4. Нажмите «Commit changes».
5. Включите сайт: Settings → Pages → Source: «Deploy from a branch» → Branch: `main`, папка `/ (root)` → Save.
6. Через минуту сайт откроется по адресу: `https://ВАШ-ЛОГИН.github.io/ИМЯ-РЕПОЗИТОРИЯ/`

Важно:
- Регистр имён файлов важен: `cards/TheLovers.jpg` — именно так.
- Папку `cards` не переименовывайте: в коде пути вида `cards/xxx.jpeg`.
- Если сайт открылся, а картинок нет — проверьте, что папка `cards` загрузилась целиком (78 файлов).
- Архив в ручную загрузку GitHub не принимает — загружаются именно файлы и папки.
