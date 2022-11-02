# sagirovTGBot

![image](https://user-images.githubusercontent.com/91225680/199411718-f6c08502-76d2-40ec-acf6-8b55493d6526.png)

DOCKER IMAGE https://hub.docker.com/repository/docker/fourzd/sagirovtgbot

TG BOT: https://t.me/sagirovTestbot

Скачайте docker image с помощью данной команды:

``` docker pull fourzd/sagirovtgbot:1.0 ``` 

Затем активируйте образ:

``` docker run fourzd/sagirovtgbot:1.0 ```

Бот запущен!

Скриншот поступает каждые 10 минут по очереди пользователей из БД(sqlite3). Реализована базовая проверка валидности заполнения, однако в случае некорректных данных, бот просто удаляет заявку и переходит к следующей.

Чтобы поменять директорию для скриншотов, необходимо поменять путь SCREENSHOT_DIR = '' в selenium_part.py на желаемый. По умолчанию создается папка screenshots.

Если возникнут вопросы по реализации, я всегда на связи TG @Forzzy 

