# sqsc

> AWS Simple Queue Service 命令行客户端

- 列出所有队列：

`sqsc lq {{queue_prefix}}`

- 列出队列中的所有消息：

`sqsc ls {{queue_name}}`

- 从一个队列复制所有消息到另外一个队列：

`sqsc cp {{source_queue}} {{destination_queue}}`

- 从一个队列移动所有消息到另外一个队列：

`sqsc mv {{source_queue}} {{destination_queue}}`

- 描述一个队列：

`sqsc describe {{queue_name}}`

- 以 SQL 语法查询一个队列：

`sqsc query "SELECT body FROM {{queue_name}} WHERE body LIKE '%user%'"`

- 拉取一个队列的所有消息到你当前工作目录的一个本地 sqlite 数据库：

`sqsc pull {{queue_name}}`

[#]: contributors: ([王興與·區塊鏈·Linux中國])