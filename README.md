# Домашнее задание к занятию "`ELK`"
# Халатов Александр

### Задание 1. Elasticsearch 

Установите и запустите Elasticsearch, после чего поменяйте параметр cluster_name на случайный. 

*Приведите скриншот команды 'curl -X GET 'localhost:9200/_cluster/health?pretty', сделанной на сервере с установленным Elasticsearch. Где будет виден нестандартный cluster_name*.

### *Ответ:*

![1](https://github.com/IMiroxxI/ELK/blob/main/img/1.1.png)

---

### Задание 2. MKibana

Установите и запустите Kibana.

*Приведите скриншот интерфейса Kibana на странице http://<ip вашего сервера>:5601/app/dev_tools#/console, где будет выполнен запрос GET /_cluster/health?pretty*.

### *Ответ:*

![2](https://github.com/IMiroxxI/ELK/blob/main/img/2.1.png)

---

### Задание 3. Logstash

Установите и запустите Logstash и Nginx. С помощью Logstash отправьте access-лог Nginx в Elasticsearch. 

*Приведите скриншот интерфейса Kibana, на котором видны логи Nginx.*

### *Ответ:*

Отправка access-логов Nginx в Elasticsearch с помощью Logstash
![3.1](https://github.com/IMiroxxI/ELK/blob/main/img/3.1.png)

Конфигурация Logstash
![3.2](https://github.com/IMiroxxI/ELK/blob/main/img/3.2.png)

---

### Задание 4. Filebeat. 

Установите и запустите Filebeat. Переключите поставку логов Nginx с Logstash на Filebeat. 

*Приведите скриншот интерфейса Kibana, на котором видны логи Nginx, которые были отправлены через Filebeat.*

### Ответ:

![4](https://github.com/IMiroxxI/ELK/blob/main/img/4.1.png)

---
