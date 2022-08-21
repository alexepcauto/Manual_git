# **Памятка - инструкция по Git**
---
![GIT](image_git.JPG)

## Инициализация

    git init

## Простмотр состояния

    git status

## Добавление файлов и директорий

    git add
        git add .

## Отправка изменений состояний

    git commit -m -a 'Message........'
        git commit -am 'Message.......'

## Добавление ветки

    git branch branch_name

## Переключение на ветку

    git checkout branch_name

## Добавление ветки и переключение в одной строке

    git checkout -b branch_name

## Просмотр лога

    git log
        git log --all
            git log --oneline --all

## Просмотр и сравнение изменений (commit)

    git diff
        git diff hash#1 hash#2

# Запись кода

```html

# HTML code
<p><a href = 'https://google.com'>Googl</a></p>
<a href="https://developer.mozilla.org">MDN</a>

```
# Откладывание изменений

    git stash
