# Скрипт для обновления Интернет магазина

![img_1.png](img_1.png)

### Предметная область

Скрипт производит синхронизацию продукции с сайта https://timeworld.ru и интернет магазинов на https://ozon.ru и https://market.yandex.ru 

### Как запустить

Для запуска сайта вам понадобится Python третьей версии.
Скачайте код с GitHub.

Запустите скрипт

```sh
python3 seller.py
```

```sh
python3 market.py
```

### Переменные окружения

Настройки скрипта **seller.py** берётся из переменных окружения.
Создайте файл `.env` и запишите туда данные в формате: `ПЕРЕМЕННАЯ=значение`.
Доступны 2 переменные:
- `SELLER_TOKEN=` 
- `CLIENT_ID=` 

Настройки скрипта **market.py** берётся из переменных окружения.
Создайте файл `.env` и запишите туда данные в формате: `ПЕРЕМЕННАЯ=значение`.
Доступны 5 переменных:
- `MARKET_TOKEN=` 
- `FBS_ID=` 
- `DBS_ID=` 
- `WAREHOUSE_FBS_ID=` 
- `WAREHOUSE_DBS_ID=` 

#### Автор
**3atomiс** - *Цель проекта* - Код написан в образовательных целях на онлайн-курсе для веб-разработчиков [Devman](https://dvmn.org)
