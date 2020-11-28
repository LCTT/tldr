# phing

> 一个基于 Apache Ant 的 PHP 构建工具

- 执行 "build.xml" 文件中的默认任务：

`phing`

- 初始化一个新的构建文件：

`phing -i {{path/to/build.xml}}`

- 执行一个指定的任务：

`phing {{task_name}}`

- 指定一个构建文件的路径：

`phing -f {{path/to/build.xml}} {{task_name}}`

- 指定输出的日志文件：

`phing -b {{path/to/log_file}} {{task_name}}`

- 指定用于该构建的定制属性：

`phing -D{{property}}={{value}} {{task_name}}`

- 指定一个定制的监听器类：

`phing -listener {{class_name}} {{task_name}}`

- 使用详细输出构建：

`phing -verbose {{task_name}}`

[#]: contributors: ([王興與]，[戚正阳]，[好名字可以让你的朋友更容易记住你]，[咪咪咪🍼])