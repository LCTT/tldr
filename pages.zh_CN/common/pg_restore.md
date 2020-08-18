# pg_restore

> 使用 pg_dump 生成的归档文件来恢复 PostgreSQL 数据库

- 将存档恢复到指定数据库里：

`pg_restore -d {{db_name}} {{archive_file.dump}}`

- 同上操作，并指定用户名：

`pg_restore -U {{username}} -d {{db_name}} {{archive_file.dump}}`

- 同上操作，并指定主机和端口：

`pg_restore -h {{host}} -p {{port}} -d {{db_name}} {{archive_file.dump}}`

- 在重新创建数据库对象之前清除它们：

`pg_restore --clean -d {{db_name}} {{archive_file.dump}}`

- 采用多任务的方式来恢复：

`pg_restore -j {{2}} -d {{db_name}} {{archive_file.dump}}`

[#]: contributors: ([李峰])