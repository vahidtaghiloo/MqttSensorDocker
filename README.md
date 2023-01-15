# MqttSensorDocker
mqtt, telegraf, influxdb, grafana, docker compose sensor data logger

# How it works
Telegraf agent reads mqtt data and writes it into influxdb database. Grafana
is used to demonstrate live data.

Quectel M65 module was used as IOT node and sht35 was used as temp/humidity sensor. 

# How to run
Insert token created with influxdb into telegraf.conf

```
$ docker compose up -d
```

# To Do:
+ A detailed blog post