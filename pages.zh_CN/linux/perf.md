# perf

> Linux 性能计数器测量框架

- 显示一个命令的基本性能计数器统计：

`perf stat {{gcc hello.c}}`

- 显示系统级实时性能计数剖析：

`sudo perf top`

- 运行一个命令并记录其性能剖析到 `perf.data`文件：

`sudo perf record {{command}}`

- 读取由 `perf record` 生成的 `perf.data`，并显示其剖析：

`sudo perf report`

[#]: contributors: ([王興與·區塊鏈·Linux中國]，[朝搴夕揽])