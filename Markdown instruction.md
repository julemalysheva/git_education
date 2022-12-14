# Инструкция для работы с Markdown

## Выделение текста

Чтобы выделить текст курсивом, необходимо обрамить его звездочками (*) или знаком
нижнего подчёркивания (_). Например, *Вот так* или _Вот так._

Чтобы выделить текст полужирным, необходимо обрамить его двойными звездочками (**) или двойным нижним подчёркиванием (__). Например, **Вот так** или __Вот так__.

Альтернативные способы выделение текста жирным или курсивом, нужны для того,
чтобы мы могли совмещать оба этих способа. Например, _текст может быть выделен
курсивом и при этом быть **полужирным**._

## Списки

Чтобы добавить ненумерованные списки, необходимо пункты выделить звёздочкой (*) или знаком +. Например, вот так:
* Элемент 1
* Элемент 2
* Элемент 3
+ Элемент 4

Чтобы добавить нумерованные списки, необходимо пункты просто пронумеровать. Например, вот так:
1. Первый пункт
2. Второй пункт

## Работа с изображениями

Чтобы вставить изображение в текст, достаточно написать следующее:

! [] () без пробелов. Например:

![Привет, это я, Юля!))](1626805609192.jpg)

В квадратных скобках мы укажем текст, который будет выводиться, если изображение не
загрузится. А в круглых скобках имя файла, из которого необходимо изображение достать.

## Ссылки
Есть 2 способа создать ссылку:

1. [С указанием ссылки сразу](https://www.google.com) - в этом случае сначала в квадратных скобках [указываем отображение текста для ссылки] и рядом в круглых скобках (https://www.google.com) указываем адрес ссылки.

2. [С указанием ссылки в сноске][Произвольный ссылочный текст без учета регистра]

   [Можно использовать цифры в качестве сносок][1]
   
   В этом случае строка состоит из пары квадратных скобок [], в первой указывается текстовое отображение ссылки, во второй произвольный ссылочный текст или цифра, который используется в качестве расшифровки сноски ниже, в таком формате:

   [Произвольный ссылочный текст без учета регистра или цифра]: сама ссылка без кавычек и скобок

   [Произвольный ссылочный текст без учета регистра]: https://www.mozilla.org
   [1]: https://github.com

   Также любая ссылка, обрамлённая в угловые скобки (<>), автоматом преобразуется
<https://www.google.com>


## Работа с таблицами
Обязательно требуют заголовок и настройки выравнивания (второй строкой). Выравнивание задаётся двоеточием (:). Колонки задаются вертикальным палками (|)

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

Внешние вертикальные палки (|) задавать необзяательно, также не требуется подгонять колонки под один размер. Можно использовать стили, описанные выше.

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3

Во второй таблице используются элементы выделения текста.
## Цитаты
> Цитаты задаются угловой скобкой (>).
> Это строка является частью цитаты.

Здесь цитата прерывается.

> Можно писать много-много текста, и он автоматически всё преобразует в одну цитату. Также можно использовать разилчные *начертания* в **цитате**. Красота!

>Уровень цитат определяется количеством знаков (>). 
>>Здесь используется второй уровень.
>>> А здесь цитата третьего уровня.
>>>> Здесь четвертого
>>>>> Пятого и т.д.

Уровень цитирования не может превышать 15-й.
## Заключение
25.07.2022 изменила имя в Git на julemalysheva