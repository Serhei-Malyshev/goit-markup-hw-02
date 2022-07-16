# goit-markup-hw-02

Ссылка на ДЗ 2-3 в Фигме: https://www.figma.com/file/oTYBECAN79dXy19hzWObO4/Web-Studio-(Version-2.1)?node-id=1%3A94

/_ --------------------------Проведенные работы: --------------------------_/

1. создание css и привязка к html:

<head>

<link rel="stylesheet" href="./css/styles.css" />

</head>

2. создание палитры цветов текста:

Основной цвет текста - #212121

Вторичный цвет текста - #757575

3. создание палитры цветов сайта:

Основной цвет фона - #E5E5E5

Цвет фона шапки - #FFFFFF

Цвет фона футера - #2F303A

Основной интерактивный цвет - #2196F3

4. создание списка стилей текста

Roboto - 400, 500, 700, 900 Raleway - 700

5. задаем общие шрифты в index.html <head> и body (css) с сайта https://fonts.google.com/

в html:

 <head>:

<link rel="preconnect" href="https://fonts.googleapis.com" />

<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />

<link href="https://fonts.googleapis.com/css2?family=Raleway:wght@700&family=Roboto:wght@400;500;700;900&display=swap" rel="stylesheet"/>

</head>

в css:

body {

    background-color: #e5e5e5;

    font-family: "Raleway", sans-serif;

    font-family: "Roboto", sans-serif;}

6. Создаем :root - кастомные стили в css:

в css (1):

:root

{

--name-text-color: #000000;

--name-background-color: #000000;

--name-interface-color: #000000;

}

в css (2):

.element

{

color: var(--name-element-color);

}

в html:

class="element"

7. Убираем точки (маркеры <ul>):

в <head>:

class="list"

в css:

.list

{

list-style: none;

}

8. Оформляем заголовки в секциях

в html:

<h2 class="text-title">заголовок</h2>

в css:

color: var(--primery-text-color);

text-align: center;

9. Оформляем текст в секциях:

в html:

<p class="text-paragraf">

в css:

.text-paragraf

{

color: var(--secondary-text-color);

}

9. создаем стили для интерактивных кнопок (фильтра):

в css:

.button - общий стиль

{

color: var(--inter-text-color);

background: var(--fon-color);

}

.button-hover:hover - выделение при наводке курсора

{

color: var(--fon-color);

background: var(--inter-text-color);

}

.button.primery - выделение при активности

{

color: var(--inter-text-color);

background-color: var(--fon-color);

}

.button.secondary - свободное состояние

{

color: var(--fon-color);

background-color: var(--inter-text-color);

}

в html:

<button type="button" class="button">Кнопка с общим стилем</button>

<button type="button" class="button button-hover">Кнопка с общим стилем и выделением при наводке</button></li>

<button type="button" class="button primary">Активная кнопка</button>

<button type="button" class="button secondary">Неактивная кнопка</button>

9. Работаем с заголовком в HERO отдельно:

Задаем цвет текста:

color: var(--fon-color);

Задаем цвет фона:

background-color: var(--hero-footer-text-color);

Задаем жирность:

font-weight: 400;

Задаем font-size из Фигмы:

font-size: 44px;

Задаем line-height из Фигмы, но используем множитель:

line-height: 1.4; (line-height: 60px делим на font-size: 44px = 1.4)

Размещяем по центру:

text-align: center;

10. Создаем кнопку "Заказать услугу":

<button type="button" class="button primary">Активная кнопка</button>
