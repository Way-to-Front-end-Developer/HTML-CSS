**CSS (Cascading Style Sheets, каскадные таблицы стилей) — набор правил, которые описывают то, как выглядят элементы на странице.**  

Cascading Style Sheets (CSS) is a stylesheet language used to describe the presentation of a document written in HTML or XML (including XML dialects such as SVG, MathML or XHTML). CSS describes how elements should be rendered on screen, on paper, in speech, or on other media.

https://developer.mozilla.org/en-US/docs/Web/CSS  
https://html5book.ru/css-css3/

**CSS стили** отвечают за визуальное представление документа пользователю. Представляют собой набор css селекторов,  
и перечня css стилей для этого селектора, состоящих из конструкции ключ: значение; разделенных точкой с запятой.  
CSS селектор - это описание элемента, к которому будут применяться свойства. Может выбираться по:  
Тегу (селектору): div {...}  
Классу (атрибут класс) .element {...}  
Идентификатору, атрибуту и/или его содержимому (в более редких случаях).

**Синтаксис CSS-правила**  
Каждое CSS-правило состоит из двух частей: селектора и списка свойств. 
Список свойств записывается в фигурных скобках. 
Каждое свойство располагается на отдельной строке и заканчивается точкой с запятой.

```
селектор {
  свойство1: значение1;
  свойство2: значение2;
}

p {
  color: red;
  font-size: 2em;
}

```

**Селектор** — это указатель на элементы, к которым применяется данный набор свойств.  

https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Selectors  
https://www.w3schools.com/cssref/css_selectors.asp

### Приоритеты стилей  
  
1. Для одинаковых по массе селекторов приоритетнее будет тот, который записан снизу.    
2. У селекторов также есть свои приоритеты (указаны от меньшего)  
  a. Тег - 1;  
  b. Класс - 10;  
  c. Идентификатор - 100
  
3. У стилей, записанных через атрибут (инлайном) приоритет - 1000.  
4. Еще более приоритетным является объявлением !important в конце свойства.

**color**

1. Зарезервированное слово   
2. Шестнадцатеричный код (HEX) 
3. Десятичный код (RGB) 
```
color: navy;
color: #EE82EE;  
color: rgb(0,0,255);
```

HEX  
HEX (Hexadecimal) — это шестнадцатеричная модель RGB, где значения насыщенности представлены в шестнадцатеричной системе. 0 соответствует 00, а 255 — FF.

RGB  
В цветовой модели RGB (Red, Green, Blue) основные цвета имеют условные значения насыщенности от 0 до 255.

**background-color - цвета фона**  
**font-size - размера шрифта(px, em, rem etc.)**  
**font-weight - заданиe насыщенности шрифта**
**font-style - заданиe стиля шрифта**  
**font-family - заданиe гарнитуры шрифта**  
В качестве значения перечисляются несколько названий шрифтов. Если браузер не найдёт в системе первый шрифт, он перейдёт ко второму, и т. д.  
Последним в свойстве font-family указывается семейство шрифтов.

**Загрузка шрифтов**  
https://fonts.google.com/

**Наследование CSS-стиля**  
https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Cascade_and_inheritance

**Mastering margin collapsing**
https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Box_Model/Mastering_margin_collapsing
