# Телеграм Бот для подготовки к собеседованию по фронтенд-разработке

Бот написан на **Node JS** с использованием библиотек:
* [grammY](https://grammy.dev/)
* [random-js](https://www.npmjs.com/package/random-js)
* [dotenv](https://www.npmjs.com/package/dotenv)
* [nodemon](https://www.npmjs.com/package/nodemon)
### Инструкция по запуску кода локально на личном ПК

1. Склонировать репозиторий
```
git clone https://github.com/arseniypom/intreview-bot.git
```
ИЛИ
скачать zip-архив и распаковать его

2. Открыть папку `intreview-bot` в редакторе кода, запустить терминал и выполнить команду для установки зависимостей
```
npm i
```
3. Создать в корне проекта файл `.env` и вставить туда ключ от своего бота (полученный от BotFather по инструкции из [видео](https://youtu.be/BQr9u6Bb_mE?si=r1ecn6P3U4r7tzrw&t=170))
```
BOT_API_KEY=9876543210:AbCdEfGhIjKlMnOp-QrStUvWxYz1234567890
```