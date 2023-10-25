
1. Для перемещения по директориям используется команда *cd*
```bash
$ cd
```
2. Чтобы перейти на уровень выше, в родителькую папку, используется команда *cd ..*
```bash
$ cd ..
```
3. Чтобы перейти в домашнюю директорию, используется команда *cd ~*
```bash
$ cd ~
```
4. Чтобы перейти в корневую директорию, используется команда *cd /*
```bash
$ cd /
```
5. Чтобы узнать текущую (рабочую) директорию используется команда *pwd*
```bash
$ pwd
``` 
6. Чтобы просмотреть содержимое директории используется команда *ls*
```bash
$ ls
``` 
7. Чтобы просмотреть все скрытые элементы директории, применяется команда *ls -a*
```bash
$ ls -a
```
8. Чтобы создать файл, используется команда *touch*
```bash
$ touch %Имя_Файла%.Расширение
```
9. Чтобы создать директорию, используется команда *mkdir*
```bash
$ mkdir %Имя_Директории%
```
10. Чтобы создать несколько директорий сразу, применяется команда *mkdir -p*
```bash
$ mkdir -p %Имя_Директории1% %Имя_Директории2%
```
11. Чтобы скопировать файлы, применяется команда *cp* 
```bash
$ cp %что_копируем% %куда_копируем%
```
12. Чтобы переместить файл из одной директории в другой, используется команда *mv*
```bash
$ mv %что_перемещаем% %куда_перемещаем%
```
13. Чтобы просмотреть содержимое файла, используется команда *cat*
```bash
$ cat %имя_файла%
```
14. Чтобы скопировать содержимое файла в буфер обмена, используется команда *clip*
```bash
$ clip < %имя_файла%
```
15. Чтобы удалить файл, применяется команда *rm*
```bash
$ rm %имя_файла%
```
16. Чтобы удалить директорию, применяется команда *rmdir*
```bash
$ rmdir %имя_директории%
```
17. Чтобы удалить директорию, в которой что-то содержится, используется команда *rm -r* 
```bash
$ rm -r %имя_папки%
```
18. Чтобы выполнить несколько команд друг за другом, применяется *&&*
```bash
$ %команда1% && %команда2%
```
19. С помощью ↑↓ можно перемещаться по использованным ранее командам
20. Tab применяется для автозаполнения или предложения вариантов команд
21. / и ~ позволяют перемещаться к корневой и домашней директориям 
22. Для инициализации локального репозитория, испольуется команда *git init*
```bash
$ git init
```
23. Чтобы разгитить папку, используется команда *rm -rf git*
```bash
$ rm -rf .git
```
24. Чтобы проверить состояние репозитория, используется команда *git status*
```bash
$ git status
```
25. Чтобы подготовить файл к сохранению в репозитории, используется команда *git add*
```bash
$ git add %имя_файла%
```
26. Чтобы подготовить все файлы к сохранению, используется команда *git add --all*
```bash
$ git add --all
```
27. Чтобы добавить в репозиторий текущую папку со всем содержимым, используется команда *git add .*
```bash
$ git add .
```
28. Чтобы совершить коммит, используется комадна *git commit -m*
```bash
$ git commit -m "Сообщение"
```
29. Чтобы просмотреть историю коммитов, используется команда *git log*
```bash
$ git log
```
30. Чтобы вызвать сокращённую историю  коммитов, используется команда *git log --oneline*
```bash
$ git log --oneline
```
31. Чтобы связать локальный репозиторий с удалённым, используется команда *git remote add*
```bash
$ git remote add origin git@github.com:%ИМЯ_АККАУНТА%/first-project.git 
```
32. Чтобы убедиться, что репозитории связаны, используется команда *git remote -v*
```bash
$ git remote -v
```
33. Чтобы создать ssh-ключ, используется команда *ssh-keygen*
```bash
$ ssh-keygen -t ed25519
```
34. Чтобы проверить правильность ssh-ключа, используется команда *ssh -T git@github.com*
```bash
$ ssh -T git@github.com
```
35. Чтобы загрузить данные с локального репозитория на удалённый, используется команда *git push*
```bash
$ git push -v origin master/main
```
36. Статусом *untracked* помечается файл, о существовании которого Git знает, но не следит за изменениями в нём. Этот статус — противоположность tracked, в который попадают все файлы, отслеживаемые Git. Файл переходит в статус *staged* после выполнения *git add*. Статус *modified* означает, что файл был изменён


