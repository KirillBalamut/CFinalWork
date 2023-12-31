
# Итоговоя проверочная работа #

## Задача ##

Написать программу, которая из имеющегося массива из строк, длинна которохменьше либо равнв 3 символам.
Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения аогоритма.

*При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.*

## Алгоритм решения ##

1. Перебираем значения исходного массива.
2. Проверяем каждое знаение массва по очереди на соответствие условию: длинна строки меньше или равна трем (3).
3. Если условия выполняются выбранной строкой из исходного массива то данное значение кладем в новый массив.
4. Повторяем пункты 2 и 3 до тех пор пока не достигнем конца исходного массива.
5. Возращаем новый заполненый массив как результат.

## Блок схема ##

Блок схема находится в папке BlockDiagram.
![блок-схема алгоритма](./BlockDiagram/algorithms.png)

## Программа ##

Программа расположена в папке Programs. Задача: Написать программу, которая из имеющегося массива строк формирует новый массив из строк, длина которых меньше, либо равна 3 символам. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.
. Для ее запуска неопходимо перейти в соответствующую папку и за пустить программу через терминал : *dotnet run*

После чего программа запросит ввести значения через пробел, нпример: Введите значения через запятую: 1223,123,32,qwe,qwerty
Пример вывода программы: [1223,123,32,qwe,qwerty] -> [123,32,qwe]
