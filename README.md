# Домашнее задание к занятию 2 "`«Кластеризация и балансировка нагрузки»`" - `Филон Андрей`

---

### Задание 1

    Запустите два simple python сервера на своей виртуальной машине на разных портах
    Установите и настройте HAProxy, воспользуйтесь материалами к лекции по ссылке
    Настройте балансировку Round-robin на 4 уровне.
    На проверку направьте конфигурационный файл haproxy, скриншоты, где видно перенаправление запросов на разные серверы при обращении к HAProxy.

### Ответ:  

![Ссылка на haproxy.cfg](https://github.com/AndreyFilon/nginx-haproxy/blob/main/1.1%20haproxy.cfg)
![Ссылка на скриншот](https://github.com/AndreyFilon/nginx-haproxy/blob/main/1.2%20check.jpg)
![Ссылка на скриншот](https://github.com/AndreyFilon/nginx-haproxy/blob/main/1.3%20check2.jpg)
![Ссылка на скриншот](https://github.com/AndreyFilon/nginx-haproxy/blob/main/1.4%20stats.jpg)

---

### Задание 2

    Запустите три simple python сервера на своей виртуальной машине на разных портах
    Настройте балансировку Weighted Round Robin на 7 уровне, чтобы первый сервер имел вес 2, второй - 3, а третий - 4
    HAproxy должен балансировать только тот http-трафик, который адресован домену example.local
    На проверку направьте конфигурационный файл haproxy, скриншоты, где видно перенаправление запросов на разные серверы при обращении к HAProxy c использованием домена example.local и без него.

### Ответ:

![Ссылка на haproxy.cfg](https://github.com/AndreyFilon/nginx-haproxy/blob/main/2.2%20haproxy-task2.cfg)
![Ссылка на скриншот](https://github.com/AndreyFilon/nginx-haproxy/blob/main/2.1.png)

---

