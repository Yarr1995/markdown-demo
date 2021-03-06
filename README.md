<!--Заголовки-->
# Heading 1     
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5 
###### Heading 6


***


# Заголовок 1-го ур-ня.
## Заголовок 2-го ур-ня.
### Заголовок 3-го ур-ня.
#### Заголовок 4-го ур-ня.
##### Заголовок 5-го ур-ня.
###### Заголовок 6-го ур-ня.

***
<!--Горизонтальный разделитель 3-мя звездами--> 

Заголовки "Heading 1" и "Heading 2" 
по умолчанию, подчеркиваются тонким
горизонтальным разделителем в Markdown.

(заметь автоматическое подчеркивание заголовков Heading 1 и Heading 2)
___

Альтернативный вывод заголовка Heading 1
===

Альтернативный вывод заголовка Heading 2
---

(заметь автоматическое подчеркивание заголовков Heading 1 и Heading 2)
___

<!--Горизонтальный разделитель 3-мя подчеркиваниями-->

<!--Выделения текста-->
_Italic text-1 (Этот текст стал курсивом через нижнее подчеркивание)_

*Italic text-2 (А этот текст стал курсивом через звездочки с обеих сторон)*

---
<!--Горизонтальный разделитель 3-мя дефисами-->

__Bold text-1 (Этот текст стал жирным благодаря двойному подчеркиванию с обеих сторон)__

**Bold text-2 (Этот текст стал жирным благодаря двойным звездочкам с обеих сторон)**

___
<!--Горизонтальный разделитель 3-мя подчеркиваниями-->

~~strikethrough text (Этот текст стал зачеркнутым благодаря двум тильдам с обеих сторон)~~

---

Одновременно _курсив_ + **жирный текст**:

**_Этот текст стал жирным курсивом благодаря подчеркиванию с обеих сторон плюс по 2 звезды с обеих сторон, перед подчеркиванием текста_**

***

<!--списки в markdown-->

Маркированный список:
* item 1
* item 2
* item 3
* item 4
* item 5

Вложенный маркированный список:
* item 1
  * item 1.1
  * item 1.2
  * item 1.3
* item 2
  * item 2.1
  * item 2.2
  * item 2.3

Нумерованный список:
<!--Цифры перед списком могут быть любыми, результат будет все равно замечательным-->
1. item 1
1. item 2
9. item 3
4. item 4
8. item 5

Еще один вложенный список:
1. item 1
   * item 1.1
   * item 1.2
   * item 1.3
1. item 2
   * item 2.1
   * item 2.2
   * item 2.3
1. item 3
   * item 3.1
   * item 3.2
   * item 3.3

   ---

<!--Ссылки в markdown-->
Ссылки в markdown:

В квадратных скобках пишется имя ссылки;

В круглых собках пишется адрес ссылки;
   [Имя ссылки](адрес ссылки)

[Google](https://google.com)

[YouTube](https://youtube.com)

[Puzzle English](https://puzzle-english.com)

[GitHub](https://github.com)

[Puzzle Movies](https://puzzle-movies.com/)

[jsfiddle](https://jsfiddle.net/)

***

Ссылки, выделенные __жирным__ текстом:

[__Google__](https://google.com)

[**YouTube**](https://youtube.com)

[__Puzzle English__](https://puzzle-english.com)

[**GitHub**](https://github.com)

[__Puzzle Movies__](https://puzzle-movies.com/)

[**jsfiddle**](https://jsfiddle.net/)

___

Ссылки, выделенные __жирным__  *курсивом*:

[**_Google_**](https://google.com)

[**_YouTube_**](https://youtube.com)

[**_Puzzle English_**](https://puzzle-english.com)

[**_GitHub_**](https://github.com)

[**_Puzzle Movies_**](https://puzzle-movies.com/)

[**_jsfiddle_**](https://jsfiddle.net/)

---

<!--Выделение кода в markdown-->
Выделение кода в markdown:

Я пишу слова и хочу выделить `однострочную команду`

То есть, однострочная команда выделяется: `вот так`

```
Многострочный код оформляется так.
```

```
npm install react
```

Оформление кода, как в синтаксисе javascript:
```javascript
   import {useState} from 'react';
```
Оформление кода, как в синтаксисе css:
```css
   .header {
       margin: 1 rem;
   }
```

Другие примеры javascript-кода:

```javascript
function perimeterSequence(a,n) {
  var perimeter = a*4;
  if(n>=1){
    return perimeter *n;
  }
}
```

```javascript
function opposite(number) {
  return number > 0 ? Number('-'+number) : Number(String(number).split('').slice(1).join(''))
}
```

```javascript
function fakeBin(strOfDigits){
 let arr =[];
  strOfDigits.split("").map(numstr =>{
    if(+numstr >=5){
      arr.push(1);
    }
    else{
      arr.push(0);
    }
  })
  return arr.join("");
}
```

```javascript
function even_or_odd(number) {
  return number % 2 ===0 ?"Even" :"Odd";
}
```

```javascript
function century(year) {
  return Math.ceil(year /100);
}
```

```javascript
const century = (year) => (year % 100 === 0 ? parseInt(year / 100, 10) : parseInt(year / 100, 10) + 1)
```

***

<!--Картинки в Markdown-->
Картинки в Markdown:

Картинка-1:

![Альтернативный текст картинки-1](https://upload.wikimedia.org/wikipedia/commons/thumb/4/48/Markdown-mark.svg/2560px-Markdown-mark.svg.png)

Картинка-2:

![Альтернативный текст картинки-2](https://www.gatsbyjs.com/_gatsby/image/e6976832ec63c547cbe1f11273cfc640/d68e08058a6f56bec56ce677733498ed/Hero%20visual.avif?u=https%3A%2F%2Fimages.ctfassets.net%2Fvkdbses00qqt%2FGzjal4V50EhyQc5sL8cjO%2F9063ef2217c170ef1fe054c2be358147%2FHero_visual.png&a=w%3D1600%26h%3D1259%26fm%3Davif%26q%3D75)

Картинка-3:

![Альтернативный текст картинки-3](https://trofimovdigital.ru/wp-content/uploads/markdown-guide/markdown-guide.jpg)

Картинка-4:

![Альтернативный текст картинки-4](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQwq4lu9d9KmKPKHL3gR0FSwns_in8QsEGgtX7pFzWj-bt6LngbSMjCebp-BmYXq6_FkA0&usqp=CAU)

<!--Цитаты в markdown-->
Цитаты в markdown:

>Первая цитата в Markdown

>Еще какая-то цитата в Markdown

>Вообще, цитаты в Markdown пишутся крайне просто:
 достаточно поставить знак ">" и дальше записать 
 текст цитаты. 

<!--Горизонтальные разделители в Markdown:-->
Горизонтальные разделители в Markdown:

***
---
___ 

Горизонтальный разделитель 3-мя звездами ***:
***
***
Горизонтальный разделитель 3-мя дефисами ---:
<!--для 3-х дефисов должно быть расстояние между строкой текста и тремя дефисами, иначе 3 дефиса будут считаться частью строки текста-->
---
---
Горизонтальный разделитель 3-мя подчеркиваниями:
___
___

<!--Таблицы в markdown-->
Таблицы в markdown:

| Tables   |      Are      |  Cool |
|----------|:-------------:|------:|
| col 1 is |  left-aligned | $1600 |
| col 2 is |    centered   |   $12 |
| col 3 is | right-aligned |    $1 |


***
<!--Горизонтальный разделитель 3-мя звездами-->

| 1  | 2  | 3  | 4  | 5  | 6  | 7  |
|----|----|----|----|----|----|----|
| 8  | 9  | 10 | 11 | 12 | 13 | 14 |
| 15 | 16 | 17 | 18 | 19 | 20 | 21 |
| 22 | 23 | 24 | 25 | 26 | 27 | 28 |

---
<!--Горизонтальный разделитель 3-мя дефисами-->

| №1  | №2  | №3  | №4  | №5  | №6  | №7  |
|-----|-----|-----|-----|-----|-----|-----|
| №8  | **№9**  | №10 | №11 | **№12** | №13 | №14 |
| №15 | №16 | __№17__ | №18 | №19 | **№20** | №21 |
| №22 | №23 | №24 | **№25** | №26 | №27 | **№28** |

___
<!--Горизонтальный разделитель 3-мя подчеркиваниями-->


| Значение 1 | Значение 2 | Значение 3 | Значение 4 | Значение 5 |Значение 6  |Значение 7  |
|------------|------------|------------|------------|------------|------------|------------|
|Значение 8  | Значение 9 | Значение 10|Значение 11 |Значение 12 |Значение 13 |Значение 14 |
|Значение 15 | Значение 16| Значение 17|Значение 18 |Значение 19 |Значение 20 |Значение 21 |
|Значение 22 | Значение 23| Значение 24|Значение 25 |Значение 26 |Значение 27 |Значение 28 |

---

<!--Список дел в markdown-->
Список дел в markdown:

Отображение серых  чекбоксов с серой
 галочкой на GitHub:

* [x] Todo 1
* [x] Todo 2
* [x] Todo 3
* [x] Todo 4
* [x] Todo 5
---
<!--Горизонтальный разделитель не входит в синтаксис cписка дел в markdown-->

Такой же список, но жирный:

* [x] **Todo 1**
* [x] __Todo 2__
* [x] __Todo 3__
* [x] **Todo 4**
* [x] **Todo 5**

___

Отображение серых  чекбоксов без серой
 галочки на GitHub:

* [ ] Todo 1
* [ ] Todo 2
* [ ] Todo 3
* [ ] Todo 4
* [ ] Todo 5
***
<!--Горизонтальный разделитель не входит в синтаксис cписка дел в markdown-->

Комбинированный список дел:
* [ ] Todo 1
* [ ] Todo 2
* [x] Todo 3
* [ ] Todo 4
* [x] Todo 5
* [x] Todo 6
* [x] Todo 7
* [ ] Todo 8
* [x] Todo 9
* [x] Todo 10

___
<!--Горизонтальный разделитель не входит в синтаксис cписка дел в markdown-->


<!--Добавление YouTube-видео в markdown-->
Добавление YouTube-видео в markdown:

Видео-1:

  [![Альтернативный текст](https://i.ytimg.com/vi/iguB3BKGSLo/hq720.jpg?sqp=-oaymwEcCNAFEJQDSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLASA9YvcayMo8fNNk5DYZZt9QDfkw)](https://www.youtube.com/watch?v=iguB3BKGSLo)

  ---
Видео-2:

[![Альтернативный текст видео](https://i.ytimg.com/vi/uCNWuSbPnt4/hq720.jpg?sqp=-oaymwEcCNAFEJQDSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLCJK2uWHiYvX7_3dyS5MC0UNzan4g)](https://www.youtube.com/watch?v=uCNWuSbPnt4)

***

Видео-3:

[![Альтернативный текст к видео](https://i.ytimg.com/vi/Pkh8UtuejGw/hq720.jpg?sqp=-oaymwEcCNAFEJQDSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLAlEom4rIygiHjjwOiSd0at0nRFPg)](https://www.youtube.com/watch?v=Pkh8UtuejGw)

Markdown - что за язык и как им пользоваться

<!--Комментарии в markdown-коде пишутся точно так же, как в html-->