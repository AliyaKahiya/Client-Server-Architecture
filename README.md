# Client-Server-Architecture

1) Прочиать про клиент-серверную архитектуру

Клиент-серверная архитектура может состоять из следующих элементов: клиент, сервер и БД (база данных).

Клиент - это программа, с которой работает пользователь.

Сервер - это компьютер, на котором хранится само приложение, весь код, логика, дополнительные материалы и справочники.

БД - это хранилище данных.
 
В зависимости от количества элементов, клиент-серверная архитектура подразделяется на:

а) Двухзвенная архитектура - архитектура, которая состоит из клиента и сервера. В данном случае вся информация хранится в памяти сервера. Если сервер упадет или перезагрузится, все данные будут удалены.

b) Трехзвенная архитектура - архитектура, которая состоит из клиента, сервера и БД.

c) Многозвенная архитектура - архитектура, которая состоит из клиента, сервера, БД и дополнительных серверов.

Для предотвращения простоя при падении серверов и уменьшения нагрузки на сервер, используется кластер серверов. При использовании нескольких серверов, перед серверами ставится балансировщик и балансировщик отправляет запрос на тот сервер, который меньше всего загружен. Такая схема называется горячий резерв, т.е. имеется несколько серверов, работающих параллельно, и балансировщик распределяет нагрузку между ними. Также может быть применена схема холодного резерва, т.е. работает один сервер и если первый сервер выйдет из строя, только тогда балансировщик перенаправит нагрузку на второй сервер.

3) Что ткое HTTP и HTTPS

4) HTTP методы

5) HTTP статус коды сервера

7) Что такое ядро браузера 

7) Какие браузеры какиие ядра используют

8) Что такое API

9. Что такое ендпоинты

10) URL (URI, URL, URN)

11) Идемпотентные HTTP методы

12) Безопасные HTTP методы

13) Иденфикация, Аутентификация, Авторизация

14) Что такое IP

15) Что такое октаты в DNS

16) Что такое порт, сколько портов у Linux сервера

17) Уровни OSI

18) Хедеры http запросов
