
# Первая тестовая работа
- Создать репозиторий на GitHub
- Нарисовать блок-схему алгоритма (будет представлена блок-схема основного метода)
- Добавит файл README.md
- Написать программу для решения задачи
- Использовать контроль версий
___
#### Задача:
Написать программу, которая из имеющегося массива строк сформирует массив из строк, длина которых
меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать
на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись
исключительно массивами.

#### Примеры:
 - ```["hello", "2","world", ":-)"] -> ["2", ":-)"]```
 - ```["1234", "1567", "-2", "computer science"] -> ["-2"]```
 - ```["Russia", "Japan", "Africa"] -> []```
___

Программа для решения задачи реализована на языке C#.
    
    Для решения задачи было создано 3 метода:
        - RandomString()
        - FormOutString()
        - Print)

___
### Print(String[] strs)
    Метод для вывода в консоль элементов массива строк
#### Параметры:
- strs - массив строк


### FormOutString(String[] strs)
    Метод для формирования нового массива строк согласно условиям задачи.

    Возвращаемое значение типа String[] 
#### Параметры:
- strs - массив строк 

### RandomString()
    Метод для создания начального массива строк с помощью заполнения
    строчных элементов массива случайными символами

    Возвращает значение типа String[] 

___