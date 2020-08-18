# odps table

> 创建并修改 ODPS (开放数据处理服务)中的表

- 创建一个表，指定部分内容，以及生命周期：

`create table {{table_name}} ({{col}} {{type}}) partitioned by ({{col}} {{type}}) lifecycle {{days}};`

- 创建一个表，基于另外一个表的定义：

`create table {{table_name}} like {{another_table}};`

- 添加一部分到表中：

`alter table {{table_name}} add partition ({{partition_spec}});`

- 部分删除表：

`alter table {{table_name}} drop partition ({{partition_spec}});`

- 删除表：

`drop table {{table_name}};`

[#]: contributors: ([东先生])