# jhat

> Java 堆分析工具

- 分析堆转储（来自 jmap ），通过端口 7000 上的 http 进行查看：

`jhat {{dump_file.bin}}`

- 分析堆转储，指定 http 服务器的备用端口：

`jhat -p {{port}} {{dump_file.bin}}`

- 分析一个转储，让 jhat 使用高达 8GB 的 RAM（建议使用 2-4x 转储大小）：

`jhat -J-mx8G {{dump_file.bin}}`

[#]: contributors: ([潘潘])