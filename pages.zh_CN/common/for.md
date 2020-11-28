# for

> Shell 中参数间的循环

- 使用不同的参数来执行命令：

`for argument in 1 2 3; do {{command $argument}}; done`

- 在（给定的）每个目录中执行命令：

`for d in *; do (cd $d; {{command}}); done`

[#]: contributors: ([张益兴])