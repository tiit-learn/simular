# Simular finder
Скрипт парсер, с возможностью сбора данных, храннеие в sqlite и сохранением на
указанный проект. Для этого, проект должен соответсвовать требованиям заказчика.

![Main Logo](/img/1.png)

0. Авторизация
    0.1 Проверка куки
    0.2 Сохранение куки в файл

1. Ищет по домену на указанном сайте
    1.1 Вывод Результатов поиска
2. Ищет в БД по хешу скриншота главной странице сайта # find_simular_db_from_url()
    2.1 Вывод результатов поиска # return -> img_hash
3. Работа с БД и проектом по отдельности

![Same work](/img/2.png)

Для работы необходим файл с конфигурациями социальных сетей.
