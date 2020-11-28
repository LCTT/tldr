# shc

> 通用的 shell 脚本编译器

- 编译一个 shell 脚本：

`shc -f {{script}}`

- 编译 shell 脚本并指定输出的二进制文件：

`shc -f {{script}} -o {{binary}}`

- 编译 shell 脚本并为生成的可执行文件设置到期日期：

`shc -f {{script}} -e {{dd/mm/yyyy}}`

- 编译 shell 脚本并设置在到期时显示的消息：

`shc -f {{script}} -e {{dd/mm/yyyy}} -m {{"Please contact your provider"}}`

[#]: contributors: ([王兴宇，Linux & BC]，[󠀀])