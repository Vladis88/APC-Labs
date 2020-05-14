# APC-Labs
## Лабораторные работы по АПК (БГУИР 4 семестр)

### ЛР1 - вариант 9
9. F(x) = x / (|sin(x)| + 2)

### ЛР2 - вариант 13
13. Сформировать из двух массивов "минимальный"; (результат[i] = min(массив1[i],
массив2[i])). *pminub,pminsb,pminuw,pminsw
##### Результат работы ЛР2:
![Иллюстрация к проекту](https://github.com/Vladis88/APC-Labs/raw/master/Laba_2/Result/Результат_работы_программы.png)

### ЛР3 - вариант 27
27.Базовый вектор - 08H / B0Н. Под MS-DOS написать программу, которая:
1) выполняет инициализацию контроллера прерываний;
2) выводит на экран содержимое регистров запросов, обслуживаний и масок для ведущего и ведомого контроллеров (через видеобуфер).
3) При нажатии на клавиши меняется цвет или фон выводимой информации.
Программа должна быть резидентной. Все вектора прерываний переопределяются, новый базовый адрес выбирается в соответствии с вариантом.
##### Результат работы ЛР3:
![Иллюстрация к проекту](https://github.com/Vladis88/APC-Labs/raw/master/Laba_3/Result/Screenshot.png)
##### Видеодемонстрация:
<https://youtu.be/G81YZyDFZmI>

### ЛР4 - вариант 5
5. Частота, Гц (длительность, мс): 196 (400), 261 (400), 329 (400), 196 (400), 261 (400), 329 (400), 196 (400), 261 (400), 329 (400).
Я сделал мелодию на свой вкус, частоту и длительность старался оставить по заданию.

ЗАДАНИЕ
Под MS DOS написать программу, которая:
1) c помощью системного таймера генерирует звук заданной частоты (по вариантам);
2) выводит слово состояния для каждого канала в двоичном виде;
3) определяет коэффициент деления для каждого канала в 16-ричном виде.

*Реализовать генератор случайных чисел от нуля до заданного с клавиатуры числа.
##### Видеодемонстрация:
<https://www.youtube.com/watch?v=96WbSyKF3BE&feature=youtu.be>

### ЛР5 - один у всех
ЗАДАНИЕ
Под MS DOS написать программу, которая:
1) считывает и устанавливает время в часах реального времени;
2) реализует функцию задержки с точностью в миллисекунды;
3) реализует функции программируемого будильника.
##### Видеодемонстрация:
<https://www.youtube.com/watch?v=UQxuHJEiitU&feature=youtu.be> 

p.s использовалась виртуальная машина - "Oracle VM VirtualBox". Также программа WinImage для создания дискеты img в которой будет находиться .exe файл (наша скомпилированная программа), для далнейшего коннекта с виртуальной машиной. 

### ЛР6 - один у всех
ЗАДАНИЕ

Программируя клавиатуру, помигать её индикаторами (алгоритм мигания
произвольный).
Выводить на экран все коды возврата в 16-ричной форме.
