# mongorestore

> 从二进制文件导入数据集或数据库到 MongoDB 实例的工具

- 将指定文件夹中的 bson 数据文件导入至 MongoDB 数据库：

`mongorestore --db {{database_name}} {{path/to/folder}}`

- 将文件夹中的 bson 数据转储导入 MongoDB 服务器主机中的给定数据库，该主机在给定端口运行，并使用用户身份验证（将提示用户输入密码）：

`mongorestore --host {{database_host:port}} --db {{database_name}} --username {{username}} {{path/to/folder}} --password`

- 将指定 bson 文件中的一个数据集导入 MongoDB 数据库：

`mongorestore --db {{database_name}} {{path/to/file}}`

- 将一个集合从 bson 文件导入 MongoDB 服务器主机中的给定数据库，该主机在给定端口运行，并使用用户身份验证（将提示用户输入密码）：

`mongorestore --host {{database_host:port}} --db {{database_name}} --username {{username}} {{path/to/file}} --password`

[#]: contributors: ([潘潘]，[东先生])