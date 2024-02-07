# M-estimators
В работе рассмотрены робастные M-методы оценивания параметров в линейной регрессионной модели с различными распределениями шумов, которые являются более устойчивыми к выбросам, чем МНК.

Рассмотренными М-оценками являются оценки Тьюки, Хьюбера, Коши и Вельша.

В качестве сравниваемой величины в моделируемых данных использовалась усредненная (по количеству моделирований) сумма квадратов отклонений оценок параметров.
На практических данных качество оценки определялось как сумма квадратов отклонений зависимой переменной.
В процессе исследования использовалась модель линейной регрессии с одной независимой переменной. Моделировались три распределения шумов: Тьюки, Стьюдента и двугорбое. Для усреднения результата для каждого набора изменяемых параметров реализация шумов и произведение над ней расчетов производилось многократно.
Матрица значений независимых переменных Х моделировалась единожды для всех моделирований выбросов, вектор оцениваемых коэффициентов α также являлся константным на протяжении работы.

В работе используются два датасета реальных данных: ирисы Фишера и данные о странах (ВВП на душу населения и безработица; данные с официального сайта Всемирного банка).
