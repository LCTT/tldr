# phpstan

> 一个PHP静态分析工具，用于发现代码中的错误

- 显示可用的分析选项：

`phpstan analyse --help`

- 分析指定的空间分隔目录：

`phpstan analyse {{path/to/directory}}`

- 使用配置文件分析目录：

`phpstan analyse {{path/to/directory}} --configuration {{path/to/config}}`

- 使用特定的规则级别进行分析（0-7，越高越严格）：

`phpstan analyse {{path/to/directory}} --level {{level}}`

- 在分析之前指定要加载的自动加载文件：

`phpstan analyse {{path/to/directory}} --autoload-file {{path/to/autoload_file}}`

- 在分析期间指定内存限制：

`phpstan analyse {{path/to/directory}} --memory-limit {{memory_limit}}`

[#]: contributors: ([　])