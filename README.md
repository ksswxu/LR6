# LR6
Лабораторная работа №6

После копироваривания репозитория получаю историю всех изменений, сделанных в нем ранее:
![Получение всей истории](./images/all_changes.png "История изменений репозитория")

Затем получаю последнее изменение ветки master:
![Последнее измененея ветки master](./images/master_last_change.png "Последнее изменение ветки master")

Также получаю последнее изменение ветки branch1: 
![Последнее изменение ветки branch1](./images/branch1_last_change.png "Последнее изменение векти branch1")

После чего провожу слияние ветки branch1 и ветки master, получаю конфликт:
![Конфликт слияния ветки branch1 и master](./images/merge_conflict_git.png "Конфликт слияния ветки branch1 и master")

Открываю файл mergefile.txt, вызвавший конфликт:
![Полученный файл mergefile.txt](./images/merge_conflict_mergefile.png "Полученный файл mergefile.txt")

Изменяю его, оставляя текст из обеих веток:
![mergefile.txt с решенным конфликтом слияния](./images/conflict_solved_mergefile.png "mergefile.txt с решенным конфликтом слияния")

Затем провожу коммит и осуществляю слияние веток:
![Коммит и слияние веток master и branch1](./images/merge_conflict_fixed.png "Коммит и слияние веток master и branch1")

Удаляю ветку branch1:
![Удаление ветки branch1](./images/delete_branch1.png "Удаление ветки branch1")

Добавляю в файл new_file.txt строчку:
![Изменение new_file.txt 1](./images/new_file_change_1_text.png "Файл new_file.txt")

Делаю коммит:
![Коммит изменений new_file.txt 1](./images/new_file_change_1_git.png "Коммит изменений файла new_file.txt")

Добавляю вторую строчку:
![Изменение new_file.txt 2](./images/new_file_change_2_text.png "Файл new_file.txt")

Делаю коммит:
![Коммит изменений new_file.txt 2](./images/new_file_change_2_git.png "Коммит изменений файла new_file.txt")

Добавляю третью строчку:
![Изменение new_file.txt 3](./images/new_file_change_3_text.png "Файл new_file.txt")

Делаю коммит:
![Коммит изменений new_file.txt 3](./images/new_file_change_3_git.png "Коммит изменений файла new_file.txt")

Провожу откат последнего коммита с помощью git revert, появляется:
![Откат последнего коммита](./images/revert_msg.png)

Выхожу командой wq и возвращаюсь в консоль:
![Откат последнего коммита 2](./images/git_revert.png "Откат последнего коммита")

Итоговая история коммитов:
![История коммитов](./images/full_commit_hystory.png "История коммитов")