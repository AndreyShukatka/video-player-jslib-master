# Проект видео плеера
Данный проект сделан по уроку: "Урок 1. Верстаем видеоплеер"

Задачи, которые были решены в данном проекте:
- Сверстайте видеоплеер
- Стилизуйте его с помощью CSS и иконок
- Выложите работу в интернет

![image](https://user-images.githubusercontent.com/106096891/199233379-9a5bd365-6dd3-4234-9ee3-f85c21980684.png)


Посмотреть пример работы плеера можно по [ссылке](https://andreyshukatka.github.io/video-player-jslib-master/)

# Установка
- JS код поставляется в виде файла `player.js`, который лежит в папке `static`, его нужно скачать из этого репозитория.

- Для работы он требует двух библиотек - `jQuery` и `Playable`. Пример подключения:
```html
<script src="https://code.jquery.com/jquery-3.4.1.min.js"></script>
<script src="https://unpkg.com/playable@2.10.3/dist/statics/playable.bundle.min.js"></script>
<script src="player.js"></script>
```
- Далее необходимо в `HTML` файле прописать скрипт подключения видеоплеера:
```
<script type="text/javascript">
  createPlayer({elementId: 'player'});
</script>
```
- Создаём `div` контейнер, в котором уже будет лежать наш плеер:
```
<div id="player" style="width: 800px; height: 600px;">
    <div class="js-video-container" style="width: 100%; height: 100%"></div>
</div>
```
