# make

> 用于执行Makefile中所描述目标的任务
> 主要用于控制从源代码编译可执行文件

- 调用Makefile中指定的第一个目标(通常命名为“all”)：

`make`

- 调用特定的目标：

`make {{target}}`

- 调用一个特定的目标，一次并行执行n个作业，（n为运行的任务数量，不设置参数为尽可能同时多运行任务，该参数通常设置为cpu核心数的二倍）：

`make -j{{n}} {{target}}`

- 使用特定的Makefile：

`make --file {{file}}`

- 从另一个目录执行make：

`make --directory {{directory}}`

- 强制制作一个目标，即使源文件没有改变：

`make --always-make {{target}}`

[#]: contributors: ([仁人])