# Sedona
Учебный макет сайта *Sedona*


## Ссылки на текущую реализацию:

- [index](https://ayrgrant.github.io/sedona/)
- [hotels](https://ayrgrant.github.io/sedona/hotels.html)


## Тесты реализации некоторых элементов

* Тест [сетки](http://codepen.io/anon/pen/KpyWXK)
* Тест [шапки](http://codepen.io/anon/pen/RPjpaQ)
* Тест маски для постера:
  * [с помощью градиентов](http://codepen.io/anon/pen/eNevNm)
  * [с помощью svg](http://codepen.io/anon/pen/NqwpyZ)
* Тест нумерации блоков через псевдоэлемент:
  * [с помощью атрибута](https://jsfiddle.net/59gd5qjd/)
  * [с помощью счетчика](https://jsfiddle.net/59gd5qjd/1/)
* Тест ['элемента диапазона'](http://codepen.io/anon/pen/RPjmBX)

## Фрагменты Т.З.:

>Все макеты:
>
- Контентная область центрируется и не может быть уже макетной ширины.
Логотип — это ссылка на главную страницу.
- Главное меню: четыре ячейки по 20% ширины, в каждой из них контент лежит по центру. Между второй и третьей есть отступ для расположения логотипа так же шириной 20%.
- При достижении 1200px (или 768px, если верстается фиксированная версия с этой шириной) сетка перестаёт масштабироваться дальше, и слева и справа от неё появляется серый фон, на который сайт бросает лёгкую тень.

>sedona-index.psd:
>
- Крупное фото: фотография занимает 100% ширины, в её нижней части есть белая маска, которая также масштабируется на 100% ширины, но в отличие от фотографии меняет свои пропорции (то есть высота остаётся постоянной, а ширина — 100%).
- Фотографии, занимающие по две трети ширины вставляются так, чтобы обрезаться сверху и снизу при увеличении размера (ширина 66%, высота подстраивается под ширину, чтобы не нарушать пропорций, но фото не выходит за отведённую для него зону).
- Кнопка «Поиск гостиницы в Седоне» управляет отображением формы поиска гостиницы (смотрите папку слоёв «search form»), необходимо дополнить анимацией «выезда» сверху вниз.
- Блок карты — достаточная реализация — обычное изображение.
- Блок карты — реализация по желанию — интерактивная карта, которая также масштабируется на 100% ширины.

>sedona-hotels.psd:
>
- Главное меню и футер совпадают с главной страницей.
Фоновое фото другое (размытое и меньшей высоты), но также масштабируется на 100% ширины.
- Блок «Стоимость в сутки» — при наведении на любой из маркеров появляется указатель `cursor: pointer`, делать маркеры подвижными не обязательно, цена меняться не должна.
- Фильтр: верстать с помощью формы, кнопка «Показать» отвечает за отправку формы, при выключенном JavaScript должен осуществляться переход на отдельную страницу (отдельную страницу верстать не нужно).

