# mongodump

> 用于导出 MongoDB 实例内容的实用程序

- 创建一个所有数据库的备份 (此操作会将备份文件存放在“dump”文件夹内)：

`mongodump`

- 指定转储的输出位置：

`mongodump --out {{path/to/folder}}`

- 创建给定数据库的转储：

`mongodump --db {{database_name}}`

- 在给定数据库中创建给定集合的转储：

`mongodump --collection {{collection_name}} --db {{database_name}}`

- 连接到在给定端口上运行的给定主机，并创建转储：

`mongodump --host {{host}} --port {{port}}`

- 使用给定的用户名创建给定数据库的转储，将提示用户输入密码：

`mongodump --username {{username}} {{database}} --password`

[#]: contributors: ([潘潘]，[Makise])