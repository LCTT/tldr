# kube-fzf

> 用于命令行模糊搜索kubernetes pods的shell命令
> 有关相关命令，请参见“kubectl”

- 获取 pod 详细信息（从当前命名空间）：

`findpod`

- 获取 pod 详细信息（从所有命名空间）：

`findpod -a`

- 描述一个 pod ：

`describepod`

- 追尾 pod 日志：

`tailpod`

- 执行进入 pod 的容器：

`execpod {{shell_command}}`

- 端口转发一个 pod ：

`pfpod {{port_number}}`

[#]: contributors: ([潘潘]，[Judie])