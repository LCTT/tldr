# env

> 显示当前环境或在修改后的环境中运行程序

- 显示环境：

`env`

- 运行一个程序常用在脚本#!之后，以查找程序路径：

`env {{program}}`

- 清除环境并运行程序：

`env -i {{program}}`

- 从环境中删除变量并运行程序：

`env -u {{variable}} {{program}}`

- 设置变量并运行程序：

`env {{variable}}={{value}} {{program}}`

[#]: contributors: ([东先生]，[Datura stramonium L.])