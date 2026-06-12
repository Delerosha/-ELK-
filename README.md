# Домашнее задание к занятию «ELK» Мальцев Андрей.

## 1. Elasticsearch
Установите и запустите Elasticsearch, после чего поменяйте параметр `cluster_name` на случайный.

## Решение:
<img width="1441" height="462" alt="Задание 1" src="https://github.com/user-attachments/assets/9a9e60ee-20db-429a-a686-ee44c36abee4" />


Приведите скриншот команды `curl -X GET 'localhost:9200/_cluster/health?pretty'`, сделанной на сервере с установленным Elasticsearch. Где будет виден нестандартный `cluster_name`.

## 2. Kibana
Установите и запустите Kibana.

Приведите скриншот интерфейса Kibana на странице `http://<ip вашего сервера>:5601/app/dev_tools#/console`, где будет выполнен запрос `GET /_cluster/health?pretty`.


## Решение: 
<img width="2488" height="688" alt="Задание 2" src="https://github.com/user-attachments/assets/949fd59f-5b51-4378-a35f-73f259fb8e76" />


## 3. Logstash
Установите и запустите Logstash и Nginx. С помощью Logstash отправьте access-лог Nginx в Elasticsearch.

Приведите скриншот интерфейса Kibana, на котором видны логи Nginx.


## Решение: 
<img width="2106" height="972" alt="Задание 3" src="https://github.com/user-attachments/assets/f3900de8-ce6f-4088-9cc8-46d5be858ecb" />


## 4. Filebeat
Установите и запустите Filebeat. Переключите поставку логов Nginx с Logstash на Filebeat.

Приведите скриншот интерфейса Kibana, на котором видны логи Nginx, которые были отправлены через Filebeat.


## Решение: 
<img width="2469" height="884" alt="Задание 4" src="https://github.com/user-attachments/assets/4ab55159-3495-4635-9621-07295b670d36" />
