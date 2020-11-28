# ionice

> 获取或设置程序I/O调度类和优先级
> 调度类：1（实时）、2（尽最大努力）、3（空闲）
> 优先级：0（最高）-7（最低）

- 设置正在运行的进程的 I / O 调度类：

`ionice -c {{scheduling_class}} -p {{pid}}`

- 使用自定义 I / O 调度类和优先级一般调遣运行命令：

`ionice -c {{scheduling_class}} -n {{priority}} {{command}}`

- 打印正在运行的进程的I/O调度类和优先级：

`ionice -p {{pid}}`

[#]: contributors: ([潘潘]，[artes]，[Judie])