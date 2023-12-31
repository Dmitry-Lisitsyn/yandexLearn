# Руководство по проекту

## О проекте
Этот проект создан для изучения основ работы с Git и GitHub. В нем содержится информация о базовых командах Git, работе с репозиториями, коммитами и ветвлением кода.

## Команды Git

### Инициализация репозитория
- `git init`

### Работа с коммитами
- `git add <файл>`: добавить изменения в индекс
- `git commit -m "сообщение"`: создать коммит с сообщением
- `git commit -am "сообщение"`: добавить и закоммитить изменения
- `git push -u origin master`: добавить и закоммитить изменения
- `git log`: посмотреть историю коммитов

### Ветвление
- `git branch`: показать список веток
- `git branch <название>`: создать новую ветку
- `git checkout <название>`: переключиться на другую ветку
- `git merge <название>`: слить ветку с текущей
- 
### Работа с историей коммитов
- `git log`: просмотр истории коммитов
- `git log --oneline`: компактный вывод истории коммитов
- `git log --graph`: отображение истории коммитов в виде графа
- `git log --author="автор"`: фильтрация истории коммитов по автору
- `git log --since="дата"`: вывод коммитов с указанной даты

### Отмена изменений
- `git reset HEAD <файл>`: снять файл с индексации
- `git checkout -- <файл>`: отменить изменения в файле (вернуть к последнему коммиту)
- `git revert <коммит>`: создать новый коммит, отменяющий изменения указанного коммита

### Работа с удаленным репозиторием
- `git remote -v`: показать список удаленных репозиториев
- `git push <удаленный> <ветка>`: отправить изменения на удаленный репозиторий
- `git pull <удаленный> <ветка>`: получить и слить изменения с удаленного репозитория
- `git clone <ссылка на репозиторий>`: склонировать удаленный репозиторий на локальную машину

