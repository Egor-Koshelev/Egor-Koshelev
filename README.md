<h1>ПОРТФОЛИО: АНАЛИТИК ДАННЫХ</h1>
<h2>ОБО МНЕ </h2>
Добрый день, меня зовут Егор Кошелев, я начинающий аналитик данных.
В этом репозитории вы можете найти ряд проектов, которые я выполняла во время обучения и практики. Email: 

<h3>НАВЫКИ И ТЕХНОЛОГИИ</h3>
<p>- Инструменты анализа данных: SQL, Excel (агрегирующие функции, умные таблицы, сводные таблицы, Power Query, Power Pivot, визуализация данных, построение дашбордов), Google Sheets, PolyAnalist, Gephi.
<p>- Языки программирования и библиотеки: Python, Pandas.
<p>- Системы управления базами данных: MySQL, диалект PostgreSQL.
<p>- Средства визуализации данных: PowerBi, Matplotlib, Gephi, Yandex DataLens, Looker Studio.
### Проекты

#### Проект 1: Калькулятор юнит-экономики онлайн-школы

Что нужно было сделать:

Задача №1.
Расчет суммы увеличения расходов на основных сотрудников (ФОТ) при условии, что маржинальность в месяце не должна упасть ниже 11%.

Задача №2.
Расчет маржинальности в месяце при условии падения доли бесплатных уроков на 10 процентных пунктов.

Задача №3.
Расчет увеличения маржинальности в месяце при условии увеличения среднего показателя ретеншн на два процентных пункта и выше.

Ссылка на проект:  
<p> Итоги:

<p> Итог №1. Если маржа составляет 11%, то возможно увеличить оплату ФОТ  на 100% (52,37%(ЗП учителей) - 22,78% (САС) - 11% (Маржа) = 13,85% - 10,99% = 2,86%).
<p> Итог №2. Маржинальность в расчетном месяце, пересчитанная с учётом уменьшившейся доли бесплатных уроков на 10% составила 0,02% (данный процент получился путем подставления пересчитанной выручки за расчетный месяц в сводную таблицу). 
<p> Итог №3. Расчеты показали, что увеличение Retention c 88,5% до 90,5% приведет к увеличению LTR на 12 тысяч рублей (с 58 тысяч р. в среднем до 70 тысяч р. в расчетном месяце), при этом маржинальность увеличится на 3,9%.

#### Проект 2: Визуализация данных по онлайн-школе в Excel

<p> Что нужно было сделать:
  
<p> Задача №1. Визуализировать расходы маркетинга и их эффективность в динамике по месяцам.
<p> Задача №2. Визуализировать доли уроков с разной ценой в динамике.
<p> Задача №3. Визуализировать динамику привлечения новых студентов по различным каналам. 
<p> Ссылка на проект:  
<p> Итоги:

<p> Итог №1. Визуализация данных на графике с суммарными расходами маркетинга на основной оси и CAC — на вспомогательной для оценки динамики CAC и объема маркетинговых расходов.
<p> Итог №2. Визуализация с помощью которой можно оценить доли уроков разных цен по времени.
<p> Итог №3. Визуализация, полученная из сырых данных с помощью сводной диаграммы о динамике привлечения новых студентов по каналам.


#### Проект 3: Сравнение и сопоставление средних чеков по группам животных 
<p> Что нужно было сделать: Сегментировать клиентские чеки в ветеринарной клинике с помощью применения параметрических гипотез статистического анализа.

<p> Задача №1. Построить сводную таблицу, по которой видно, какое количество заказов было для каждой пары животное - порода. Построить сводную таблицу, по которой видно, какой средний чек был для каждой пары животное - порода.
<p> Задача №2. Ответить на следующие вопросы, используя Анализ Данных в Excel:

<p> 1. Какой средний чек выше - по собакам или по кошкам?
<p> 2. Какой средний чек выше - по экзотическим животным или по домашним породистым кошкам?

<p> Ссылка на проект: 

<p> Итоги:

<p> Итог №1. Построено 2 сводных таблицы по количеству заказов по принципу животное - порода и по среднему чеку для каждой пары животное - порода.
 
<p> Итог №2. 
<p>    2.1 Выявлено, кошки домашние породистые дороже собак домашних породистых, а средний чек по непородистым кошкам и собакам примерно сопоставим.  Данный вывод сделан на основе проведенного  двухвыборочного t-теста с различными дисперсиями "кошки уличные vs собаки уличные". Вывод: т.к. мы находимся в интервале от -1.96 до 1.96, средние у нас равны. + Проведен  двухвыборочный t-тест с различными дисперсиями "кошки домашние обыкн. vs собаки дом обыкн." Вывод: т.к. мы находимся в интервале от -1.96 до 1.96, средние у нас равны.
<p>    2.2. Выявлено, что средний чек примерно равен по этим группам животных. Вывод сделан на основе проведенного  двухвыборочного t-теста с различными дисперсиями  - т.к. мы находимся в интервале от -1.96 до 1.96, средние у нас равны.
#### Проект 4: Моделирование изменения балансов студентов  онлайн школы и визуализация результатов в SQL

<p> Что нужно было сделать: Смоделировать изменение балансов (=  количество уроков) студентов с помощью SQL и написать запрос, который собирает данные о балансах студентов за каждый день.

<p> Задача №1. На основе таблиц Payments  и Classes создать несколько подзапросов с использованием CTE.  
<p> Задача №2. Создание визуализации (линейной диаграммы итогового результата).

<p> Ссылка на проект: 
<p> Итоги:

<p> Итог №1. В результате создана  CTE с вычисленными балансами каждого студента.  
<p> Итог №2. Создана визуализация балансов студентов.



Контактная информация
Egor koshelev . Email: 
