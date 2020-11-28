# jmap

> Java 内存映射工具

- 打印 java 进程的共享对象映射（像 pmap 这样的输出）：

`jmap {{java_pid}}`

- 输出堆的概要信息：

`jmap -heap {{filename.jar}} {{java_pid}}`

- 按类型输出堆使用的柱状图：

`jmap -histo {{java_pid}}`

- 将堆的内容转储到二进制文件中以便使用 jhat 进行分析：

`jmap -dump:format=b,file={{filename}} {{java_pid}}`

[#]: contributors: ([潘潘]，[6 °分离]，[刚刚])