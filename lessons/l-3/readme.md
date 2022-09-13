### Виды селекторов  

https://learn.javascript.ru/css-selectors

### class

The **class** global attribute is a space-separated list of the case-sensitive classes of the element. Classes allow CSS and JavaScript to select and access specific elements via the class selectors or functions like the DOM method document.getElementsByClassName.

Один элемент может относиться к нескольким классам. Имена в этом случае указываются в атрибуте class через пробел.  
Несколько элементов можно отнести к одному классу. Тогда описанные стили применяются к каждому из них.

### Имя класса

Имена классов принято писать маленькими буквами.
Если имя класса состоит из нескольких слов, то оно пишется слитно, а каждое слово отделяет дефис. Такой способ задания имени называется kebab-case (шашлычная нотация).

```
.lead-text {
  font-style: italic;
}
```

### Сложные селекторы  

https://web.dev/learn/css/selectors/

Чтобы описать элемент с помощью нескольких селекторов, их нужно перечислить друг за другом, без пробелов и запятых.

### Вложенность

В селекторах можно указывать вложенность. Для этого несколько селекторов нужно разделить пробелом.
.head li — сработает для всех элементов <li>, находящихся внутри элементов с классом head.

чтобы задать общее правило для нескольких селекторов, их можно перечислить через запятую: h1, .price сработает для всех элементов h1 и всех элементов с классом price.

### Псевдоклассы

A CSS pseudo-class is a keyword added to a selector that specifies a special state of the selected element(s).
https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-classes

```
li:first-child {
  color: red;
}
```

Для указания псевдокласса к селектору добавляется ключевое слово с двоеточием перед ним.

Первый дочерний элемент (first-child)
  
differnce between :: and :  

Pseudo-class :  
Pseudo-elements ::  
The CSS3 Selectors specification prefixes pseudo-elements with two colons instead of one. So, :first–letter becomes ::first-letter and :first-line becomes ::first-line. IE 8 and earlier don’t understand the double-colon prefix, so you need use the single-colon versions to avoid styles breaking in older browsers.
