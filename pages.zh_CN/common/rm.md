# rm

> 删除文件或目录

- 删除任意位置的文件：

`rm {{path/to/file}} {{path/to/another/file}}`

- 递归删除一个目录以及它下面的所有子目录：

`rm -r {{path/to/directory}}`

- 强制删除目录，不提示确认或显示错误消息
：

`rm -rf {{path/to/directory}}`

- 删除前逐一询问确认：

`rm -i {{file(s)}}`

- 用冗长模式删除文件，每删除一个文件打印一条信息：

`rm -v {{path/to/directory/*}}`

[#]: contributors: ([Hello World]，[rm -rf]，[发条夏]，[深水海豚]，[CPY]，[ukyozhou]，[寒梦遥]，[斯文与众]，[黄伟明])