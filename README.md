# git-shortcuts

## Основные шорткаты Git для новичков

### Настройка

`git config --global user.name "Твое Имя"` — установить имя
`git config --global user.email "email@example.com"` — установить email

### Создание репозитория и связь с GitHub

`git init` — создать репозиторий
`git remote add origin https://github.com/твой_логин/репозиторий.git` — связать с GitHub
`git remote -v` — проверить связь

### Добавление файлов в индекс

`git status` — проверить статус
`git add файл.txt` — добавить файл
`git add .` — добавить всё
`git add --all` — добавить всё

### Создание коммитов

`git commit -m "Сообщение коммита"` — создать коммит
`git commit -a -m "Сообщение"` — добавить и коммитнуть

### Отправка на GitHub

`git push origin main` — отправить коммиты
`git push -u origin main` — отправить впервые

### Получение обновлений с GitHub

`git pull origin main` — скачать и объединить
`git fetch origin` — посмотреть изменения

### Проверка состояния

`git log --oneline` — список коммитов
`git diff` — незакоммиченные изменения
`git diff --staged` — изменения в индексе

