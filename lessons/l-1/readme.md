Advanced:https://advanced.team/

### HTML

history - https://vertex-academy.com/tutorials/ru/html_history/

https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Getting_started

**HTML**(Hypertext Markup Language) — язык гипертекстовой разметки для создания веб-страниц, представляет собой текстовый файл, который умеет читать браузер. HTML состоит из набора элементов, элементы HTML сообщают браузеру, как отображать содержимое. Когда такая страница открывается в браузере, он просматривает код HTML, находит специальные символы, называемые тегами, и использует их для создания элементов, таких как: рисунки, таблицы, ссылки и др.

HTML (Hyper Text Markup Language) — это язык разметки информации на веб-странице.(low)  

Документ HTML — это описание структуры страницы, в котором каждый элемент обозначен с помощью тэга.

### HTML Document  

http://www.etsav.upc.edu/assignatures/portafoli/tutorial1/3.html#:~:text=It's%20a%20text%20document%20saved,tutorials%20when%20applied%20and%20needed

### Element HTML

https://developer.mozilla.org/en-US/docs/Glossary/Element  
https://www.digitalocean.com/community/tutorials/what-is-an-html-element

**Elements** are designators that define the structure and content of objects within a page.

An **HTML element** is a component of an HTML document that tells a web browser how to structure and interpret  
a part of the HTML document. HTML elements can contain formatting instructions, semantic meaning, and content.

### Tag

https://www.digitalocean.com/community/tutorials/what-is-an-html-tag

An **HTML tag** is a piece of markup language used to indicate the beginning and end of an HTML element in an HTML document + describe element  
(text,img, table etc.)
**HTML tags** are like keywords that define how a web browser will format and display the content. With the help of tags,
a web browser can distinguish between an HTML content and a simple content.  

Тэг описывает отдельный элемент страницы: текст, картинку, таблицу и т. д.

HTML tags contain three main parts: an opening tag, content, and closing tag.

### Element VS Tag  

Elements and tags are not the same things.   
Теги начинают или заканчивают элемент в исходном коде, тогда как элементы являются частью DOM, модели документа для отображения страницы в браузере.  
(When you will use js all be clear)  
In HTML, a **tag** is used for creating an element.  
The name of an HTML element is the name used in angle brackets such as <p> for paragraph.  
Тег HTML — это часть языка разметки, используемая для обозначения начала и конца элемента HTML в документе HTML.  
As part of an HTML element, HTML tags help web browsers convert HTML documents into web pages.  
For example, the <p> tag is used to organize text content into paragraph elements and the <img> tag is used to embed image elements.
  
**Empty elements** - https://developer.mozilla.org/en-US/docs/Glossary/Empty_element

### Семантика

**Cемантика** - это использование чего-либо в соответсвии с его предназначением. В нашем случаем,  
это использованием элементов по их предназначению.

**Семантическая вёрстка** — подход к разметке, который опирается не на содержание сайта, а
на смысловое предназначение каждого блока и логическую структуру документа.
  
В программировании, Семантика означает значение фрагмента кода - например, «к какому результату приведёт выполнение этой строки JavaScript?»,  
или «каково предназначение или какая роль у этого элемента HTML» (а не «как он выглядит ?».)

Semantic elements = elements with a meaning.

https://htmlacademy.ru/blog/boost/frontend/semantics  
https://webref.ru/course/html-basics/semantics  
https://htmlacademy.ru/blog/articles/semantics?amp=1  
https://www.w3schools.com/html/html5_semantic_elements.asp  
https://www.simplilearn.com/tutorials/html-tutorial/html-semantics

### Anatomy of an HTML document  

https://www.geeksforgeeks.org/html-course-structure-of-an-html-document/  
https://html5book.ru/osnovy-html/#part1

**meta**    
https://developers.google.com/search/docs/crawling-indexing/special-tags

  
### Attributes
  
**HTML-атрибуты** это специальные слова, которые управляют поведением HTML-элемента. Они добавляют    
дополнительную функциональность, либо меняют поведение элемента по умолчанию. Атрибуты элемента выражаются внутри начального тега элемента.
  
**Атрибут — не обязательное свойство тега, с помощью которого можно задавать дополнительные параметры.**  

Нужен для описания более детальных характеристик html-элемента. Помещается внутри тега, и состоит из конструкции: ключ="значение".  
**src** — Указывает адрес файла, который будет загружаться на сайте.  
**href**— Указывает адрес документа, на который следует перейти.  
**class** — определяет одно или несколько имен для HTML элемента.  Позволяет связать определенный тег с его стилями или javascript логикой.
  
Attributes contain extra information about the element that won't appear in the content.  
In this example, the class attribute is an identifying name used to target the element with style information.
  
**action** in form it is that where form will send  
Every input has name  and value name=key value=velue

### Hyperlink
  
https://developer.mozilla.org/en-US/docs/Glossary/Hyperlink  
  
## HTML absolute and relative path
  
The path with reference to root directory is called absolute. The path with reference to current directory is called relative.

https://www.coffeecup.com/help/articles/absolute-vs-relative-pathslinks/
https://www.w3schools.com/html/html_filepaths.asp
  
**The relative path** means that the path to the file or page of the site is specified relative to  
the directory in which the current page is located, or relative to the root directory of the site. 
  
**An absolute path** is usually used to specify the path to a file that is located on another network resource.  
It is a complete URL to a file or page. In the absolute path, the protocol is first specified, followed by  
the domain name (site name). For example: http://www.example.com - this is how the absolute path to a particular  
website looks. http:// is a data transfer protocol, and www.example.com is the name of the site (domain)
  

**b(i) vs strong(em)** 

https://developer.mozilla.org/en-US/docs/Web/HTML/Element/strong#b_vs._strong

**validator**  

https://validator.w3.org/

Правила оформления кода:  

Чтобы код было удобно читать, нужно соблюдать несколько правил оформления:  
- Каждый отдельный элемент должен находиться на отдельной строке.  
- Элементы одного уровня вложенности должны иметь одинаковый отступ.  
- Длинный текст нужно разделять на несколько строк.  
- Для указания значения атрибутов нужно использовать двойные кавычки.
  
**Мнемоники или спецсимволы гипертекстовой разметке** как правило применяются для отображения на вебстранице символов отсутствующих на клавиатур
  
  
