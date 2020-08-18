# odps resource

> 管理 ODPS (开放数据处理服务)中的数据源

- 显示当前项目中的数据源：

`list resources;`

- 添加文件源：

`add file {{file_name}} as {{alias}};`

- 添加文档源：

`add archive {{archive.tar.gz}} as {{alias}};`

- 添加 .jar 源：

`add jar {{package.jar}};`

- 添加 .py 源：

`add py {{script.py}};`

- 删除源：

`drop resource {{resource_name}};`

[#]: contributors: ([东先生])