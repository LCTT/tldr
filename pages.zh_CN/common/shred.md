# shred

> 覆盖文件以安全删除数据

- 覆盖文件：

`shred {{file}}`

- 覆盖文件，留下零而不是随机数据：

`shred --zero {{file}}`

- 覆盖文件 25 次：

`shred -n25 {{file}}`

- 覆盖文件并将其删除：

`shred --remove {{file}}`

[#]: contributors: ([潘潘])