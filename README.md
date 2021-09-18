# Middlewares

Stack of middlewares run on Docker by using docker-compose.

## Supported Middleware :white_check_mark:
| Name | Version | Port | Volume | Remark |
| ---- | ------- | ---- | ------ | ------ |
| ZooKeeper | 3.7.0 | 2181 | zookeeper:/data, zookeeper_log:/datalog | |
| ZooNavigator | 4.2.16 | 1812 | | |
| Kafka | 2.8.0 | 9092 | kafka:/bitnami/kafka | Kafka required ZooKeeper to work. |
| KafkaManager | 3.0.0.5-2 | 2909 | |
| Etcd | 3.5.0 | 2379, 2380 | etcd:/opt/bitnami | |
| EtcdKeeper | latest | 8081 | | |

## How to :question:
##### Using Docker Compose
``` bash
docker-compose up -d
```

__REMARK__
The volumes are obviously created, so it is no data lost even related containers are pruned.

## :heart: That's all. Enjoy! :heart:

## Buy me a :coffee:?
If you feel it is helpful :+1:, please consider to buy me a :coffee:!<br />
[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/T6T165VJF)


Thank you so much! :facepunch: