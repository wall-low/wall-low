<div align="center">

# Данила Валов

**Java-разработчик**

[![Telegram](https://img.shields.io/badge/Telegram-@wall__low-26A5E4?logo=telegram&logoColor=white)](https://t.me/wall_low)
[![Email](https://img.shields.io/badge/edinorog2005@yandex.ru-CC0000?logo=maildotru&logoColor=white)](mailto:edinorog2005@yandex.ru)

</div>

---

Учусь в магистратуре, ищу работу Java-разработчиком.

Пишу бэкенд на Spring Boot: авторизация через JWT, REST API, работа с базой через JPA,
кэш на Redis. Умею довести проект до работающего сервиса — спроектировать схему данных,
собрать окружение в Docker, развернуть на VPS и подключить клиент.

Кроме Java работал с Laravel и Flutter. Дипломный проект — мобильное приложение
с собственным бэкендом, который я сам поднимал и администрировал.

---

## Стек

**Основное**

![Java](https://img.shields.io/badge/Java-ED8B00?logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?logo=springsecurity&logoColor=white)
![Hibernate](https://img.shields.io/badge/JPA_/_Hibernate-59666C?logo=hibernate&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white)

**Инфраструктура**

![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Gradle](https://img.shields.io/badge/Gradle-02303A?logo=gradle&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux_/_VPS-FCC624?logo=linux&logoColor=black)

**Также работал с**

![Flutter](https://img.shields.io/badge/Flutter-02569B?logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?logo=dart&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?logo=php&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?logo=laravel&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white)

---

## Проекты

### [TuneVault — своё музыкальное хранилище](https://github.com/wall-low/TuneVault)
`Java 25` `Spring Boot 4` `PostgreSQL` `Docker` `PWA`

Заливаешь свои MP3, слушаешь с любого устройства, раздаёшь доступ друзьям.
Стриминг с настоящей перемоткой — сервер отдаёт файл кусками по заголовку `Range`.
Повторные загрузки не плодят копии: считается отпечаток содержимого, и если такой
уже есть, файл на диск не пишется. Подборки, история прослушиваний с агрегатами
по темам, разбор ID3-тегов. 17 тестов.

### [Spring Boot JWT Authentication](https://github.com/wall-low/JWT)
`Java` `Spring Boot` `Spring Security` `JPA`

Пара access и refresh токенов, отзыв токена при выходе через чёрный список.
Список чистится по расписанию — иначе он растёт бесконечно, а поиск по нему идёт
при каждом обновлении сессии. Валидация входных данных, единый формат ошибок.
Тесты проверяют и то, что защиту нельзя обойти: токен с чужой подписью отвергается.

### [Titanic II — бронирование кают](https://github.com/wall-low/titanic2-booking)
`Laravel` `MySQL` `Docker`

Система продажи билетов на круиз. Моя часть — выбор кают на схеме палубы, оформление
заказа и оплата, система лояльности со скидками. Отдельно решал классическую задачу
бронирования: билет удерживается за пользователем, а неоплаченный заказ через 10 минут
автоматически отменяется по cron, возвращая место в продажу.
Командный проект, 58 коммитов из 109.

### [Учёба рядом — поиск репетиторов](https://github.com/wall-low/MyDiplomProject)
`Flutter` `PocketBase` `Docker` `VPS`

Дипломный проект. Ученик бронирует занятия в расписании репетитора, общается в чате
с голосовыми сообщениями и файлами, оплачивает и оставляет отзыв. Бэкенд поднимал
и администрировал сам — PocketBase в Docker на VPS, схема из девяти коллекций.

### [Cipher — криптографические алгоритмы](https://github.com/wall-low/Cipher)
`Java` `JUnit 5` `Gradle`

Шифр Цезаря, симметричный шифр на XOR с перестановками и RSA — всё написано руками,
включая расширенный алгоритм Евклида. 21 тест.

Тесты нашли настоящую дыру: ключ накладывался дважды за раунд, и при некоторых длинах
текста два наложения гасили друг друга. Шифр вырождался в перестановку букв, и
сообщение читалось любым ключом подходящей длины.

---

<div align="center">

**Открыт к предложениям и стажировкам**

[![Telegram](https://img.shields.io/badge/Написать_в_Telegram-26A5E4?logo=telegram&logoColor=white)](https://t.me/wall_low)

</div>
