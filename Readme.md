
Здравствуйте. Итоговый проект. 
@@@@  Блок схема находится в картинке под названием 222.png

Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символам. 
Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма.

*Примеры:*

*["hello","2","world",":-)",]->["2",":-)"]*

*["1234","1567","-2","computer scince"]->["-2"]*

*["Russia","Denmark","Kazan"]->[]* 


Приложение состоит из четырех методов

1. Метод определения размера массива, который предстоит сформровать *SearchValidSizeArray*. 
В качестве аргументов на вход метод принимает первоначальный одномерный массив строк и целочисленное значение количества символов в строках искомого массива.
Цикл *for* считает количество пустых элементов массива, вне цикла определяется число валидных элементов, которые возвращаются из метода целочисленным значением *validSizeArray*;  
2. *Основной метод решения задачи.
Метод формирования массива из строк, длина которых меньше либо равна заданному количеству символов *GetLimitLengthElementArray*.
В данном методе используется принцип цикла в цикле, где внутренний цикл фиксирует индекс искомого элемента массива, а внешний - запоняет итоговый массив. 
На вход метод принимает первоначальный массив, количество символов строк искомого массива и число валидных элементов, найденное предыдущим методом.
На выходе возвращается итоговый массив. 
3. Метод вывода массива на экран состоит из цикла *for* и операторов вывода текста и значения объектов в текстовое представление в выходной поток. Для вывода используя визуальный формат из примеров задачи. 
На вход метод принимает одномерный массив строк.
На старте выполнения алгоритма метод использутся дважды: для отображения первоночального и итогового массивов. 
4. Метод ввода первоначального массива с клавиатуры предлагает пользователю ввести массив самостоятельно, изначально определившись с его длиной. 
Проверить работу приложения можно как с его помощью, так и через "// закомментированные" массивы из примеров задачи. 


