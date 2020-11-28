# jstack

> Java 堆栈跟踪工具

- 为 Java 进程中的所有线程打印 Java 堆栈跟踪：

`jstack {{java_pid}}`

- 为 Java 进程中的所有线程打印混合代码的（Java/C++）堆栈跟踪：

`jstack -m {{java_pid}}`

- 从 Java 核心转储打印堆栈跟踪：

`jstack {{/usr/bin/java}} {{file.core}}`

[#]: contributors: ([Datura stramonium L.])