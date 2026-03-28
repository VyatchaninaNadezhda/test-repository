# Все что я узнала про Git
1. Создала новую папку test-repository локально и добавила туда через командную строку файл readme.md 
cd ~/dev/test-repository 
touch readme.md
2. Добавила этот файл в Git и закоммитила
Git add readme.md
Git commit -m 'Мой комментарий'
3. [Создала новый репозиторий test-repository на GitHub](https://github.com/VyatchaninaNadezhda?tab=repositories)
4. Так как SSH уже созданы и переданы в настройки на GitHub, сразу связала удаленный репозиторий с локальным
 cd ~/dev/test-repository
$ git remote add origin git@github.com:%ИМЯ_АККАУНТА%/first-project.git 
5. Добавила информацию в readme.md файл
6. Сохранила
7. Закоммитила изменения
8. Запушила изменения в readme.md файле на GitHub
Git push
9. Проверила на GitHub отображение readme.md файла и его содержания