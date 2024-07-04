# show tables
show tables;

# delete table
DROP TABLE favorite_food;

# show column in table
desc customer;

# Предложения запроса
    -select Определяет, какие столбцы следует включить в результирующий набор запроса
    Определяет таблицы, из которых следует выбирать данные, а также таблицы,
    которые должны быть соединены
    -where Отсеивает ненужные данные
    -group by Используется для группировки строк по общим значениям столбцов
    -having Отсеивает ненужные данные
    -order by Сортирует строки окончательного результирующего набора по одному или
    нескольким столбцам
# example

select language_id,
-> 'COMMON' language_usage,
-> language_id * 3.1415927 lang_pi_value,
-> upper(name) language_name
-> from language;

# example 
SELECT version(),
user(),
database();

# get unique record and sort by id
select distinct actor_id from film_actor order by actor_id;



