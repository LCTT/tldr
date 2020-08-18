# julia

> 用于科学计算的高级、高性能动态编程语言

- 启动 Julia 交互式会话：

`julia`

- 执行 Julia 程序，然后退出：

`julia {{program.jl}}`

- 执行带有参数的 Julia 程序：

`julia {{program.jl}} {{arguments}}`

- 执行包含 Julia 代码的字符串：

`julia -e '{{julia_code}}'`

- 执行 Julia 代码的字符串，并给它传递参数：

`julia -e '{{for x in ARGS; println(x); end}}' {{arguments}}`

- 以并行模式启动 Julia，使用 N 个工作进程：

`julia -p {{N}}`

[#]: contributors: ([CNife])