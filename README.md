# goit-markup-hw-02

Ссылка на ДЗ 2-3 в Фигме: https://www.figma.com/file/oTYBECAN79dXy19hzWObO4/Web-Studio-(Version-2.1)?node-id=1%3A94

/_ --------------------------Проведенные работы: --------------------------_/

1. создание css и привязка к html:

<head>

<link rel="stylesheet" href="./css/styles.css" />

</head>

2. создание палитры цветов:

:root {

    --primery-text-color: #212121;

    --secondary-text-color: #757575;

    --inter-color: #2196f3;

    --fon-color: #e5e5e5;

    --secondary-fon-color: #2f303a;

    --footer-text-color: rgba(255, 255, 255, 0.6);

    --fon-button-color: #f5f4fa;

    --fon-header-color: #ffffff;

}

используем их:

в css:

.element

{

color: var(--name-element-color);

}

в html:

class="element"

3. Создаем список стилей текста и устанавливаем их с сайта https://fonts.google.com/

Roboto - 400, 500, 700, 900 Raleway - 700

в html:

<head>:

<link rel="preconnect" href="https://fonts.googleapis.com" />

<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />

<link href="https://fonts.googleapis.com/css2?family=Raleway:wght@700&family=Roboto:wght@400;500;700;900&display=swap" rel="stylesheet"/>

</head>

в css:

body

{

font-family: "Raleway", sans-serif;

font-family: "Roboto", sans-serif;

}

4. Убираем точки (маркеры <ul>):

в html <head>:

class="list"

в css:

.list

{

list-style: none;

}

5. Убираем подчеркиванние ссылок для всех страниц:

в css:

a

{ text-decoration: none;

}

6. Задаем цвет фона в шапке:

в css:

.fon-header

{

background-color: var(--fon-header-color);

}

в html:

<header class="fon-header">

7. Изменяем цвет ссылки текущей страницы.

Добавляем к стилям ссылки текущей страницы .current елемент:

в css:

.site-nav.current

{

    color: #000000;

}

в html:

<a href="./index.html" class="site-nav current">Студия</a></li>

<a href="./portfolio.html" class="site-nav current">Портфолио</a></li>

8. Меняем цвет ссылок контактов в шапке:

в css:

.col-text-contact {

color: var(--primery-text-color);

в html:

<a href="mailto:info@devstudio.com" target="_blank" class="site-nav col-text-contact">info@devstudio.com</a>

<a href="tel:+380961111111" target="_blank" class="site-nav col-text-contact">+38 096 111 11 11</a>

Меняем цвет ссылок карты и контактов в футере:

в css:

.footer-maps-color

{

font-family: "Roboto";

font-style: normal;

font-weight: 400;

font-size: 14px;

line-height: 1.72;

color: #ffffff;

}

.footer-contact-color

{ color: var(--footer-text-color);

font-family: "Roboto";

font-style: normal;

font-weight: 400;

font-size: 14px;

line-height: 1.72;

}

в html:

<a href="https://goo.gl/maps/JzSsFaJVBJ5db8CR7" target="_blank" class="footer-maps-color">

г. Киев, пр-т Леси Украинки, 26</a>

<a href="mailto:info@devstudio.com" target="_blank" class="footer-contact-color">info@devstudio.com</a>

<a href="tel:+380961111111" target="_blank" class="footer-contact-color">+38 096 111 11 11</a>

9. Оформляем заголовки в секциях

в html:

<h2 class="text-title">заголовок</h2>

в css:

color: var(--primery-text-color);

text-align: center;

10. Оформляем текст в секциях:

в html:

<p class="text-paragraf">

в css:

.text-paragraf

{

color: var(--secondary-text-color);

font-size: 14px;

line-height: 1.7;

}

11. создаем стили для интерактивных кнопок (фильтра):

в css:

.button - общий стиль

{

color: var(--inter-color);

background: var(--fon-color);

}

.button-hover:hover - выделение при наводке курсора

{

color: var(--fon-color);

background: var(--inter-color);

}

.button.primery - выделение при активности

{

color: var(--inter-color);

background-color: var(--fon-button-color);

}

.button.secondary - свободное состояние

{

color: var(--fon-color);

background-color: var(--inter-color);

}

в html:

<button type="button" class="button">Кнопка с общим стилем</button>

<button type="button" class="button button-hover">Кнопка с общим стилем и выделением при наводке</button></li>

<button type="button" class="button primary">Активная кнопка</button>

<button type="button" class="button secondary">Неактивная кнопка</button>

12. Работаем с блоком HERO отдельно:

9.1 Задаем стиль текста заголовка:

в html:

<h1 class="title-text-hero">

в css:

Задаем цвет текста:

color: color: #ffffff;

Задаем жирность текста:

font-weight: 900;

Задаем font-size из Фигмы:

font-size: 44px;

Задаем line-height из Фигмы, но используем множитель:

line-height: 1.4; (line-height: 60px делим на font-size: 44px = 1.4)

Размещяем по центру:

text-align: center;

9.2 Задаем фон:

в html:

<section class="fon-hero">

в css:

.fon-hero

{

background-color: var(--secondary-fon-color);

}

9.3 Создаем кнопку "Заказать услугу":

<button type="button" class="button primary">Активная кнопка</button>

13. Изменяем фон футера:

в html:

<footer class="footer-fon">

в css:

.footer-fon

{

background-color: var(--secondary-fon-color);

}
