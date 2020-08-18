# odps tunnel

> 在开放数据处理服务 ODPS 中的数据隧道

- 下载表到本地：

`tunnel download {{table_name}} {{file}};`

- 将本地文件上传到表分区：

`tunnel upload {{file}} {{table_name}}/{{partition_spec}};`

- 上传表指定字段和记录分隔符：

`tunnel upload {{file}} {{table_name}} -fd {{field_delim}} -rd {{record_delim}};`

- 多线程上传表：

`tunnel upload {{file}} {{table_name}} -threads {{num}};`

[#]: contributors: ([潘潘]，[Eski])