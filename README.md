# Обеспечение безопасности веб-приложений

## Содержание

1. [Как выполнять задания](#как-выполнять-задания)
1. [Roadmap](#roadmap)
1. [Лидерборд](./leaderboard.ods)
1. [Документация](#документация)
1. [Полезное](#полезное)

## Roadmap

Все, что находится выше `Мы здесь` должно быть у вас для успешного получения зачета

### 1. Тренажер по терминалу

[Интерактивный тренажер по Unix терминалу](https://www.terminaltutor.com/) [en]
или
[Бесплатный курс по терминалу](https://ru.hexlet.io/courses/cli-basics) [ru]

### 2. Passive Recon

[Презентация](https://ktkv-presentations.github.io/websec-2)

[Задание](https://github.com/41ISR/websec-lab1)

### 3. XSS

[Презентация](https://ktkv-presentations.github.io/websec-3)

[Тренажер](https://xss-game.appspot.com/) 

[Зарегистрироваться здесь](https://play.picoctf.org/)

[Задание](https://github.com/41ISR/websec-lab2)

### 4. Защита сервера

[Презентация](https://ktkv-presentations.github.io/websec-4)

[Задание](https://github.com/41ISR/websec-lab4)

### 5. CSRF

[Презентация](https://ktkv-presentations.github.io/websec-4)

[Задание](https://github.com/41ISR/websec-lab4)

### 6. SQL Injection

[Презентация](https://ktkv-presentations.github.io/websec-6)

[Задание](https://github.com/41ISR/websec-lab6)

### 7. Fix уязвимостей веб приложения

[Задание](https://github.com/41ISR/websec-lab7) _<-- Мы здесь_

## Как выполнять задания

В каждом репозитории описано как выполнять задание. В случае, если не указано, то работать по следующему принципу:

> [!warning]
> Перед началом работы с git не забудьте заменить ключ `~/.ssh/id_ed25519` на ваш ключ

### Как начать выполнять

1. Создайте fork репозитория в организации [41ISR](https://github.com/41ISR) под названием `websec-lab{N}-{last_name}`
    - `N` - номер лабораторной работы
    - `last_name` - ваша фамилия
2. Склонируйте себе этот форк по протоколу SSH
    - `git clone {SSH_ПУТЬ_ДО_ВАШЕЙ_РЕПЫ}`
3. Переключитель на ветку `dev`
    - `git branch dev` - создать ветку (не надо писать, если ветка уже существует)
    - `git checkout dev` - переключиться на ветку `dev`
4. Выполняйте задания в ветке `dev`

### Как работать

_если на вашей машине нет вашей работы, то незабудьте склонировать репозиторий_

1. Если были изменения в репозитории, то нужно стянуть последние изменения `git pull`
2. Выполняйте задания в ветке `dev`
3. Для отправки ветки `dev` на репозиторий GitHub необходимо:
    - Создать коммит `git add .` и `git commit -m "{Что делали}"`
    - Отправить коммит на GitHub `git push -u origin dev`

### Как сдавать

При успешном выполнении задания:

-   Делайте коммит
-   Добавляйте [pull request](#как-делать-pull-request) из `dev` в `main` в **вашем репозитории**
-   Указывайте меня ([ktkv419](https://github.com/ktkv419)) как reviewer

При успешной сдаче задания pull request будет закрыт и последним сообщением перед закрытием реквеста будут написаны мои комментарии и оценка

### Как делать pull request

_Обратите внимание, что это делается в **вашем** репозитории, где вы работали_

1. Откройте вкладку Pull requests

2. Создайте новый PR

3. Перепроверье, что изменения сливаются из ветки `dev` (справа) в ветку `main` (слева) и создайте новый PR

В случае успешной сдачи работы вы увидите мои комментарии по поводу работы, оценку и что реквест был слит с веткой main

## Документация

1. [NCat](https://nmap.org/ncat/guide/index.html) [en]
2. [Metasploit](https://docs.metasploit.com/) [en]
3. [Burp Suite](https://portswigger.net/burp) [en]
4. [Bloodhound](https://bloodhound.readthedocs.io/en/latest/index.html) [en]

## Полезное

1. [awesome pentest](https://github.com/enaqx/awesome-pentest) [en]
2. [Интерактивный тренажер по Unix терминалу](https://www.terminaltutor.com/) [en]
3. [Бесплатный курс по терминалу](https://ru.hexlet.io/courses/cli-basics) [ru]
4. [~~краткий~~ 15 часовой курс как быть умнее всех в группе](https://www.youtube.com/watch?v=3Kq1MIfTWCE)

## Payloads

1. [PayloadsAllTheThings](https://swisskyrepo.github.io/PayloadsAllTheThings/) [en]
1. [XSS-payload-list](https://github.com/payloadbox/xss-payload-list) [en]
