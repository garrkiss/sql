# Домашнее задание к занятию "`SQL. Часть 1`" - `Бакулев Евгений`

### Задание 1
### Что нужно сделать:

1. Получите уникальные названия районов из таблицы с адресами, которые начинаются на “K” и заканчиваются на “a” и не содержат пробелов.

### Решение 1

```
CREATE USER sys_temp IDENTIFIED BY '571802gg';
GRANT ALL PRIVILEGES ON  * . *  TO sys_temp;
```

![Скрин](https://github.com/garrkiss/ddl_mdl/blob/main/img/%D0%B7%D0%B0%D0%BF%D1%80%D0%BE%D1%81%20%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D1%82%D0%B5%D0%BB%D1%8F.png)
![Скрин](https://github.com/garrkiss/ddl_mdl/blob/main/img/%D0%BF%D1%80%D0%B8%D0%B2%D0%B8%D0%BB%D0%B5%D0%B3%D0%B8%D0%B8.png)
![Скрин](https://github.com/garrkiss/ddl_mdl/blob/main/img/%D1%81%D1%85%D0%B5%D0%BC%D0%B0.png)

### Задание 2
### Что нужно сделать:

1. Получите из таблицы платежей за прокат фильмов информацию по платежам, которые выполнялись в промежуток с 15 июня 2005 года по 18 июня 2005 года включительно и стоимость которых превышает 10.00.

```
Название таблицы | Название первичного ключа
customer         | customer_id
```

### Решение 2

```
Название таблицы | Название первичного ключа
actor	         | actor_id   
address	         | address_id
category	 | category_id
city	         | city_id
country	         | country_id
customer         | customer_id
film	         | film_id
film_actor	 | actor_id film_id
film_category	 | film_id category_id
film_text	 | film_id
inventory   	 | inventory_id
language	 | language_id
payment	         | payment_id
rental	         | rental_id
staff	         | staff_id
store	         | store_id
```


### Задание 3
### Что нужно сделать:

1. Получите последние пять аренд фильмов.


### Решение 3


### Задание 4
### Что нужно сделать:

1. Одним запросом получите активных покупателей, имена которых Kelly или Willie.Сформируйте вывод в результат таким образом:
все буквы в фамилии и имени из верхнего регистра переведите в нижний регистр,
замените буквы 'll' в именах на 'pp'.

### Решение 4
