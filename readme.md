**Задача:** 

_Написать программу, которая из имеющегося массива строк формирует новый массив из строк, длина которых меньше, либо равна 3 символам. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами._


>Блок-схема алгоритма находится в файле _**Diagram.png**_


Для решения этой задачи мною задан массив строк, а также новый массив (временный), размер которого соответствует размеру первого массива. 

Затем, проходя в цикле по первому массиву, записываю в новый массив те элементы, которые соответствуют условию (<= 3 символов). 

Для нового массива заведена переменная j, которая увеличивается на 1 при записи элемента в массив, благодаря чему элементы записываются во временный массив из первоначального массива по порядку и мы можем узнать количество элементов для итогового массива, в котором исключим пустые строки при их наличии.

Когда программа выходит из цикла, ввожу еще одну переменную k = 0. Запускается новый цикл от k до j, чтобы заполнить итоговый массив соответствующими элементами из временного массива. Если таких нет, то вывожу в консоль сообщение об их отсутствии. 

Для вывода массива в консоль использован метод для печати одномерного массива.
