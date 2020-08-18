# git config

> 管理 git 仓库配置项
> 可以是本地配置项（作用于当前代码库）或全局配置项（作用于当前用户）
> 主页地址: <https://git-scmcom/docs/git-config>

- 仅列出本地配置项（存储在当前代码库的 `.git/config`  文件里）：

`git config --list --local`

- 仅列出全局配置项（存储在 `~/.gitconfig` 文件里）：

`git config --list --global`

- 列出所有已定义的本地或全局配置项：

`git config --list`

- 获取一条配置项的值：

`git config alias.unstage`

- 设置一条全局配置项的值：

`git config --global alias.unstage "reset HEAD --"`

- 将一条全局配置项回复为默认值：

`git config --global --unset alias.unstage`

[#]: contributors: ([李峰])