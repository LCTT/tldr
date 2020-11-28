# valgrind

> 封装了一系列用于剖析、优化和调试程序的专业工具
> 常用工具包括 `memcheck`、 `cachegrind`、 `callgrind`、 `massif`、 `helgrind` 和 `drd`

- 使用（默认的）`memcheck` 工具来展示对
{{program}} 内存使用情况的诊断：

`valgrind {{program}}`

- 使用 Memcheck 来报告 `program` 中所有可能的内存泄露的全部细节：

`valgrind --leak-check=full --show-leak-kinds=all {{program}}`

- 使用 Cachegrind 工具剖析和记录 `program` 的 CPU 缓存操作：

`valgrind --tool=cachegrind {{program}}`

- 使用 Massif 工具来剖析和记录 `program` 的堆内存和堆栈的使用情况：

`valgrind --tool=massif --stacks=yes {{program}}`

[#]: contributors: ([王興與·區塊鏈·Linux中國]，[王兴宇，Linux & BC]，[庄秋彬])