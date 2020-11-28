# lz4

> 压缩或者解压 lz4 文件

- 压缩一个文件：

`lz4 {{file}}`

- 解压一个文件：

`lz4 -d {{file.lz4}}`

- 解压缩文件并写入 stdout ：

`lz4 -dc {{file.lz4}}`

- 打包并压缩目录及其内容：

`tar cvf - {{path/to/dir}} | lz4 - {{dir.tar.lz4}}`

- 解压缩并解压缩目录及其内容：

`lz4 -d {{dir.tar.lz4}} | tar -xv`

- 使用最优压缩生成压缩文件：

`lz4 -9 {{file}}`

[#]: contributors: ([潘潘]，[6 °分离]，[Mr. Ren])