```
토픽 생성
bin/kafka-topics.sh --bootstrap-server my-kafka:9092 --create --topic test --partitions 3

데이터 확인
bin/kafka-console-consumer.sh --bootstrap-server my-kafka:9092 --topic test --from-beginning
```