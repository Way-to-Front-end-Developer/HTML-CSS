**DevTools**

**Вкладка Elements**  
Она позволяет просмотреть структуру HTML-документа (DOM-дерево — Document Object Model).  
Также можно посмотреть CSS-правила, применяемые каждому элементу.  
Также можно посмотреть, как выглядит страница на мобильном устройстве и включить просмотр элемента по наведению указателя мыши.

**display**

### Flex

https://flexboxfroggy.com/#ru

**Флексбокс (flexbox)** — это система организации элементов на странице. Она помогает удобно располагать элементы относительно друг друга.

**Оси направления**  
**Главная ось** - (main axis) — это направление, вдоль которого расположены элементы.  
**Поперечная ось** - (сross axis) проходит перпендикулярно главной оси.

**flex container** - это элемент, которому назначено свойство display: flex.  
**flex items** - элементы, размещённые в контейнере.

**flex-direction**  
https://developer.mozilla.org/en-US/docs/Web/CSS/flex-direction  
направление расположения элементов задаётся свойством контейнера **flex-direction**.

```
flex-direction: <направление>;
```

**flex-wrap**  
https://developer.mozilla.org/en-US/docs/Web/CSS/flex-wrap  
Свойство **flex-wrap** задаёт правила переноса элементов на новую строку.

```
flex-wrap: <правило переноса>;
```

**justify-content**  
https://developer.mozilla.org/en-US/docs/Web/CSS/justify-content  
задаёт **justify-content** выравнивание элементов вдоль главной оси

```
justify-content: <правило выравнивания>;
```

flex-start, center, flex-end, space-between, space-around, space-evenly

**align-items**  
https://developer.mozilla.org/en-US/docs/Web/CSS/align-items  
Свойство **align-items** задаёт выравнивание элементов относительно поперечной оси.

```
align-items: <правило выравнивания>;
```

flex-start, flex-end, center, baseline, stretch (растягивание элементов, для которых не задана высота)

`<section>` — крупный раздел страницы, объединяющий содержание по смыслу.
Примеры: раздел «О компании», список товаров и пр.

`<article>` — самостоятельный фрагмент документа, который не зависит от других частей. Примеры: статья, пост в блоге, отдельная запись на форуме и пр.


