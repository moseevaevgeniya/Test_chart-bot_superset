{
 "cells": [
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "##  <center> Пишем своего телеграм-бота :)</center>\n",
    "\n",
    "\n",
    "<img src=\"https://evilcoder.ru/wp-content/uploads/2017/09/TelegramMessenger.png\" width=100>"
   ]
  },
# wazzup  
product analyst job test  
## Тестовое задание №1   
#### Написать телеграм бота  
Исходные данные - сгенерированный случайный набор данных (история продаж) в
СУБД на выбор  
Технические требования к разработке:  
Наличие HTTP сервиса (Python), который имеет 2 метода:  
● добавить запись о продаже  
● получить данные о продажах за период  
В телеграм боте должны быть доступны 2 кнопки:  
● Внести данные о продаже  
● Получить отчет о продажах за период  
**Результат:**  
● [ссылка на файл](https://github.com/moseevaevgeniya/wazzup/blob/d2ef061b1901ac6308655b4d89f3a91853c3ba13/wizzard.ipynb)  
● [ссылка на бот](https://t.me/testwizzart_bot)

## Тестовое задание №2
#### Реализовать дашборд SuperSet с когортным анализом номенклатуры на выбор
[Исходные данные](https://drive.google.com/file/d/1bTCKuOnHLtRq-x3Oxxxe0YuLIM8wY-vZ/view?usp=sharing)
Сущности:: 
- `date` - первый день месяца,  
-  `lvl_5` - номенклатура,  
-   `card_id` - ключ покупателя,   
-   `checks` - количество уникальных чеков.  
**Технические требования:**
● SuperSet должен быть развернут через docker compose и доступен из интернета  
● В дашборде должен быть фильтр выбора номенклатуры для анализа  
● В случае невозможности развернуть SuperSet на личном ПК или отсутствия
белого IP адреса, можно воспользоваться бесплатным пробным периодом VDS
сервисов ( например https://serveroid.com/ru/trial.html или
https://sweb.ru/vds/free/ и прочие)  
● Если быстро развернуть SuperSet через docker compose не получается, то
можно воспользоваться облачной версией preset.io Набор данных -
подключение к PostgreSQL с параметрами: HOST 188.235.255.74 PORT 5432
DATABASE NAME test USERNAME candidate PASSWORD 12345candidate
DISPLAY NAME Postgre. Схема public, таблица ds.
Не забываем публиковать
дашборд.   
**Результат:**  
● [ссылка на дашборд](https://d28e6176.us1a.app.preset.io/superset/dashboard/8/?native_filters_key=DDLmTZHcUz-x-0l2r-m-tPQIW48zpeAWhN7QbVMT1_GAhGDuDaZF0fuPJpr13v-g)
