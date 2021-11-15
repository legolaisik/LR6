# LR6
Лабораторная работа №6

1. Создаем аккаунт на GitHub и делаем копию репозитория преподавателя в личное хранилище
2. Устанавливаем Git и настраиваем клиент
 ![1]( https://github.com/legolaisik/LR6/tree/report/Screenshots/1.jpg)
4. Клонируем репозиторий на компьютер
 ![2]( https://github.com/legolaisik/LR6/tree/report/Screenshots/2.jpg)
6. Добавляем файл на GitHub и подтягиваем его на компьютер
 ![3]( https://github.com/legolaisik/LR6/tree/report/Screenshots/3.jpg)
8. Получаем историю операций для каждой ветки
 ![4]( https://github.com/legolaisik/LR6/tree/report/Screenshots/4.jpg)
10. С помощью GitHub Desktops объединяем ветки, исправляя конфликт, и удаляем ненужную ветку
 ![5]( https://github.com/legolaisik/LR6/tree/report/Screenshots/5.jpg)
12. Делаем изменение в файле и выполняем коммит
 ![6]( https://github.com/legolaisik/LR6/tree/report/Screenshots/6.jpg)
14. Делаем хард откат
 ![7]( https://github.com/legolaisik/LR6/tree/report/Screenshots/7.jpg)
16. Создаем ветку для отчета
 ![8]( https://github.com/legolaisik/LR6/tree/report/Screenshots/8.jpg)
18. Загружаем ветку в удаленный репозиторий
 ![9]( https://github.com/legolaisik/LR6/tree/report/Screenshots/9.jpg)
20. Лог команд
 git clone https://github.com/legolaisik/LR6
 git pull origin master
 git reflog –-all
 git add .
 git commit –m “Add something”
 git push
 git reset –-hard HEAD
 git checkout –b report
 git branch
 git push –set-upstream origin report
31. История коммитов
 commit e660282e7e248b63be893d9005816093aa46ce24 (HEAD -> report, origin/report, origin/master, origin/HEAD, master)
 Author: Zhdanov Daniil <68649279+legolaisik@users.noreply.github.com>
 Date:   Mon Nov 15 14:03:02 2021 +0300

    Add something

 commit bb968e3342a450ae585df3ac61e22bc8518a3b54
 Merge: 5b71641 0f9f50d
 Author: Zhdanov Daniil <68649279+legolaisik@users.noreply.github.com>
 Date:   Mon Nov 15 13:38:28 2021 +0300

    Merge branch 'branch1'

 commit 5b71641881d6d121ab601cb2442cf487c3b64b4f
 Author: Zhdanov Daniil <68649279+legolaisik@users.noreply.github.com>
 Date:   Mon Nov 15 12:00:27 2021 +0300

    Create NewFile

 commit 921f53b8d0cebf542c791cf31f04e9b792f385a4 (upstream/master)
 Author: Kurtyanik <45309985+Kurtyanik@users.noreply.github.com>
 Date:   Sat Nov 21 20:09:49 2020 +0300

    Обновление информации

 commit 0f9f50db68a6983b47398017545532cd0f992846 (upstream/branch1)
 Author: Kurtyanik <45309985+Kurtyanik@users.noreply.github.com>
 Date:   Sat Nov 21 20:08:33 2020 +0300

    Заполнил файл

 commit c08a654a63cfc3a7146b2b7015884d9020f5cbf5
 Author: Kurtyanik <45309985+Kurtyanik@users.noreply.github.com>
 Date:   Sat Nov 21 20:02:16 2020 +0300

    Файл создан пустым

 commit 3c6e9131bb47ed6009c28226afb0535c7f6d5964
 Author: Kurtyanik <45309985+Kurtyanik@users.noreply.github.com>
 Date:   Sat Nov 21 19:58:20 2020 +0300

    Initial commit

