[![Build status](https://ci.appveyor.com/api/projects/status/w6ylbt7l34kfhhw0/branch/main?svg=true)](https://ci.appveyor.com/project/Aleksandr-Suchugov/messenger-front-end/branch/main)

# AHJ Diploma

## Описание проекта

### Реализованы обязательные функции:

* сохранение в истории ссылок и текстовых сообщений;
![](./src/assets/jpg/history.jpg)
* ссылки (`http://` или `https://`) должны быть кликабельны и отображаться, как ссылки;
![](./src/assets/jpg/hyperlinks.jpg)
* сохранение в истории изображений, видео и аудио (как файлов) — через Drag & Drop и через иконку загрузки;
![](./src/assets/jpg/drag_and_drop.jpg)
* скачивание файлов на компьютер пользователя;
![](./src/assets/jpg/download_option.jpg)
* ленивая подгрузка: сначала подгружаются последние 10 сообщений, при прокрутке вверх подгружаются следующие 10 и т. д.
![](./src/assets/jpg/lazy_history.jpg)

### Реализованы дополнительные функции:

* синхронизация: если приложение открыто в нескольких окнах или вкладках, то контент должен быть синхронизирован;
![](./src/assets/jpg/2nd_client.jpg)
* запись и воспроизведение видео и аудио, используя API браузера;
![](./src/assets/jpg/audio_recording.jpg)
* отправка геолокации по клику на кнопку в поле ввода;
![](./src/assets/jpg/geolocation.jpg)
* отправка команд боту:
  - '/get usd' бот присылает действующий курс Доллара к Рублю;
  - '/get eur' бот присылает действующий курс Евро к Рублю;
  - '/get weather' бот присылает прогнозом погоды по координатам клиента;
![](./src/assets/jpg/bot_get_comands.jpg)
* поддержка смайликов (emoji).
![](./src/assets/jpg/emoji.jpg)