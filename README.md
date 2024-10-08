# Синтаксис языка разметки Markdown

# H1 — заголовок первого уровня, самый большой
## H2 — заголовок второго уровня, поменьше
### H3
#### H4
##### H5
###### H6 — заголовок шестого уровня, самый маленький 

#### Заголовок 4

Текст над чертой

---

Текст под чертой


Текст до переноса⋅⋅  
Текст после переноса <br>
Текст после второго переноса

Курсив — это *звёздочки* или _подчёркивания_.

Полужирный шрифт — двойные **звёздочки** или двойные __подчёркивания__.
Можно совместить выделение **звёздочки и _подчёркивания_**.

~~Зачёркнутый текст.~~

Списки

Для оформления нумерованного списка достаточно поставить в начало строки цифры с точкой.

1. Первый пункт нумерованного списка.
2. Второй пункт. 

Ненумерованный список создаётся звёздочкой с пробелом в начале строки либо дефисом с пробелом.

* первый пункт ненумерованного списка;
* второй пункт ненумерованного списка

- первый пункт ненумерованного списка;
- второй пункт ненумерованного списка 


Ссылки

Чтобы сделать ссылкой часть текста, его заключают в квадратные скобки, а затем указывают нужный адрес в круглых скобках.

[Яндекс](https://www.yandex.ru) 

Также можно добавить ссылке тайтл (от англ title — «название», «заголовок»). Тайтл — это всплывающая подсказка, которая появляется при наведении мыши на ссылку. Тайтл нужно заключить в кавычки и указать внутри скобок после адреса.

[Яндекс](https://www.yandex.ru "Я Yandex!") 



Код

Чтобы оформить текст как код, нужно окружить его тройками косых кавычек — грависов. После первой тройки грависов указывают язык программирования, на котором написан код. В маркдауне есть поддержка синтаксиса почти всех популярных языков и инструментов.

```bash
ls - la
```

```html
<h1>А я просто текст</h1>
``` 

Обратите внимание: вторая тройка тройных кавычек стоит на отдельной строке.
