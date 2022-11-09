# Описание docker-compose
* здесь сделан упор на docker-compose*
Написан docker-compose выполняющий следующее:
1. Создается 3 контейнера nginx1 nginx2 grafana
2. Nginx1 прокидывается через порт 8001 на Grafana
3. Nginx2 прокидывается через порт 8002 на Grafana
4. Nginx1 и Nginx2 в разных сетях.
5. Healthcheck Nginx1 в контейнере с Grafana
6. Cоздан в композе раздел и подключен к 2м nginx (т.к. конфигурационный файл идентичен)
