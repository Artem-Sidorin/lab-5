# lab-5
Динамические языки программирования

1 Считать в pandas DataFrame любой источник данных: CSV, JSON, Excel-файл, HTML-таблицу, встроенный датасет sklearn. Опишите ваши данные, что обозначает каждый столбец, какого типа (категориальный, вещественный, целочисленный, бинарный) данный столбец, при необходимости для категориальных в том числе бинарных признаков привести расшифровку их значений. В общем, проведите "визуальный" анализ ваших данных.

2 Выполните с датафреймом следующие операции (многие операции можно совершить не одним способом, используйте все известные вам способы, поищите/придумайте новые способы) :

2.1 вывод таблицы

2.2 вывод первых 5 элементов таблицы

2.3 вывод последних 5 элементов таблицы

2.4 использовать функцию describe()

2.5 считывание значения конкретной ячейки (с конкретным индексом из конкретной колонки) всеми известными вам способами

2.6 фильтрация строк по диапазону индекса

2.7 фильтрация набора данных по какому-либо условию

2.8 работа с пропущенными значениями (если они есть): удаление строк с пропущенными значениями, заполнение пропущенных значений средним значением по колонке. Если пропущенных значений нет — намеренно их "генерируете", прибивая какие-то куски данных в np.nan

2.9. создание нового поля вычисленного на основе значений других полей:

2.9.1 через выражение на базе имеющихся колонок,

2.9.2 через DataFrame.apply

2.9.3 через Series.apply

2.10 сортировка по какому-либо из полей

2.11 вычислить несколько статистик по колонкам (используйте встроенные агрегатные функции — любые на выбор)

2.12 .value_counts()

2.13 Вывод уникальных значений колонки через .unique()

2.14 Удалите текущий индекс и создайте новый индекс на базе новой колонки, которая для этого лучше всего подходит
