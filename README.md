# hw9
## Регулярные выражения.
* Пункт 1.
Чтобы удалить все пустные строки, я использовала регулярное выражение: (\n\n) заменил все вхождения на \n.

![](https://github.com/stepanceva/hw9/blob/master/пункт%201.png)

P.s. т.к. задание четко не прописано, я удалила по одной лишней строке, чтобы остались красивые абзацы. Чтобы удалить вообще все пустые строчки, поле "Substitution" нужно оставить пустым. 

* Пункт 2.
Использовала регулярное выражение: [А-Я][а-яё]*слав[^\s.,\?!:;] 

![](https://github.com/stepanceva/hw9/blob/master/пункт%202.png)

Всего упоминаний о князьях нашла: 564


* Пункт 3.
Использовала регулярное выражение: (Нов(ѣ|ъ|[а-яё])?город([а-яё]*)?)[^\s.,\?|:;]?

![](https://github.com/stepanceva/hw9/blob/master/пункт%203.png)


Всего упоминаний Новгорода нашла: 59
