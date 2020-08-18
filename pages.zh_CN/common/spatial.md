# spatial

> 一套管理和开发 SpatialOS 项目的命令

- 当你首先使用一个项目时请运行此命令：

`spatial worker build`

- 在 macOS 上做 Unity 本地开发时构建工作进程：

`spatial worker build --target=development --target=Osx`

- 在 Windows 上做 Unity 本地开发时构建工作进程：

`spatial worker build --target=local --target=Windows`

- 本地部署：

`spatial local launch {{launch_config}} --snapshot={{snapshot_file}}`

- 启动一个本地工作进程以连接到你的本地部署环境：

`spatial local worker launch {{worker_type}} {{launch_config}}`

- 将一个汇编程序部署到云端：

`spatial cloud upload {{assembly_name}}`

- 启动云端部署：

`spatial cloud launch {{assembly_name}} {{launch_config}} {{deployment_name}}`

- 清理工作程序目录：

`spatial worker clean`

[#]: contributors: ([王興與·區塊鏈·Linux中國])