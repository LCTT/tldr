# test

> 条件判断
> 如果条件为真，返回值为0，否则返回值为1

- 判断指定的变量是否等于字符串：

`test $MY_VAR == '/bin/zsh'`

- 当指定的变量为空时返回真：

`test -z $GIT_BRANCH`

- 当指定的文件存在时返回真：

`test -e {{filename}}`

- 判断指定的目录，如果不存在，为真，否则为假：

`test ! -d {{path/to/directory}}`

- 如果条件为真则输出true，否则输出false：

`test {{condition}} && echo "true" || echo "false"`

[#]: contributors: ([雨天]，[CL]，[Mary Tim])