# Инструкция для работы с Markdown

## Выделение текста

Чтобы выделить текст курсивом необходимо обрамить его звездочками (*) или знаком нижнего подчеркивания (_). Например, *вот так* или _вот так_.

Чтобы выделить текст полужирным, необходимо обрамить его двойными звездочками (**) или двойным знаком нижнего подчеркивания (__).
Например, **вот так** или __вот так__. 

Альтернативные способы выделения текста жирным или курсивом нужны для того, чтобы мы могли совмещать оба этих способа. Например, _текст может быть выделен курсивом и при этом быть **полужирным*

## Списки

Чтобы добавить ненумерованные списки, необходимо пункты выделить звездочкой (*) или знаком +.
Например, вот так:
* Элемент 0
* Элемент 1
+ Элемент 3
+ Элемент 4

Чтобы добавить нумерованные списки, необходимо пункты просто пронумеровать.
Например, вот так:
1. Первый пункт
2. Второй пункт

## Работа с изображениями 

Чтобы вставить изображение в текст, достаточно написать следующее:

![Привет, это Кот!](Cat.png)

## Ссылки

Чтобы поставить гиперссылку без анкора, нужно взять URL в угловые скобки. С e-mail – аналогично.

Если вставлять с анкором, то тогда текст ссылки заключается в квадратные скобки, а адрес страницы – в круглые. Рядом с URL можно прописать тайтл, его объявляют в кавычках (он тоже остается внутри круглых скобок).


Это [ссылка]( "Агентство TexTerra") с тайтлом.

[Эта ссылка](http://example.net/) без заголовка.

<https://texterra.ru/&gt; – а это безанкорная ссылка.

## Работа с таблицами

Если поддерживается расширенная версия Markdown, можно вставлять таблицы. Для этого используются всего два символа: вертикальная черта и дефис. Дефисы работают примерно так же, как в случае с горизонтальной линией: отделяют заголовки от других строк, при этом количество символов значения не имеет. Вертикальная черта служит границей между столбцами.

Обязательно требуют заголовок и настройки выравнивания (второй строкой). Выравнивание задаётся двоеточием. Колонки задаются вертикальным палками (|)

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

## Цитаты

Если безанкорные ссылки оформляются двумя угловыми скобками, то для цитаты нужна только одна такая скобка. Все очень просто:

> Привет! Это цитата

> Это тоже цитата

> Это еще одна цитата

    Это ее продолжение (показываем отступом)   
    Это тоже
    Будет
    Одна целая цитата

## Заключение

Настоящий документ предназначен для ознакомления пользователя с функциональными возможностями языка разметки Markdown. Markdown – это облегченный язык разметки, который является инструментом преобразования кода в HTML. Главной особенностью данного языка является максимально простой синтаксис, который служит для упрощения написания и чтения кода разметки, что, в свою очередь, позволяет легко его корректировать. 
