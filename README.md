# Описание нашего проекта
## GU_3515
## Работа с удаленными репозиториями

### Предложения по дополнению инструкции git от Кудряшова Максима

Чтобы копировать внешний репозитория на свой ПК можно командой _git clone (адрес репозитория, который копируем на свой ПК)_

1. Команда **git clone** составная: она не только загружает все изменения, но и пытается слить все ветки на локальном компьютере и в удаленном репозитории.

2. **git push**

Отправить свою версию репозитория во внешний репозиторий поможет команда _git push_. При первом ее использовании нужна авторизация.

+ Эта команда позволяет отправить нашу версию репозитория на внешний репозиторий. ТРЕБУЕТ АВТОРИЗАЦИИ на внешнем репозитории.

3. **git pull**

+ Эта команда позволяет скачает все из текущего репозитория и автоматически сделать merge с нашей версией.

***

### Как настроить совместную работу

Для добавления нового удаленного репозитория на GitHub, в командной строке нужно прописать:

_git remote add origin (адрес репозитория)_

_git branch -M main_

_git push -u origin main_

1. Создать аккаунт на GitHub.com
2. Создать локальный репозиторий
3. "Подружить" ваш локальный и удаленный репозитории. _GitHub при создании нового реопзитория подскажет, как это можно сделать_
4. Отправить (push) ваш локальный репозиторий в удаленный (на GitHub), при этом, возможно, вам нужно будет авторизоваться на удаленном репозитории
5. Провести изменения "с другого компьютера"
6. Выкачать (pull) актуальное состояние из удаленного репозитория

***

### Как сделать pull request

* Делаем **fork** (ответвление) репозитория
* Делаем _git clone_ **СВОЕЙ** версии репозитория
* Создаем новую ветку и в нее в носим свои изменения
* Фиксируем изменения (делаем коммиты)
* Отправляем свою версию в свой GitHub
* На сайте GitHub нажимаем кнопку _pull request_