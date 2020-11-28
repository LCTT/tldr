# pathchk

> 检查一个或多个路径名称的合法性和可移植性

- 对路径名在当前系统中的合法性进行检查：

`pathchk {{path1 path2 …}}`

- 在一个宽泛的 POSIX 兼容系统上检查路径名的合法性：

`pathchk -p {{path1 path2 …}}`

- 检查路径名在所有的 POSIX 兼容系统上的合法性：

`pathchk --portability {{path1 path2 …}}`

- 仅检查空的或以连接线（`-`）开头的路径名：

`pathchk -P {{path1 path2 …}}`

[#]: contributors: ([王興與]，[杨旭东])