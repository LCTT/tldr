# mongo

> MongoDB 交互式命令行客户端

- 连接到一个数据库：

`mongo {{database}}`

- 连接到运行在给定主机和端口的数据库：

`mongo --host {{host}} --port {{port}} {{database}}`

- 使用给定的用户名连接数据库；并在提示符后输入用户密码：

`mongo --username {{username}} {{database}} --password`

- 在数据库求一个 javascript 表达式的值：

`mongo --eval '{{JSON.stringify(db.foo.findOne())}}' {{database}}`

[#]: contributors: ([jim.大团结])