# Инструкция по GIT и Linux командам?

## Работа с Linux

1. Чтобы создать папку, пишем mkdir "Навзание папки".
2. Чтобы проверить целосность папки, пишем ls -la.
3. Чтобы тронуть объект (то-есть изменить последнюю дату открытия и изменения), пишем touch.
4. Чтобы перейти в содержимое папки, пишем cd.
5. Чтобы перейти в Vim, пишем vim.
6. Чтобы отредактировать файл, пишем vim "Название файла".

### Cокращения в Linux
1. Ls-"List Files"
2. L-"list"
3. La-"List all"
4. A-"all"

## Работа с Vim
1. Чтобы стереть,нажимаем Backspace.
2. Чтобы выйти из Vim,нажимаем ECS+:+q.
3. Чтобы создать заголовок,пишем #"Название заголовка",в завистимости от размеров заголовка пишем ##,и т.д. и т.п.,чем больше мы пишем "#" тем меньше заголовок(Максимум можем быть 6 "#").
4. Чтобы сохрнаить измения в Vim,пишем ECS+W.

### Режимы в Vim
1. Основной-**Предупреждение,в основном режмие можно работать только в английской расскалдке*Это режимв котором нельзя редактировать файл,а только *Выбирать другие режимы**
2. Вставка-В этом режиме можно редактировать текст.Для перехода в этот режим нажмите в Основном режмие кнопку **"I"**.

## Работа с GIT
1. Чтобы открыть список настроек пишем, git config --list

### Работа с индексом

1. Чтобы добавить файл в индекс, пишем git add "Название файла".
2. Чтобы удалить файл из индекса, пишем git rm "Название файла".
3. Чтобы удалить файл из индекса, но отсавить в рабочей директории, пишем git rm --cached "Название файла".

### Работа с ветками
Чтобы создать определённую ветку, пишем git checkout -b "Название ветки".
Чтобы перейти на опрделённую ветку,пишем git checkout "Название ветки".
Чтобы включить изменения из другой ветки в текущую, пишем git merge "Навзание ветки".
## Работа с Markdown
1. Маркированный список
  - *Первый элемент
  - +Второй элемент
  - -Третий элемент
  - **"Текст"**-для написания жирным шрифтом.
  - ____(4 пробела)-для создания подблока.
  - ____*(4 пробела)-для создания подопункта.
  - *"Текст"*-для написания курсивом.
    
