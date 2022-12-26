# Итоговая проверочная работа.

Данная работа необходима для проверки знаний и навыков по итогу прохождения первого блока обучения на программе разработчик.

Задача: Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решение не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.
 **Примеры:**

> ["hello", "2", "world", ":-)"] -> ["2",":-)"]

> ["1234", "1567", "-2", "computer science"] -> ["-2"]

> ["Russia", "Denmark", "Kazan"] -> []


## Описание алгоритма решения:
Объявляем два массива: arrya1 и вторый такой же длины (arrya2). Потом метод, в котором цикл соразмерный длине массива, внутри цикла проверка условия, если да - элемент первого массива заносится в count элемент второго массива. Переменная count нужна, чтобы поочередно закидывать элементы из первого массива во второй. После присвоения, увеличивается переменная count на 1 и возвращается к циклу for, в котором i увеличивается на 1. И так проверяется до конца.

## *Также представлена блок-схема алгоритма:*


![Блок схема](images/BS.PNG)