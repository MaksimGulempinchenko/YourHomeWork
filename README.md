# Добрый день, уважаемые студенты! 
  При выполнении данной работы от вас требуется дополнить мой репозиторий, добавив в него свой файл с инструкцией по работе с git. Помните, что добавление файла - такой же процесс изменения репозитория, как и изменения внутри конкретных файлов и не пугайтесь этого :)

  P.S. Называйте добавляемые файлы своими фамилиями(только на английской раскладке), чтобы мне было проще их идентифицировать. И не забудьте сделать скрин окна с pullrequest, на сайт GB необходимо отослать именно этот скрин, чтобы работа была окончательно завершена.

  P.P.S. Не забывайте, что отправляем на pullrequest мы побочные ветки!

  # Иструкция по работе с Git ![git](git.jpeg)

## Команды :


* *git init* - команда, инициализурующая репозиторий в задоной директории.
 * *git cd* - команда, переключения между папками  
 * *git clear* - команда, удаляет всю рабочую зону терминала 
 * *git checkout* - указать имя комита для перехода к нему, переключение между веток       
 * *git add* - добавить файл для отслеживания Git
 * *git add* - добавить файл для отслеживания Git
 * *git log* - просмотреть все комиты
 * *git diff* - позволяет посмотреть измененную разницу в комитах
 * *git branch* - просмотреть в какой ветке находимся
     * git branch (имя ветки) - созать новую ветку
* *git merge* - слить ветки (добавить ветку второстепенную в ветку master)
* git branch -d(название ветки) - удаляем ветку (после слияния с master)
   * git -D удаление моментальное
* git log --grup - просмотр всех комитов
* .gitignor - файл для игнорирования элементов
* git commit - запись (сохранение) текущего изминения  в репозитории

## Работа с документом :

 1. Внесение изменений 
 2. сохранить эти изменения CTRL + S
 3. Добавить файл "add" 
 4. фиксировать изменения "commit"

 ##      Ссылка на основы git :
 
**[часть 1 хабра](https://habr.com/ru/post/541258/)**

**[часть 2 хабр](https://habr.com/ru/post/542616/)**

## 2 часть :

### Создание веток :

* *git branch* - просмотреть в какой ветке находимся, отоброжение всех созданных веток

* git branch (имя ветки) - созать новую ветку


### Слияние веток :

*git merge* <branch_name> - слить ветки (добавить ветку второстепенную в ветку master)

__*NB*__ - перед слияянием веток, нужно убедиться, что базавая и принемаемая ветка указанны верно. 
### Конфликты :

# ДЗ 
 * создаем ветку для слияния fast - forward 
 1 ветка для слияния со второй 
уникальный камит для мастера
ветка 2 
готова к слиянию с веткой 1
сливаем ветку с мастер
для fast forward
сливаем с мастер
сливаем с мастер
меняем строку в мастере
оставляем оба варианта
этот вариант остается в мастере 
и для закрепления auto merge 
уникальный каммит 