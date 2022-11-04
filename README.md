# LR6
## Лабораторная работа №6

Создан аккаунт на GitHub и сделана копия исходного репозитория в личное хранилище

![](https://github.com/0-kira-0/LR6/blob/master/screens/1.png)
![](https://github.com/0-kira-0/LR6/blob/master/screens/2.png)

Установлен Git

![](https://github.com/0-kira-0/LR6/blob/master/screens/3.png)

Настроен клиент Git (введено имя пользователя и email) с помощью команд `git config --global user.name <имя>` и `git config --global user.email <почта>`

![](https://github.com/0-kira-0/LR6/blob/master/screens/4.png)
![](https://github.com/0-kira-0/LR6/blob/master/screens/5.png)

Клонирован личный удалённый репозиторий на компьютер с помощью `git clone`

![](https://github.com/0-kira-0/LR6/blob/master/screens/6.png)

Добавлен файл через интерфейс GitHub

![](https://github.com/0-kira-0/LR6/blob/master/screens/7.png)

Изменения подтянуты в локальный репозиторий (переход в локальный репозиторий - `cd LR6`, "подтягивание" - `git pull`)

![](https://github.com/0-kira-0/LR6/blob/master/screens/8.png)

> Далее работа продолжена локально

Получена история операций ветки **master** с помощью `git log`

![](https://github.com/0-kira-0/LR6/blob/master/screens/9.png)

Просмотрены последние изменения ветки **master** (3 последних) с помощью `git log -p -3`

![](https://github.com/0-kira-0/LR6/blob/master/screens/10.png)

Совершён переход на ветку **branch1** с помощью `git checkout branch1`

![](https://github.com/0-kira-0/LR6/blob/master/screens/11.png)

Просмотрена история операций и последних трёх изменений ветки **branch1** (`git log` и `git log -p-3`)

![](https://github.com/0-kira-0/LR6/blob/master/screens/12.png)
![](https://github.com/0-kira-0/LR6/blob/master/screens/13.png)

Для слияния веток в одну переходим в ветку **master** (`git checkout <ветка>`) и производим слияние веток (`git merge branch1`)
> Переход на ветку **master** нужен т.к. по заданию необходимо получить слияние в ветку **master**

![](https://github.com/0-kira-0/LR6/blob/master/screens/14.png)

Видим, что появился конфликт.
Чтобы узнать состояние проекта используем `git status`.
По полученным данным понимаем, что слияние не происходит т.к. есть "несоединённая часть". Разрешаем конфликт по данной инструкции (`git add <file>`)

![](https://github.com/0-kira-0/LR6/blob/master/screens/15.png)

Проверяем готовность к дальнейшему слиянию с помощью команды `git status`. Видим, что конфликты разрешены, но всё ещё идёт процесс слияния

![](https://github.com/0-kira-0/LR6/blob/master/screens/16.png)

Для завершения процесса необходимо прописать команду `git commit -m`
> `-m` нужно, чтобы можно было написать небольшой комментарий сразу в консоли

![](https://github.com/0-kira-0/LR6/blob/master/screens/17.png)

Удаление побочной ветки после слияния с помощью `git branch -d <ветка>`

![](https://github.com/0-kira-0/LR6/blob/master/screens/18.png)

Проверка правильности выполнения с помощью `git branch`

![](https://github.com/0-kira-0/LR6/blob/master/screens/19.png)

Изменения проведены и зафиксированы (созданы 2 текстовых файла), используемые команды:
- `echo текст_изменения > файл_для_сохранения`
- `git add <файл>`
- `git commit -m "изменение n"`

![](https://github.com/0-kira-0/LR6/blob/master/screens/20.png)
![](https://github.com/0-kira-0/LR6/blob/master/screens/21.png)

История операций (`git log -3`)

![](https://github.com/0-kira-0/LR6/blob/master/screens/22.png)

Сделан откат коммита (`git reset HEAD~1`) и проверка с помощью истории изменений (`git log`)

![](https://github.com/0-kira-0/LR6/blob/master/screens/23.png)

Создана ветка для отчёта **branch2** (`git branch branch2`)

![](https://github.com/0-kira-0/LR6/blob/master/screens/24.png)

Окно редактора (Notepad)

![](https://github.com/0-kira-0/LR6/blob/master/screens/25.png)