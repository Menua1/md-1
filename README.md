# Инструкция по работе с md 

# содержание 
## заголовок
# текст 
## текст 
### текст 
#### текст
##### текст
###### текст 

 заголовки обозначаются знаком (#) в начале строки ,после чего пробел и непосредственно заголовок. Чем больше (#) тем меньше будет у вас заголовок(подзаголовок)

## выделение 
*курсив* обозначается звездочками(* *)или же нижним подчеркиванием(_ _) без пробела вводится текст.

**полужирный шрифт** обозначается двойными звездочками/или нижними подчеркиваниями в начале и концце слова/предложения (** **) или (__ __).

**_комбинированное выделение_** дает возможность выделить и шрифт и курсив ,делается с помошью (** _ _ **) двух звездочек и 1 подчеркивания ,или же (__ * * __)двумя подчеркиваниями и звездочкой 

для ~~зачеркнутого текста~~ используйте две тильды (~~) в начале и конце слова\предложения. (Ctrl+Ё)
## списки 
1. Первый пункт нумерованного списка
2. Второй пункт
⋅⋅*Ненумерованный вложенный список.
1. Сами числа не имеют значения, лишь бы это были цифры.
4. И еще один пункт.

        
    Чтобы вставить разрыв строки, но не начинать новый параграф, нужно добавить два пробела перед новой строкой.

* Ненумерованный список можно размечать звездочками
(-) Или минусами
(+)Или плюсами
## ссылки 

__[ссылка](https://gb.ru/lessons/261857) делается с помошью квадратных и обычных скобочек название ссылки берется в квадратные ссылки,сама ссылка же в круглых скобках.__
__Точно такой же принцип для ссылки на документ ,название выделается в квадратные скобки а ссылка на документ в квадратные.__

## изображения 

![alt-text](https://lubopitnie.ru/wp-content/uploads/2020/08/geekbrains-otzyvy.png "текст который будет при наведении на изображение")
_для добавления картинки используйте ! на начале страки,зачем [alt-text](и непосредственно ссылка на изображение в круглых скобках "в ковычки выделяются комментарии при наведении курсором на изображение")_
## подсветка кода и синтаксиса 
`Подсветка кода и синтаксиса обраменяется обратными апострафами ``.` 

``либо же двумя апострафами`` (``)

## таблицы 

Вертикальные линии обозначают столбцы.

| Таблицы       | Это                | Круто |
| ------------- |:------------------:| -----:|
| столбец 3     | выровнен вправо    | $1600 |
| столбец 2     | выровнен по центру |   $12 |
| зебра-строки  | прикольные         |    $1 |

markdown | не такой| красивый 
--- | --- | ---
*но выводится*| ``так же`` | __красиво__
1|2|3


## цитаты 
>Цитаты отмечаются (>) в начале строки 
>если вам нужно продолжить цитату и сместиться со страки используйте сдующую строку начиная с того же символа (>)

>если же маи нужно вписать другую цитату отступите одну пустую страку и получите разрыв.
## встроенный HTML  
<dl>
  <dt>Список определений</dt>
  <dd>Это то, что люди иногда используют.</dd>

  <dt>Markdown внутри HTML</dt>
  <dd>Работает *не очень** хорошо. Используйте HTML-<em>теги</em>.</dd>
</dl>

<dt> Понимаю с трудом</dt>
<dd>но вроде получится разобраться <em>время покажет </em>.</dd>


Markdown внутри HTML

Работает *не очень** хорошо. Используйте HTML-теги.


## горизонтальная линия 
горизонтальные линии можно добавить 3 способами 
1. --- дефиз 
2. *** звездочки 
3. ___ подчеркивания 
выглядит это так 
--- 
дефиз 
*** 
звездочки 
___
подчеркивания 
знаки используются на верхней страке зачетм Enter и ввод текста.

## новая строка 

это начальная строка 

эта строка на растоянии в 1 пустую строку от первоначальной ...
эта строка разделена одним нажатием клавиши Enter


эта строка разделена 2 пустыми строками ,как видите не имеет разницы вы пропустите 1 строку пустую или 2 или 3 или 4...

## видео YouTube 
видео нельзя вставить напрямую поэтому воспользуемся картинкой с ссылкой на видео.
сначала [![alt-text название изображения ](ссылка на изображение)](ссылка на видео).markdown колдует и выдает нам изображение при нажатии на которое получаем переход на видео в YouTube.

[![alt-text ЧБД](https://peopletalk.ru/wp-content/uploads/2020/09/chbdshou.jpg)](https://yandex.ru/video/preview/?text=%D1%87%D0%B1%D0%B4%20%D0%BD%D0%BE%D0%B2%D1%8B%D0%B9%20%D0%B2%D1%8B%D0%BF%D1%83%D1%81%D0%BA%202022&path=yandex_search&parent-reqid=1663674406818226-12763396503721674153-sas2-0288-sas-l7-balancer-8080-BAL-6300&from_type=vast&filmId=2001553767418009826)



# THE END.