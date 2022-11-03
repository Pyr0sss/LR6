# Лабораторная работа №6
> Система контроля версий
***

### Установлен и настроен клиент Git, введено имя пользователя и адрес электронной почты.

![](screens/sc1.png)
![](screens/sc2.png)

Рисунок 1

### На личный компьютер клонирован удаленный репозиторий

![](screens/sc3.png)

Рисунок 2

### Подтянуты изменения в локальный репозиторий

![](screens/sc4.png)

Рисунок 3

### Получена история операций для каждой из веток. Осуществлен переход между ветками.

![](screens/sc5.png)
![](screens/sc6.png)
![](screens/sc7.png)

Рисунок 4

### Осуществлено слияние в ветку master. Конфликт разрешен при помощи операторов mergetool и vimdiff.

![](screens/sc8.png)
![](screens/sc9.png)

Рисунок 5

### Получен статус изменений. Результат слияния сохранен и откоммичен.

![](screens/sc10.png)
![](screens/s11.png)

Рисунок 6

### Удалена побочная ветка.

![](screens/sc12.png)

Рисунок 7

### Создан и подвержен изменениям новый файл. Данные зафиксированы.

![](screens/sc13.png)
![](screens/s14.png)

Рисунок 8

### Зафиксирован лог последних изменений.

![](screens/sc15.png)

Рисунок 9

### Сделан откат коммитов.

![](screens/sc16.png)

Рисунок 10

### Создана новая ветка для отчета.

![](screens/sc17.png)

Рисунок 11

### Отчет заполнен в простейшем текстовом редакторе.

![](screens/sc18.png)

Рисунок 12

### Изменения в отчете поэтапно зафиксированы.

![](screens/sc19.png)

Рисунок 13

### Получена история операций в форматированном виде (сокращённый хэш + дата + имя автора + комментарий).

![](screens/sc20.png)

Рисунок 14

***
### Лог команд

$ cd C:/Lenovo/Users/LR6
$ git clone https://github.com/Pyr0sss/LR6.git
$ git pull
$ git log
$ git checkout branch1
$ git checkout master
$ git merge branch1
$ git mergetool
$ git status
$ git add .
$ git commit -m 'Merging'
$ git branch -d branch1
$ git branch
$ git commit -m 'New file'
$ git commit -m 'Modified file'
$ git reset --hard HEAD~1
$ git reset --hard HEAD~2
$ git checkout -b 'Otchet'
$ git log --pretty="%h %ad %ch %s"
