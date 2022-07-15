# goit-markup-hw-02

Ссылка на ДЗ 2-3 в Фигме: https://www.figma.com/file/oTYBECAN79dXy19hzWObO4/Web-Studio-(Version-2.1)?node-id=1%3A94

/_ --------------------------Проведенные работы: --------------------------_/

1. создание css и привязка к html:

<head>

<link rel="stylesheet" href="./css/styles.css" />

</head>

2. создание палитры цветов:

Основной цвет текста - #212121

Вторичный цвет текста - #757575

Основной цвет фона - #E5E5E5

Цвет фона шапки - #FFFFFF

Цвет фона футера - #2F303A

Основной интерактивный цвет - #2196F3

3. создание списка стилей текста

Roboto - 400, 500, 700, 900 Raleway - 700

4. задаем общие шрифты в index.html <head> и body (css) с сайта https://fonts.google.com/

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

5. Создаем :root - кастомные стили в css:

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

6. Убираем точки (маркеры <ul>):

в <head>:

class="list"

в css:

.list

{

list-style: none;

}

7. создаем стили кнопок:
