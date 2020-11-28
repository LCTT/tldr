# ansible

> 通过 SSH 远程管理计算机群组
> 使用 /etc/ansible/hosts 这个文件添加新的计算机和分组
> 主页：<https://wwwansiblecom/>

- 列出属于某个分组的主机：

`ansible {{group}} --list-hosts`

- 调用 ping 模块对一组主机做 ping 测试：

`ansible {{group}} -m ping`

- 调用 setup 模块，显示一组主机的基本配置信息：

`ansible {{group}} -m setup`

- 通过调用命令模块传入参数，在一组主机上执行命令：

`ansible {{group}} -m command -a '{{my_command}}'`

- 用管理员权限执行一条命令：

`ansible {{group}} --become --ask-become-pass -m command -a '{{my_command}}'`

- 使用自定义的主机列表执行一条命令：

`ansible {{group}} -i {{inventory_file}} -m command -a '{{my_command}}'`

[#]: contributors: ([王兴宇，Linux & BC]，[良†])