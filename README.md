<img src ="https://evilcoder.ru/wp-content/uploads/2017/09/TelegramMessenger.png" width=100>"

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

<main>
  <svg class="lp" viewBox="0 0 128 128" width="128px" height="128px" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <linearGradient id="grad1" x1="0" y1="0" x2="0" y2="1">
        <stop offset="0%" stop-color="#000" />
        <stop offset="100%" stop-color="#fff" />
      </linearGradient>
      <mask id="mask1">
        <rect x="0" y="0" width="128" height="128" fill="url(#grad1)" />
      </mask>
    </defs>
    <g fill="none" stroke-linecap="round" stroke-width="16">
      <circle class="lp__ring" r="56" cx="64" cy="64" stroke="#ddd" />
      <g stroke="hsl(183,90%,40%)">
        <polyline class="lp__fall-line" points="64,8 64,120" />
        <polyline class="lp__fall-line lp__fall-line--delay1" points="64,8 64,120" />
        <polyline class="lp__fall-line lp__fall-line--delay2" points="64,8 64,120" />
        <polyline class="lp__fall-line lp__fall-line--delay3" points="64,8 64,120" />
        <polyline class="lp__fall-line lp__fall-line--delay4" points="64,8 64,120" />
        <circle class="lp__drops" r="56" cx="64" cy="64" transform="rotate(90,64,64)" />
        <circle class="lp__worm" r="56" cx="64" cy="64" transform="rotate(-90,64,64)" />
      </g>
      <g stroke="hsl(93,90%,40%)" mask="url(#mask1)">
        <polyline class="lp__fall-line" points="64,8 64,120" />
        <polyline class="lp__fall-line lp__fall-line--delay1" points="64,8 64,120" />
        <polyline class="lp__fall-line lp__fall-line--delay2" points="64,8 64,120" />
        <polyline class="lp__fall-line lp__fall-line--delay3" points="64,8 64,120" />
        <polyline class="lp__fall-line lp__fall-line--delay4" points="64,8 64,120" />
        <circle class="lp__drops" r="56" cx="64" cy="64" transform="rotate(90,64,64)" />
        <circle class="lp__worm" r="56" cx="64" cy="64" transform="rotate(-90,64,64)" />
      </g>
    </g>
  </svg>
</main>
