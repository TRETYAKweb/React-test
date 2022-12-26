# ДЗ lesson-3-1

1. Зарегистрироваться и установить Figma. Открыть макет. 

2. Cоздать новую ветку lesson-3-1. Для этого нужно переключится на основную ветку вашего репозитория **main**

   1. **git checkout main** – Переключение нa ветку lessons
   2. **git pull** - Забираем изменения которые ментор проверил
   3. **git checkout -b lesson-3-1** - создаем новую ветку
   
2. В этой ветке создать структуру проекта

   ```
   prj-1/ <-- папка проекта
   	img/ <-- папка для картинок
   	css/ <-- папка для стилей
   	index.html
   ```
   
4. Экспортировать все графические элементы из макета в папку img. 

   1. Иконки - в формате svg
   2. Картинки  с прозрачным фоном -  png
   3. Обычные картинки - jpg


      **ВАЖНО!** Грамотно именуйте картинки. А именно: название картинки должно отображать суть картинки. К примеру, если это иконка социальной сети Facebook то название картинки будет например *facebook-icon.svg*, если это фоновое изображение секции можно назвать картинку как *<название-секции>-back-img.jpg* - *about-back-img.jpg*. Нельзя использовать пробелы в названиях картинок.

4. Сделать оптимизацию картинок, то как предлагает ресурс в дефолтных настройках.

   1. https://squoosh.app/
   2. https://jakearchibald.github.io/svgomg/
   3. [tinypng](https://tinypng.com/) 
   
4. Затем их нужно добавить картинки в ваш проект в GitLab. 

4. После всего нужно выполнить команды 

   1. **git add .** — Добавление всех новых файлов
   2. **git commit -m "added images_optimize"** — создание комита
   3. **git push origin  lesson-3-1** — отправка изменений в репозиторий

1. И затем сделать мерж реквест на ментора - **@alpha.mentor**


