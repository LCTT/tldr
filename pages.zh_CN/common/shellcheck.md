# shellcheck

> shell 脚本静态分析工具
> 主页：<https://wwwshellchecknet/>

- 检查 shell 脚本：

`shellcheck {{file.sh}}`

- 重写脚本的 shebang （#位于第一行开头，并且是#!（称为Shebang））：

`shellcheck --shell {{sh|bash|ksh}} {{file.sh}}`

- 忽略某些错误：

`shellcheck --exclude {{SC1009}} {{file.sh}}`

- 忽略多个错误：

`shellcheck --exclude {{SC1009,SC1073}} {{file.sh}}`

[#]: contributors: ([Datura stramonium L.])