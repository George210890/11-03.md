# Домашнее задание к занятию "`ELK`" - `Кримчук Г.Б.`

### Задание 1

Запущенный Elastic

![elastic](https://github.com/SashkaSer/ELK/blob/main/img/Задание1.png)`

---

### Задание 2

Запрос GET /_cluster/health?pretty в Kibana

![GET](https://github.com/SashkaSer/ELK/blob/main/img/Задание2.png)`


---

### Задание 3

Отправка access-логов Nginx в Elasticsearch с помощью Logstash

![nginx](https://github.com/SashkaSer/ELK/blob/main/img/logstashnginx.png)`

Конфигурация logstash

![logstash](https://github.com/SashkaSer/ELK/blob/main/img/logstashconf.png)`

### Задание 4

Отправка логов от filebeat напрямую в Elastic

Логи с обработкой как это было в лекции

![beat1](https://github.com/SashkaSer/ELK/blob/main/img/filebeatnginx.png)`

Логи без обработки, где видно что они поступают с beat

![beat2](https://github.com/SashkaSer/ELK/blob/main/img/filebeattupe.png)`

Конфиг бита

![beat3](https://github.com/SashkaSer/ELK/blob/main/img/filebitnginxconf.png)`

---
## Дополнительные задания (со звездочкой*)

### Задание 5

Логи Apache beat


![beat1](https://github.com/SashkaSer/ELK/blob/main/img/apachebeat.png)`

![beat2](https://github.com/SashkaSer/ELK/blob/main/img/apachebeat2.png)`

Логи Apache logstash
![apache3](https://github.com/SashkaSer/ELK/blob/main/img/apache.png)`

Так же еще поигрался с логами докера

docker run -d --log-driver gelf --log-opt gelf-address=udp://192.168.0.202:15000 --name mysql -e MYSQL_ROOT_PA
SSWORD=1234 mariadb:latest


![docker](https://github.com/SashkaSer/ELK/blob/main/img/docker.png)`
