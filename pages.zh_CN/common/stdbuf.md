# stdbuf

> 运行一个命令，修改其标准流的缓存操作

- 改变标准输入缓存的大小为 512 KiB：

`stderr --input={{512K}} {{command}}`

- 改变标准缓存区为线式缓存：

`stdbuf --output={{L}} {{command}}`

- 改变标准错误缓存为不缓存：

`stdbuf --error={{0}} {{command}}`

[#]: contributors: ([王興與·區塊鏈·Linux中國])