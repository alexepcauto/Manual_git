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

## Добавление ветки и переключение в одну строчку

    git checkout -b branch_name

## Просмотр лога

    git log
        git log --all
            git log --oneline --all

## Просмотр и сравнение изменений (commit)

    git diff
        git diff hash#1 hash#2



Some Markdown text with <span style="color:blue">some *blue* text</span>.

<font color='yellow'>test blue color font</font>

<span style="color:red">text in red</span>

# Заголовок

- Список
  1. Вложенный список

      ```html
      <div>Вложенная вёрстка</div>
      ```

      ```js
      // Вложенный JS
      const sum = (a, b) => {
        return a + b;
      }
      ```
  2. Второй элемент


Выше - разделитель для заданий. Итоговый код прогоняется через типограф, поэтому пробелы и тире в тексте правильные. Также готовый HTML код прогоняется через бьютифаер, чтобы не было каши.

| Таблица       | это           | круто |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |


