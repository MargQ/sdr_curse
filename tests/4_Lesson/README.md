# Занятие 4
## Изучение основных свойств ДПФ с помощью моделирования в  Python/Spyder

**Цель работы:**
Целью работы является изучение основных свойств дискретного преобразования Фурье с помощью моделирования в среде Python/Spyder.

**Задание**
1. Для заданных значений частоты сигнала и частоты дискретизации получите дискретное колебание, отсчеты посмотрите в Variable Explorer. Далее увеличьте частоту сигнала в несколько раз, при этом так же увеличится и частота дискретизации, но отношение частоты сигнала и частоты дискретизации - нормированная частота останется той же величиной.
Сравните дискретные отсчеты первого и второго сигналов.

![](https://github.com/MargQ/sdr_curse/blob/master/4_Lesson/Screenshots/1.png)
![](https://github.com/MargQ/sdr_curse/blob/master/4_Lesson/Screenshots/11.png)
![](https://github.com/MargQ/sdr_curse/blob/master/4_Lesson/Screenshots/111.png)
![](https://github.com/MargQ/sdr_curse/blob/master/4_Lesson/Screenshots/1111.png)

2. Вычислите шаг частот между точками ДПФ ∆f =fs/N. Определите, в  какой точке ДПФ находится заданный сигнал.

```sh
∆f=320/256=1.25
```

3. Измените частоту сигнала в целое чисто раз,определите номер точки ДПФ для данного сигнала.

```sh
∆f=320/256=1.25
```

4. Измените количество точек ДПФ до 512. Вычислите шаг частот между точками ДПФ ∆f = fs/N. Определите, в какой точке ДПФ находится заданный сигнал. (файл 4.py)

```sh
∆f = fs/N = 320/512=0.625
```

5. Задайте сигнал в виде суммы двух колебаний.Вычислите ДПФ сигнала.(файл 5.py)

![](https://github.com/MargQ/sdr_curse/blob/master/4_Lesson/Screenshots/51.png)

![](https://github.com/MargQ/sdr_curse/blob/master/4_Lesson/Screenshots/52.png)

6. Вычислите ОДПФ сигнала, заданного в частотной области в виде X=np.array([0,0,1,0,0,0,0,0]).

![](https://github.com/MargQ/sdr_curse/blob/master/4_Lesson/Screenshots/61.png)

Задавайте ненулевое значение в различных разрядах.

![](https://github.com/MargQ/sdr_curse/blob/master/4_Lesson/Screenshots/611.png)

Также задайте значение в комплексной форме X=np.array([0,0,1j,0,0,0,0,0]).
 
![](https://github.com/MargQ/sdr_curse/blob/master/4_Lesson/Screenshots/62.png)
 
Поменяйте знак мнимой единицы.

![](https://github.com/MargQ/sdr_curse/blob/master/4_Lesson/Screenshots/622.png)

Задайте спектр ДПФ в виде X=np.array([0,0,2-1j,0,0,0,0,0]) поменяйте знак мнимой 

![](https://github.com/MargQ/sdr_curse/blob/master/4_Lesson/Screenshots/63.png)

## Работа с SDR

Получен спектр сигнала изменяющегося во времени

![](https://github.com/MargQ/sdr_curse/blob/master/4_Lesson/Screenshots/sdr_1.jpg)
![](https://github.com/MargQ/sdr_curse/blob/master/4_Lesson/Screenshots/sdr_2.jpg)



