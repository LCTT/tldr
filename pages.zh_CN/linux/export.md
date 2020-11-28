# export

> 命令将当前环境中的 shell 变量标记为要与任何新派生的子进程一起导出

- 设置新的环境变量：

`export {{VARIABLE}}={{value}}`

- 删除环境变量：

`export -n {{VARIABLE}}`

- 标记一个 shell 函数：

`export -f {{FUNCTION_NAME}}`

- 往 PATH 里添加路径：

`export PATH=$PATH:{{path/to/append}}`

[#]: contributors: ([jim.大团结]，[仁人]，[Datura stramonium L.])