# Проект вёрстки видеоплеера

[Демо ссылка](https://lypavel.github.io/dvmn-player-layout/)

![Скриншот видеоплеера](https://github.com/lypavel/dvmn-player-layout/assets/157053921/e2de394b-59f2-4f70-ae64-b32466174b3b)

## Установка

1. Установите [Python 3.10.12](https://www.python.org/downloads/release/python-31012/).
2. Создайте, если нужно, виртуальное окружение
    ```sh
    python3 -m venv venv
    ```
3. Установите необходимые зависимости
    ```sh
    pip install -r -requirements.txt
    ```

## Использование

Запустите сайт с помощью команды

```sh
livereload . --host <HOST> --port <PORT>
```
где<br>
`<HOST>` - хост сайта<br>
`<PORT>` - порт сайта

Перейдите по адресу `http://<HOST>:<PORT>` для ознакомления с видеоплеером.

Эти две настройки можно опустить, тогда сайт запустится на стандартном хосте и порте: `127.0.0.1:5500`.

***
Код написан в образовательных целях на онлайн-курсе для веб-разработчиков [Devman](dvmn.org).
