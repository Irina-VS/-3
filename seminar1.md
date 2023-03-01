# Создаем тутроиал по Git

## Как создать новый репозиторий

Что бы создать новый репозиторий используйте следующую команду:
```
git init
```

## Как добавить файл на отслеживание 

Чтобы добавить файл на отслеживание используйте следующую команду:
```
git add "название файл.расширение"
```

## Как получить информацию от git о его текущем состоянии

Что бы git выдал информацию о текущем состянии используйте следующую коанду:
```
git status
```

## Как вывести на экран истории всех коммитов с хеш-кодами
```
git log
```

## Как добавить коммит 

Что бы доавить комментраий используйте следующую команду:
```
git commit -m"message"
```

## Каак перейти ото одного коммита к другому

Что бы ерейти от одного коммита другому используйте следующую команду:
 ```
git checkout
 ```

## Как увидет разинцу между текущим файлом и закоммиченным файлом

Что бы увидеть разинцу между текущим файлом и закоммиченным ипользуйте команду:
```
git diff
```

## Как изменить последний коммит

Что бы изменить послдений коммит используйте следующую команду:
```
git commit --amend -m"message"
```


# Краткая инструкция по Markdown

## Цитаты

Цитаты оформляются как в емейлах, с помощью символа `>`.

> This is a blockquote with two paragraphs. Lorem ipsum
dolor sit amet,
> consectetuer adipiscing elit. Aliquam hendrerit mi
posuere lectus.
> Vestibulum enim wisi, viverra nec, fringilla in,
laoreet vitae, risus.
>
> Donec sit amet nisl. Aliquam semper ipsum sit amet
velit. Suspendisse
> id sem consectetuer libero luctus adipiscing.
Или более ленивым способом, когда знак `>` ставится
перед каждым элементом цитаты, будь то абзац, заголовок
или пустая строка:
> This is a blockquote with two paragraphs. Lorem ipsum
dolor sit amet,
consectetuer adipiscing elit. Aliquam hendrerit mi
posuere lectus.
Vestibulum enim wisi, viverra nec, fringilla in, laoreet
vitae, risus.
>
> Donec sit amet nisl. Aliquam semper ipsum sit amet
velit. Suspendisse
id sem consectetuer libero luctus adipiscing.

В цитаты можно помещать всё что угодно, в том числе
вложенные цитаты:

> ## This is a header.
>
> 1. This is the first list item.
> 2. This is the second list item.
>
> > Вложенная цитата.
>
> Here's some example code:
>
> return shell_exec("echo $input |
$markdown_script");

## Заголовки

## Исходный код

## Таблицы
