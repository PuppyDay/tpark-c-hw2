
# tpark-c-hw2
Вариант #30

В вашем распоряжении — массив из 10 млн. структур, содержащих числовой идентификатор записи (комментария) в социальной сети, 
а также поля с семантикой средней оценки (целое 0 или вещественное от 1,0 до 5,0), числа поданных голосов (неотрицательное целое),
даты выставления последней оценки и ее значения (целое от 1 до 5). Составьте наивный алгоритм подсчета записей с оценкой не ниже 4,0,
получивших хотя бы одну оценку за последний квартал, а затем реализуйте параллельный алгоритм с использованием нескольких процессов с
учетом возможной декомпозиции (разбиения) структуры и выравнивания результатов по линиям кэш-памяти.
