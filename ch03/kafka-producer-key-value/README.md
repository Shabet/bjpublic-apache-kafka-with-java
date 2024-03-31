```
데이터 확인
bin/kafka-console-consumer.sh --bootstrap-server my-kafka:9092 --topic test --property print.key=true --property key.seperator="-" --from-beginning
```