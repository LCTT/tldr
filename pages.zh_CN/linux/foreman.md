# foreman

> 管理 Procfile-based 应用

- 使用当前目录中的 Procfile 启动应用程序：

`foreman start`

- 使用指定的 Procfile 启动应用程序：

`foreman start -f {{Procfile}}`

- 开始指定应用：

`foreman start {{process}}`

- 验证 Procfile 格式：

`foreman check`

- 使用进程的环境运行一次性命令：

`foreman run {{command}}`

- 启动除名为 worker 之外的所有进程：

`foreman start -m all=1,{{worker}}=0`

[#]: contributors: ([潘潘]，[jim.大团结])