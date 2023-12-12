<p align="center"> Министерство образования Республики Беларусь</p>
<p align="center">Учреждение образования</p>
<p align="center">“Брестский Государственный технический университет”</p>
<p align="center">Кафедра ИИТ</p>
<br><br><br><br><br><br><br>
<p align="center">Лабораторная работа №3</p>
<p align="center">По дисциплине “Общая теория интеллектуальных систем”</p>
<p align="center">Тема: “Разработка редакторов графов”</p>
<br><br><br><br><br>
<p align="right">Выполнил:</p>
<p align="right">Студент 2 курса</p>
<p align="right">Группы ИИ-23</p>
<p align="right">Медведь П. В.</p>
<p align="right">Проверил:</p>
<p align="right">Иванюк Д. С.</p>
<br><br><br><br><br>
<p align="center">Брест 2023</p>

---

# Task 
1. Разработать и реализовать программный продукт позволяющий редактировать графовые конструкции различных видов и производить над ними различные действия. Язык программирования - любой.

2. Редактор должен позволять (задания со [*] являются необязательными):
a) одновременно работать с несколькими графами (MDI);
b) [*] выделение одновременно нескольких элементов графа, копирование выделенного фрагмента в clipboard и восстановление из него;
c) задавать имена графам;
d) сохранять и восстанавливать граф во внутреннем формате программы;
e) экспортировать и импортировать граф в текстовый формат (описание см. ниже);
f) создавать, удалять, именовать, переименовывать, перемещать узлы;
g) создавать ориентированные и неориентированные дуги, удалять дуги;
h) добавлять, удалять и редактировать содержимое узла (содержимое в виде текста и ссылки на файл);
i) задавать цвет дуги и узла, образ узла;
j) [*] создавать и отображать петли;
k) [*] создавать и отображать кратные дуги.

3. Программный продукт должен позволять выполнять следующие операции:
a) выводить информацию о графе:

    *   количество вершин, дуг;
    *   степени для всех вершин и для выбранной вершины;
    *   матрицу инцидентности;
    *   матрицу смежности;
    *   является ли он деревом, полным, связанным, эйлеровым, [*] планарным;
b) поиск всех путей (маршрутов) между двумя узлами и кратчайших;
c) вычисление расстояния между двумя узлами;
d) вычисление диаметра, радиуса, центра графа;
e) [*] вычисление векторного и декартово произведения двух графов;
f) [*] раскраска графа;
g) нахождения эйлеровых, [*] гамильтоновых циклов;
h) [*] поиск подграфа в графе, со всеми или некоторыми неизвестными узлами;
i) [*] поиск узла по содержимому;
j) [*] объединение, пересечение, сочетание и дополнение графов;
k) [*] приведение произвольного графа к определенному типу с минимальными изменениями:

    *   бинарное и обычное дерево;
    *   полный граф;
    *   планарный граф;
    *   связанный граф;
5. Написать отчет по выполненной лабораторной работе в .md формате (readme.md). Разместить его в следующем каталоге: trunk\ii0xxyy\task_03\doc (где xx - номер группы, yy - номер студента, например ii02408).

6. Исходный код разработанной программы разместить в каталоге: trunk\ii0xxyy\task_03\src.
# Results:

# Создаем рабочее пространство для графа (создаем новый граф):

![](1.png)

![](2.png)

![](3.png)

![](4.png)

# Выбор между созданием орграфа или неориентированного графа:

![](5.png)

![](25.png)

![](6.png)

# Сохранение графа во внутреннем формате программы и в текстовом ( также и импорт ):

![](7.png)

![](8.png)

![](24.png)

# Замена цветов у вершин и ребер:

![](9.png)

![](10.png)

![](11.png)

# Вывод информации о графе: 

![](27.png)

![](12.png)

![](13.png)

![](14.png)

# Алгоритмы над графом:

![](26.png)

![](15.png)

![](16.png)

![](17.png)

![](18.png)

![](19.png)

![](20.png)

![](21.png)

# Работа с несколькими графами:

![](22.png)

![](23.png)
