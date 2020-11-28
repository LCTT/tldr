# lsb_release

> 提供某些 LSB（Linux标准库）和特定于分发的信息

- 打印所有可以显示的信息：

`lsb_release -a`

- 打印当前操作系统的描述信息（通常是全名）：

`lsb_release -d`

- 仅打印操作系统名称（ID），禁止字段名称：

`lsb_release -i -s`

- 打印分发的版本号和代号，禁止字段名称：

`lsb_release -rcs`

[#]: contributors: ([潘潘]，[良†])