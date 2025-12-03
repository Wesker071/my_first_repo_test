# My First Project

## Описание проекта
Это пример проекта, который демонстрирует, как выглядит файл `readme.md`.

### Основные команды в git

1. Настройка и инициализация
bash
git config --global user.name "Твое Имя"
git config --global user.email "твоя@почта.com"
git init                    # создать новый репозиторий
git clone <ссылка>          # склонировать чужой репозиторий

2. Основной рабочий цикл (90% времени)
bash
git status                  # что изменилось? (самая частая команда!)
git add <файл>             # добавить файл в индекс (staging)
git add .                   # добавить ВСЕ изменения
git commit -m "сообщение"   # зафиксировать изменения
git push                    # отправить на GitHub
git pull                    # забрать с GitHub

3. Просмотр истории
bash
git log                     # история коммитов
git log --oneline           # компактная история
git diff                    # что изменилось в файлах
git show <коммит>          # показать конкретный коммит

4. Ветки (branches)
bash
git branch                  # показать все ветки
git branch <имя>           # создать новую ветку
git checkout <имя>         # переключиться на ветку
git checkout -b <имя>      # создать и переключиться
git merge <ветка>          # слить ветки
git branch -d <имя>        # удалить ветку

5. Работа с удаленным репозиторием (GitHub)
bash
git remote add origin <url> # привязать к удаленному репо
git remote -v               # показать привязанные репо
git push -u origin main     # первый пуш (запомнить связь)
git push origin <ветка>     # отправить конкретную ветку
git fetch                   # проверить изменения

