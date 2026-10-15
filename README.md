# MINI PHOTO STUDIO

Фото-, видеоредактор и редактор аватарок в одном файле `index.html` (без сборки и зависимостей).

## Запуск
1. Распакуйте архив и откройте `index.html` в Chrome, Edge или Firefox (лучше через Live Server в Cursor).
2. Проекты сохраняются в IndexedDB браузера (блок «Мои проекты» на главной).

## Публикация (GitHub Pages)
1. Создайте репозиторий на GitHub и загрузите `index.html`.
2. Settings → Pages → Deploy from a branch → main / root.
3. Через минуту сайт откроется по ссылке вида `https://ВАШ-НИК.github.io/ИМЯ-РЕПО/`.

## Ограничения
Экспорт видео идёт в реальном времени (MediaRecorder, WebM). В Safari возможны проблемы с фильтрами и звуком.
