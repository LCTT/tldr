# odps inst

> 管理 ODPS（开放数据处理服务）中的实例

- 显示当前用户创建的实例：

`show instances;`

- 描述实例的详细信息：

`desc instance {{instance_id}};`

- 检查实例的状态：

`status {{instance_id}};`

- 等待实例终止，打印日志和进度信息，直到那时为止：

`wait {{instance_id}};`

- 杀死一个实例：

`kill {{instance_id}};`

[#]: contributors: ([潘潘])