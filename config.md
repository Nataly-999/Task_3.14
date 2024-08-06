[< к содержанию](./readme.md)

## git config

**git config** - Представляет собой базовую настройку окружения.

Чтобы настроить окружение необходимо ввести следующие команды, подставив свои данные *(имя пользователя и email)*:

```bash=
  git config --global user.name "Your Name"
  git config --global user.email "you@example.com"
```
Проверить настройки можно с помощью флага *--list* :

```bash=
  git config --list
```
Пример результата выполнения команды:

![config list](./assets/config%20list.png)
