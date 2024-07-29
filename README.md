# Redis-memcached

Задание 1. Кеширование
Приведите примеры проблем, которые может решить кеширование.

Приведите ответ в свободной форме.

Ответ:

Проблемы, которые может решить кеширование:

Кеширование - это мощный инструмент, который позволяет оптимизировать работу приложений и систем, решая целый ряд проблем. Вот несколько примеров:

1. Снижение нагрузки на сервер:
- Если у вас есть популярный сайт или приложение, к которому часто обращаются, кеширование может значительно снизить нагрузку на ваш сервер. 
- Вместо того чтобы каждый раз обрабатывать запрос заново, вы можете получить данные из кэша, что ускорит процесс и сделает сайт более отзывчивым.

2. Улучшение скорости загрузки:
- Кеширование позволяет быстро доставить контент пользователю, сокращая время загрузки страницы.
- Это особенно важно для сайтов с большим количеством изображений, видео или других ресурсоемких элементов.

3. Сокращение сетевого трафика:
- Кеширование позволяет снизить количество запросов к внешним ресурсам, таким как базы данных или API.
- Это уменьшает сетевой трафик, что особенно актуально для мобильных устройств или в условиях ограниченного доступа к интернету.

4. Увеличение доступности:
- В случае сбоя сервера кешированные данные могут обеспечить доступность сайта или приложения. 
- Пользователи смогут продолжить работу, даже если сервер временно недоступен.

5. Создание более персонализированного опыта:
- Кеширование позволяет хранить информацию о предпочтениях пользователей, что позволяет предоставлять им более персонализированный опыт.
- Например, кеширование истории покупок позволяет показывать пользователям рекомендации, которые им могут понравиться.

6. Упрощение работы с API:
- Кеширование может помочь оптимизировать работу с API, сокращая количество запросов к серверу. 
- Это особенно важно, если вы работаете с API, которые имеют ограничения по количеству запросов.

7. Повышение производительности приложения:
- Кеширование позволяет снизить время выполнения задач, улучшая производительность приложения в целом.
- Это особенно важно для приложений с интенсивной обработкой данных.

8. Снижение затрат:
- Кеширование может помочь снизить затраты на серверные ресурсы, особенно если вы используете облачные сервисы.

В общем, кеширование - это ценный инструмент, который может решить множество проблем, связанных с производительностью, доступностью и масштабируемостью приложений и систем.

Задание 2. Memcached
Установите и запустите memcached.

Приведите скриншот systemctl status memcached, где будет видно, что memcached запущен.

Ответ:

![1](https://github.com/Evgenii199130/Redis-memcached/blob/main/img/22-16-22.png)

Задание 3. Удаление по TTL в Memcached
Запишите в memcached несколько ключей с любыми именами и значениями, для которых выставлен TTL 5.

Приведите скриншот, на котором видно, что спустя 5 секунд ключи удалились из базы.

Ответ:


