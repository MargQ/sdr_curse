# Занятие 10
## Квадратурная IQ модуляция. Общая схема формирования и приема сигналов с дискретной модуляцией. Дискретная АМ, формирование символов в формирующем фильтре, прием сигналов.

**Задание**: 
- Изучить корреляцию кода Баркера 

код Баркера из 5 значений

```sh
x = np.array([+1, +1, +1, -1, +1]) # код Баркера из 5 значений
y = np.correlate(a,a,'full') # подсчёт корреляции
```
![](https://github.com/MargQ/sdr_curse/blob/master/10_Lesson/Screenshots/1.png)

код Баркера из 11 значений

```sh
x = np.array([+1, +1, +1, -1, -1, -1, +1, -1, -1, +1, -1]) # код Баркера из 11 значений
y = np.correlate(a,a,'full') 
```
![](https://github.com/MargQ/sdr_curse/blob/master/10_Lesson/Screenshots/2.png)

- Рассмотреть сигнал из лекции. Передать и получить его.

Переданные значения

![](https://github.com/MargQ/sdr_curse/blob/master/10_Lesson/Screenshots/3.png)
 
 

