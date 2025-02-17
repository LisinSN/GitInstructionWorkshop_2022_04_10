# Инструкция по работе с git

## Что это и для чего нужна система контроля версий?

*Система контроля версиями позволяет хранить несколько версий одного и того же документа, при необходимости возвращаться к более ранним версиям, определять кто и когда сделал то или иное изменение, и многое другое*

### Что такое система контроля версий?

## Система контроля версий — это система, записывающая изменения в файл или набор файлов в течение времени и позволяющая вернуться позже к определённой версии.

### Для чего нужна система контроля версий

Система контроля версий позволяет отслеживать историю изменений файлов, создавать комиты для более удобного ориентирования в истории изменеий.

    А также система контроля версий позволяет экономить место, сохраняя только измениния в версии файла.

Самой распространённой программой с ипользования системой контроля версий является GIT

![Git](./cover.png)

## Установка git и VSCode на ваш ПК.

В случае, если вы учитесь на работе и у вас нет прав устанавливать на компьютер сторонние программы, но качать из Интернета возможно. 
Вы можете скачать так называемую "Портативную версию" программ. 
1. В поисковике необходимо задать GitPortable и Vscode-portable 
2. Скачать архивы программ
3. Распаковать в доступную вам папку на компьютере. Я ставил прямо на рабочий стол. Обязательно название папки латиницей, например: learn (путь к директории C:\Users\LisinSN\Desktop\learn)
* в этом случае, управлять через терминал ВСКода будет невозможно. Следует пользоваться терминалом GitBashPortable, который в коневой папке Гита. 
* папки занятий создавайте здесь: C:\Users\LisinSN\Desktop\learn\GitPortable\Data\home 
* через ВСКод папка открывается свободно и редактируется точно так же, как в лекции. 
** НЕ ЗАБЫВАЙТЕ СОХРАНЯТЬСЯ **


### Установка VSCode на ваш ПК.
**Чтобы установить Visual Studio Code, необходимо выполнить следующие действия:**

1. В браузере перейти по [адресу](https://code.visualstudio.com/download).
2. Скачайте версию для Вашей операционной системы (Windows / MacOS, Linux).
3. После скачивания, запустите установщик. Это займёт всего одну минуту!
4. При установке можно использовать стандартные настройки, предложенные установщиком. 
5. После завершения установки можно приступать к работе!

### Установка git на ваш ПК

#### Первая настройка git

## Создание и базовая работа с локальным репозиторием.

#### Создание репозитория
Для того, чтобы добавить версионность к созданной папке, и создать в ней локальный репозиторий, для этого необходимо открыть окно терминала в этой папке и написать команду *git init*. Тогда Ваша папка станет репозиторием, и в ней появится скрытая папка .git
#### Добавление файлов в репозиторий
Добавить версионность к файлу, находящемуся в папке-репозитории, можно с помощью команды *git add*. Пишется она следующим образом *git add <название файла>*
#### Создание коммитов
Для того, чтобы зафиксировать изменения в текущей версии используется команда *git commit*. Используется она следующим образом: *git commit -m "<Сообщение к коммиту>"*. Сообщение к коммиту писать **ОБЯЗАТЕЛЬНО**


### Что такое репозиторий и инструкция по созданию локальных репозиториев.

 **Репозиторий - это хранилище файлов, которое поддерживает версионность файлов**
 *Чтобы создать локальный репозиторий, необходимо создать папку, зайти в нее через консоль и инициализировать репозиторий с помощью команды `git init`*

### Базовая работа с локальным репозиторием


## Ветки. Локальная работа с ветками в git.

### Что такое ветки и для чего они нужны при работе с системой контроля версий.

### Базовая работа с ветками в git.

## Работа с удаленными репозиториями.

### Что такое удаленный репозиторий и для чего он нужен

### Базовая работа с удаленными репозиториями GitHub

## Совместная работа над проектом (fork, pull request)

### Как строится и для чего нужна совместная работа в системах контроля версий

### Инструкция по созданию pull request

## Книги и полезные ссылки по изучению git.

## Альтернативные системы контроля версий.
