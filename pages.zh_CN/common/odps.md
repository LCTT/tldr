# odps

> 阿里云 ODPS (Open Data Processing Service，公开数据处理服务) 命令行工具

- 使用一个自定义的配置文件来启动命令行工具：

`odpscmd --config={{odps_config.ini}}`

- 切换当前的项目：

`use {{project_name}};`

- 在当前项目中显示表格：

`show tables;`

- 描述一个表格：

`desc {{table_name}};`

- 显示表格划分情况：

`show partitions {{table_name}};`

- 描述一个划分：

`desc {{table_name}} partition ({{partition_spec}});`

[#]: contributors: ([lc])