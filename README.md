#MyGit Learning
Привет, это тестовый проект для обучения Git.  
По заданию нужно создать файл с ***MarkDown*** разметкой.  
Я перечислю несколько команд, которые я узнал.
---
##Команды
1. git init
2. git add (. or filename.ext)
3. git commit -m "Комментарий"
4. git log
5. git remote add (name: origin) (URL: https://github.com/.../projname.git)
6. git branch -M main
7. git push -u (name: origin) (branch: main or ~~master~~)

Также приведу оформленную ссылку на github.com: [Вот эта ссылка](https://github.com/ "Да-да, это ссылка на GitHub")

Надеюсь Вы оцениваете мою работу неплохо
- [ ] Отлично
- [ ] Хорошо
- [x] Неплохо
- [ ] Плохо

Файл HEAD находится в папке .git и указывает на последний коммит (самый новый).
Точнее файл содержит ссылку на служебный файл в котором содержится хэш последнего коммита.
Слово HEAD в коммандах заменяет хэш последнего коммита.

Жизненный цикл файлов и статусы:
untracked + git add = tracked + staged
staged + git commit = tracked
staged (v1) + changed (v2) = tracked + staged (v1) + modified (v2)
tracked + change = modified
staged + modified = tracked + staged
modified + git add = staged
staged + push = staged + fetch + merge = tracked