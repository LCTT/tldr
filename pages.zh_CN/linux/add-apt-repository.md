# add-apt-repository

> 管理 apt 仓库定义

- 添加一个新的 apt 仓库：

`add-apt-repository {{repository_spec}}`

- 移除一个 apt 仓库：

`add-apt-repository --remove {{repository_spec}}`

- 添加一个仓库后，更新包缓存：

`add-apt-repository --update {{repository_spec}}`

- 可更新源代码包：

`add-apt-repository --enable-source {{repository_spec}}`

[#]: contributors: ([东先生])