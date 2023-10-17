Задача: Написать программу, которая из имеющегося массива строк формирует новый массив из строк, длина которых меньше, либо равна 3 символам. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.
Примеры:
[“Hello”, “2”, “world”, “:-)”] → [“2”, “:-)”]
[“1234”, “1567”, “-2”, “computer science”] → [“-2”]
[“Russia”, “Denmark”, “Kazan”] → []

Шаг 1.
Задаём два массива: исходный и пустой результирующий.

Шаг 2.
Перебираем элементы исходного массива. Проверяем длину каждого элемента. Если длина элемента меньше или равна 3, добавляем этот элемент в результирующий массив.

Шаг 3.
Выводим результирующий массив.
