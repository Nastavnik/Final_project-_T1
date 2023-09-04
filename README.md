# Final_project-_T1
Проект № 5
Служба такси.

Все операции должны считаться локально.
Данные - Служба такси 

Есть таблица, состоящая из поездок такси в Нью-Йорке.\
Поле - Описание\
VendorId - ИД компании\
Trep_pickup_datetime - Время и дата, когда пассажир сел в такси\
Trep_dropoff_datetime - Время и дата, когда пассажир вышел из такси\
Passanger_count - Количество пассажиров\
Trip_distance -Пройденное расстояние\
Ratecodeid -Код скорости\
Store_and_fwd_flag - Флаг, отвечающий за сохранение записи поездки перед ее отправкой поставщику\
PulocationId - Широта, где была начата поездка\
Dolocationid - Долгота, где была начата поездка\
Payment_type - Тип оплаты\
Fare_amount - Стоимость поездки\
Mta_tax - Комиссия автопарка\
Tip_amount -Чаевые\
Tools_amount - Оплата за платные дороги\
Improvement_surchange - Доплата за страховку\
Total_amount - Полная стоимость поездки\
Congestion_surchange -Дополнительный сбор\

Необходимо, используя таблицу поездок для каждого дня, рассчитать процент поездок по количеству человек в машине (без пассажиров, 1, 2, 3, 4 и более пассажиров). По итогу должна получиться таблица (parquet) с колонками date, percentage_zero, percentage_1p, percentage_2p, percentage_3p, percentage_4p_plus. Технологический стек — sql, scala (что-то одно). 
Также добавить столбцы к предыдущим результатам с самой дорогой и самой дешевой поездкой для каждой группы.\

Дополнительно: также провести аналитику и построить график на тему «Как пройденное расстояние и количество пассажиров влияет на чаевые» в любом удобном инструменте.

решение

