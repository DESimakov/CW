# CW
Здесь будут выкладываться файлы с продвижением в написании курсовой работы.
## Данные
1) [Сырые данные для разных ставок](https://github.com/DESimakov/CW/blob/master/mosprime.csv) 
2) [Данные для MOSPRIME 3m полные с 01-09-2007 по 22-12-2017](https://github.com/DESimakov/CW/blob/master/mosprime3m.csv)
3) [Данные для MOSPRIME 3m средние с 01-04-2010 по 01-04-2013](https://github.com/DESimakov/CW/blob/master/mosprime3m_between.csv)
4) [Данные для MOSPRIME 3m короткие с 02-04-2012 по 31-08-2012](https://github.com/DESimakov/CW/blob/master/mosprime3m_short.csv)
## Визуализация данных
Графики данных. Сравнение разных временных отрезков, их гистограммы. Месячное скользящее среднее для ставки, ее волательности. [Ноутбук](https://github.com/DESimakov/CW/blob/master/CW_data_and_visualisation.ipynb) 
## Калибровка ошибки MAPE
Для моделей Мертона и однофакторной Халла-Вайта найдены оптимальные параметры путем минимизации ошибки MAPE. [Ноутбук](https://github.com/DESimakov/CW/blob/master/CWm-calibration_MAPE.ipynb)
## Калибровка при помощи максимизации правдоподобия
Для моделей Мертона и однофакторной Халла-Вайта найдены оптимальные параметры путем максимизации функции правдоподобия. Определение влияния начального приближения. [Ноутбук](https://github.com/DESimakov/CW/blob/master/CWm-calibration_ML.ipynb)
## Использование пакета Quant-Lib (искусственный пример)
Калибровка параметров HW1f по цене свапциона. [Ноутбук](https://github.com/DESimakov/CW/blob/master/CW_QuantLib.ipynb)
## Ближайшее:
Посмотреть на <a href="https://www.codecogs.com/eqnedit.php?latex=\theta(t)&space;=&space;const" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\theta(t)&space;=&space;const" title="\theta(t) = const" /></a> . Сделать алгоритм, который подбирает параметры по заданной волатильности (в два шага). Подбор начального приближения. Случайная выборка параметров в правдоподобии. Другие способы оптимизации.
