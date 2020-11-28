# lxc

> 使用 lxd REST API 管理 Linux 容器
> 任何容器名称或模式都可以使用远程服务器的名称作为前缀

- 列出与字符串匹配的本地容器省略字符串以列出所有本地容器：

`lxc list {{match_string}}`

- 列出与字符串匹配的 images省略字符串以列出所有 images ：

`lxc image list [{{remote}}:]{{match_string}}`

- 从 image 创建一个新容器：

`lxc launch [{{remote}}:]{{image}} {{container}}`

- 启动一个容器：

`lxc start [{{remote}}:]{{container}}`

- 停止一个容器：

`lxc stop [{{remote}}:]{{container}}`

- 显示有关容器的详细信息：

`lxc info [{{remote}}:]{{container}}`

- 拍摄容器的快照：

`lxc snapshot [{{remote}}:]{{container}} {{snapshot}}`

[#]: contributors: ([潘潘])