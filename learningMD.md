# Instructions for working with MarkDown

## Git command
### Основные команды
- version - 
- status - когда возникают вопросы :)
### Создание репозитория и работа с файлами
- init - инициализация репозитория в выбранной папке
- add - добавление файла в отслеживаемые gitом
- commit -m "text of the comment" - сохранение с комментарием
- diff - 
- log - 
### Работа с ветками
- branch - 
- branch <name of new branch> - 
- branch -d <name of branch> - 
- checkout <name of branch> - 
- checkout -b <name of branch> - 
- branch -m <old name of branch> <new name of branch> - 
- merge <name of branch> - 


## Text selection

To hightlight the text in italics, *frame it with asterisks* or _underscores_

To hightlighting the text in bold, **frame it with double asterisks** or __double underscores__

To hightlighting the text by strikethrough frame it in ~~double tilde~~

We can combine the selection methods, examples bellow

***italic and bold text***

___italic and bold text___

__*italic and bold text*__

**_italic and bold text_**

~~*italic and strikethrough text*~~

**~~strikethrough and bold text~~**

___~~strikethrough, italic and bold text~~___

~~*__strikethrough, italic and bold text__*~~

**The formatting order does not matter**

## Lists

To create an unnumbered list, write at the beginning of the line (*) or (+) or (-) then a space. Examples bellow

* First element
* Second element
* Third element

+ First element
+ Second element
+ Third element

- First element
- Second element
- Third element

If we use different characters, the indentation between the lines of the list increases

* First element
* Second element
- Third element
- Fourth element
+ Fifth element
+ Sixth element

To create a numbered list, use a digit with a dot at the beginning of the line

1. First element
2. Second element
3. Third element

Markdown markup also allows you to design multi-level list. The level is indicated by indentation.  It is easier not to count spaces, but to hightlight each new subparagraph with a tab. Examples bellow

1. Item 1
    1. Sub-item 1.1
        * Sub-item 1.1.a
    2. Sub-item 2.1
        1. Sub-item 2.1.1

2. Item2
    * sub-item A
        * sub-item A.a
    * sub-item B
        + sub-item B.a
        - sub-item B.b
    + sub-item C

## Working with images

To add an image, write an exclamation mark (point) at the begining of the line, then square brackets, then in parentheses the name of the file located in the repository folder.

![](images/1575.jpg "перевод знаков")

## Links

To put a hyperlink without an anchor, you need to take the URL in angle brackets. With e-mail similarly

<https://texterra.ru/> link without anchor

if you insert with an anchor, then the link text is enclosed in square brackets, and the page address is in round brachets. to the URL, you can write a title, it is declared in quotation marks (it also remains inside parentheses)

This is the [link](https://texterra.ru/) without title

This is the [link](https://texterra.ru/ "site Texterra") with a title

## Quotes

To add a quote, use one angle bracket. Quotes are embedded both in lists and in other quotes

>quote
>>encloset quote
>>>third-level quote
>>>>>>> quotes

## working with tables

## Conclusion

again practic 2