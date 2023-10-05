# Домашнее задание к занятию "`Кеширование Redis/memcached`" - `Мурчин Артем`

### Задание 1. Кеширование
Приведите примеры проблем, которые может решить кеширование.

Приведите ответ в свободной форме.

### Решение 1

С помошью данных, сохраненных в кеше загрузка сайта будет проходить быстрее. За счет этого повышается производительность.

Также увеличивается скорость ответа.

Экономятся ресурсы базы данных, например, применяя кэширование тяжелых запросов.

Сглаживаются бусты трафика.

Понятие кэширования очень растяжимое. Под этим можно понимать: кэширование в DNS и CDN, HTTP-кэширование, кэш-процессора L1-L2-L3, тяжелые запросы в БД.

### Задание 2. Memcached

Установите и запустите memcached.

Приведите скриншот systemctl status memcached, где будет видно, что memcached запущен.

### Решение 2

### Задание 3. Удаление по TTL в Memcached
Запишите в memcached несколько ключей с любыми именами и значениями, для которых выставлен TTL 5.

Приведите скриншот, на котором видно, что спустя 5 секунд ключи удалились из базы.
### Решение 3

### Задание 4. Запись данных в Redis
Запишите в Redis несколько ключей с любыми именами и значениями.

Через redis-cli достаньте все записанные ключи и значения из базы, приведите скриншот этой операции.
### Решение 4

