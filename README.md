# html-css-l-9
lesson 9
Развернутая статья о формах
https://webref.ru/layout/learn-html-css/building-forms


Раздел на w3schools с интерактивными примерами
https://www.w3schools.com/html/html_forms.asp


Grid(Сетка)
Зачем нужна сетка?
При создании верстки сайта есть необходимость разбивать содержимое страницы на колонки: sidebar(боковая панель), main content(основное содержание), возможно еще одна боковая панель с рекламой. Внутри основного содержимого страницы (main content) также приходится разбивать на колонки, как это часто реализовано в блогах.  Даже в более мелких элементах зачастую приходится делить ширину контейнера на несколько частей.
Нужен инструмент который поможет упростить работу и не дублировать код. Для этих целей и была разработана сетка ( Grid ). Grid  работает следующим образом - ширина контейнера делится на равные части. Количество частей - это размер сетки.
Размер сетки бывает разный, но самый распространенный это 12. Это значит что одна колонка будет занимать 8.33% (100%/12 = 8.33%). Далее для создание колонок объединяется то количество колонок, которое нужно. Например, для создания 2х колонок, нужно объединить по 6 частей сетки. Так как 12 у нас это 100% ширины, то для создания колонок по 50% нам нужно объединить по 6 частей сетки.
Почему 12 колонок самый распространенный вариант?
Необходима система, которая будет достаточно гибкой, чтобы использовать ее в разных ситуациях. Размеры колонок на сайтах бывают разными. Кроме того, мы часто используем Grid при создании элементов страницы, которые в свою очередь разнятся в размерах.
12 делится на 2, 3, 4, что позволяет нам достаточно гибко выбирать размер который необходим.
