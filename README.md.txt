﻿Тесты на проверку параметра firstName при создании пользователя в Яндекс.Прилавок с помощью API Яндекс.Прилавок.
Автоматизировать проверки по чек-листу для поля name в запросе на создание набора

Подключены пакеты:
pytest, requests

Шаги тестирования:
Выполнить запрос на создание нового пользователя и запомнить токен авторизации authToken.
Выполнить запрос на создание личного набора для этого пользователя. Передать заголовок Authorization.
Для проверок по чек-листу создать функцию, которая будет менять содержимое тела запроса.
Логику позитивных и негативных проверок по чек-листу вынести в отдельные функции.