# kafkacat

> Apache Kafka 生产消费工具

- 使用以最新偏移量开头的消息：

`kafkacat -C -t {{topic}} -b {{brokers}}`

- 使用从最早的偏移量开始的消息，并在收到最后一条消息后退出：

`kafkacat -C -t {{topic}} -b {{brokers}} -o beginning -e`

- 将消息作为 Kafka 消费者群体使用：

`kafkacat -G {{group_id}} {{topic}} -b {{brokers}}`

- 通过从 stdin 读取来发布消息：

` echo {{message}} | kafkacat -P -t {{topic}} -b {{brokers}}`

- 通过读取文件发布消息：

`kafkacat -P -t {{topic}} -b {{brokers}} {{path/to/file}}`

- 列出所有主题和经纪的元数据：

`kafkacat -L -b {{brokers}}`

- 列出特定主题的元数据：

`kafkacat -L -t {{topic}} -b {{brokers}}`

- 获取特定时间点的主题/分区的偏移量：

`kafkacat -Q -t {{topic}:{{partition}}:{{unix_timestamp}} -b {{brokers}}`

[#]: contributors: ([潘潘]，[jim.大团结])