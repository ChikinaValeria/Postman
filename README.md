SHOP
===========

Коллекция состоит из двух независимых запросов к онлайн-магазину.

Тест кейсы
-----------

Проект содержит следующие запросы:

+ Создание нового товара (POST)
+ Поиск товара по наименованию (GET)

Интересные факты о коллекции:
-----------

+ На вкладке pre-requests создана функция-рандомайзер
+ Подготовка данных в пре-реквест скриптах
+ Цена товара и выбор его цвета определяются рандомно
+ Циклическая отправка запросов на создание товара на стадии pre-requests
+ Сгенерированные на вкладке pre-requests значения сохранены в переменные окружения
+ Параметры запроса заполняются из переменных окружения, а также с помощью встроенных функций рандома Postman
+ На вкладке Tests выполняется валидация JSON-схемы несколькими способами
+ После выполнения проверок выполняется очистка переменных окружения
+ После выполнения проверок выполняется удаление из базы ранее созданных объектов


Suggestions
===========
Коллекция независимых запросов к системе подсказок по именам и фамилиям.

Интересные факты о коллекции:
-----------

В запросах на вкладке Tests проверяется:
+ является ли та или иная часть ответа массивом/объектом;
+ имеется ли искомый вариант ответа среди всех вариантов (перебором);
+ JSON схема;
+ ответ в формате xml;
+ поиск нужных элементов в ответе с помощью For и forEach.
