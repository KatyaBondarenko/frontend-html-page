#Задание на вёрстку простой HTML страницы#

##Создание проекта##
1. Сделать в GitHub действие "Fork" для этого проекта, чтобы скопировать проект в свою чётную запись.
2. Установить в систему Git с сайта https://git-scm.com/downloads (если уже не сделано).
3. Установить в систему любой GUI для работы с Git (если уже не сделано). Например https://desktop.github.com/ или https://tortoisegit.org/. Многие редакторы кода имеют плагин или всроенную поддержку Git.
4. *Склонируйте* проект по адресу из **своего аккаунта** локально в файловую систему. 

##Установка##
Начальная установка и настройка проект предпологает несколько шагов, которые должны быть проделаны единожды в начале.
1. Установить NodeJS с сайт http://nodejs.org. Установите последнюю версию.
2. Запустите **/tasks/setup.bat** для автоматической установки всех модулей из открытых репозиториев. Это внешние зависимости необходимые для работы инфраструктуры разработки проект.

Следующие действия можно выполнять каждый раз, когда вы приступаете к работе с проектом.

##Разработка##
Макеты и вспомогательные файлы находятся в папке [psd](./psd).

Исходный код проекта находится в папке **/src/**. Главной страницей является файл **/src/index.html**.

##Запуск##
Просто откройте в любом браузере файл **/src/index.html**.

##Живая перезагрузка##
Чтобы активировать автоматическую перезагрузку HTML-страниц проекта, запустите файл **/tasks/livereload.bat**. После этого нужно запустить или обновить открытую страницу в браузере. Не закрывайте запущенную командную строку до тех пор, пока не нужно прекратить действие живой перезагрузки.

Такая возможность встроена во многие редакторы кода, но данная инфраструктура позволяет сделать живую перезагрузку не зависимо от этого.

##Анализ кода##
Запустите **/tasks/analize.bat**. Это запустит в командной строке статические анализаторы кода HTML и CSS, а так же в конце валидатор HTML по W3C. Многие редакторы имеют благодаря расширениям умеют проверять код на этапе написания. Ищите по названиеям **htmlhint**, **ccslint**, **w3c-validation**.

##Тесты##
Автоматических тестов нет.

