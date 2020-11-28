# pg_dump

> 导出 PostgreSQL 数据库，保存为脚本文件或其他归档文件

- 导出数据库存入指定 SQL-script 文件：

`pg_dump {{db_name}} > {{output_file.sql}}`

- 同上操作，但使用指定用户名：

`pg_dump -U {{username}} {{db_name}} > {{output_file.sql}}`

- 同上操作，但使用指定主机和端口：

`pg_dump -h {{host}} -p {{port}} {{db_name}} > {{output_file.sql}}`

- 以自定义格式导出数据库到指定归档文件：

`pg_dump -Fc {{db_name}} > {{output_file.dump}}`

[#]: contributors: ([李峰])