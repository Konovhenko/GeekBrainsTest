# Итоговая контрольная работа по основному блоку

## Задание 

_1. Создать репозиторий на GitHub
2. Нарисовать блок-схему алгоритма (можно обойтись блок-схемой основной содержательной части, если вы выделяете её в отдельный метод)
3. Снабдить репозиторий оформленным текстовым описанием решения (файл README.md)
4. Написать программу, решающую поставленную задачу
5. Использовать контроль версий в работе над этим небольшим проектом (не должно быть так, что всё залито одним коммитом, как минимум этапы 2, 3, и 4 должны быть расположены в разных коммитах)_

## Задача: 
*Написать программу, которая из имеющегося массива строк формирует новый массив из строк, длина которых меньше, либо равна 3 символам. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.*

![загружено.png](загружено.png)

## Решение
__Приведенный код представляет собой консольное приложение на языке C#, которое считывает введенные пользователем данные в виде строки, разделенной запятыми, с помощью метода ReadeConsole(string message), преобразует его в массив отдельных строк с помощью метода Split(','), отфильтровывает короткие строки с помощью метода FilterShortStrings(string[] arr, int length), а затем отображает конечный результат в окне консоли с использованием метода PrintResult(string[] strs).__
