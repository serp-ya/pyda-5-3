### Задание 1
Дан список вида:
data = [
[13, 25, 23, 34],
[45, 32, 44, 47],
[12, 33, 23, 95],
[13, 53, 34, 35],
]

Напишите функцию, которая возвращает сумму элементов на диагонали. Т. е. 13+32+23+35.

### Задание 2
Дан список чисел, часть из которых имеют строковый тип или содержат буквы. Напишите функцию, которая возвращает сумму квадратов элементов, которые могут быть числами.
data = [1, ‘5’, ‘abc’, 20, ‘2’]

### Задание 3
Напишите функцию, возвращающую сумму первых n чисел Фибоначчи

### Задание 4
Дан набор данных об обучении студентов на курсе программирования, который содержит: 1) имя 2) фамилию 3) пол 4) наличие у студента опыта в программировании 5) набор оценок за домашние работы 6) оценку за итоговую работу.
Напишите программу, которая будет принимать команду от пользователя и возвращать соотвествующий результат. Список команд: 1 - вывести на экран среднюю оценку за все ДЗ по группе и вывести на экран среднюю оценку за экзамен по группе; 2 - вывести среднюю оценку за ДЗ и за экзамен по группе в разрезе пола студентов 3 - вывести среднюю оценку за ДЗ и за экзамен в разрезе наличия опыта в программировании у студентов.
Прогрмма должна быть полностью декомпозирована на функции (кроме объявления функций и вызова итоговой функции в реализации ничего быть не должно).

students_list = [
{‘name’: ‘Василий’, ‘surname’: ‘Теркин’, ‘sex’: ‘м’, ‘program_exp’: True, ‘grade’: [8, 8, 9, 10, 9], ‘exam’: 9},
{‘name’: ‘Мария’, ‘surname’: ‘Павлова’, ‘sex’: ‘ж’, ‘program_exp’: True, ‘grade’: [7, 8, 9, 7, 9], ‘exam’: 8},
{‘name’: ‘Ирина’, ‘surname’: ‘Андреева’, ‘sex’: ‘ж’, ‘program_exp’: True, ‘grade’: [10, 9, 8, 10, 10], ‘exam’: 10},
{‘name’: ‘Татьяна’, ‘surname’: ‘Сидорова’, ‘sex’: ‘ж’, ‘program_exp’: True, ‘grade’: [7, 8, 8, 9, 8], ‘exam’: 8},
{‘name’: ‘Иван’, ‘surname’: ‘Васильев’, ‘sex’: ‘ж’, ‘program_exp’: True, ‘grade’: [9, 8, 9, 6, 9], ‘exam’: 10},
{‘name’: ‘Роман’, ‘surname’: ‘Золотарев’, ‘sex’: ‘ж’, ‘program_exp’: False, ‘grade’: [8, 9, 9, 6, 9], ‘exam’: 10}
]