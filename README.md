# СтальПрофСервис - исходники сайта
На базе GULP сборки для автоматизации вёрстки.

### Описание
- Импорты в HTML. 
Например: `@@include(header.html')` в файле index.html вставит содержимое хедера в HTML.
- Импорт CSS файлов, обработка Post CSS с множеством оптимизаций.  
- Обработка JS с помощью Webpack.  
По умолчанию jQuery не используется, но в модулях присутствует.
- Конвертация картинок в webp, сжатие, при необходимости создание копий других размеров.
- Конвертация шрифтов в woff и woff2. Автоподключение шрифтов в CSS. Создание иконочного шрифта.
- Создана начальная структура файлов/папок для быстрого старта нового проекта.

### Установка
	npm i
Отредактировать **gulp/config/ftp.js** для использования загрузки на FTP.

### Команды
- `npm run dev` — режим разработки с автообновлением браузера.
- `npm run build` — компиляция под продакшен.
- `npm run zip` — упаковка проекта в zip архив.
- `npm run ftp` — выгрузка проекта на FTP.
- `npm run icons` — создание иконочного шрифта.

---

### [Подробное описание сборки](https://starchenkov.pro/create/gulp-pack/ "Читать у меня на сайте")

[Мой Telegram](https://telegram.me/starchenkov "Если что-то пошло не так")
