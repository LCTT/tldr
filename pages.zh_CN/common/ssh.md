# ssh

> Secure Shell 是一种用于安全登录远程系统的协议
> 它可以用于登录或执行远程服务器上的命令

- 连接到远程服务器：

`ssh {{username}}@{{remote_host}}`

- 用一个用户标识（私钥）连接到一个远程服务器：

`ssh -i {{path/to/key_file}} {{username}}@{{remote_host}}`

- 连接到远程服务器的指定端口：

`ssh {{username}}@{{remote_host}} -p {{2222}}`

- 在一个远程服务器上运行一条命令：

`ssh {{remote_host}} {{command -with -flags}}`

- SSH 隧道：动态端口转发 (SOCKS 代理地址为 localhost:9999)：

`ssh -D {{9999}} -C {{username}}@{{remote_host}}`

- SSH 隧道：转发特定端口（localhost:9999 映射到 slashdot.org:80），并且禁止伪终端（`-T`）分发和执行（`-N`）远程命令：

`ssh -L {{9999}}:{{slashdot.org}}:{{80}} -N -T {{username}}@{{remote_host}}`

- SSH 中转：通过一个中转主机连接到远程服务器（如果有多个中转主机，可用逗号分隔）：

`ssh -J {{username}}@{{jump_host}} {{username}}@{{remote_host}}`

- 认证转发：将认证信息转发到远程服务器上（更多选项参考 `man ssh_config`）：

`ssh -A {{username}}@{{remote_host}}`

[#]: contributors: ([秦时明月]，[王兴宇，Linux & BC]，[思柔小仙女]，[DD]，[Datura stramonium L.])