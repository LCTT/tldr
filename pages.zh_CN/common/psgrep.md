# psgrep

> 用 `grep` 搜索进程

- 查找包含特定字符串的进程：

`psgrep {{process_name}}`

- 查找包含特定字符串的进程，不包括列表标题：

`psgrep -n {{process_name}}`

- 使用简化格式（ PID、用户、命令）搜索：

`psgrep -s {{process_name}}`

[#]: contributors: ([玉叶]，[王兴宇，Linux 中國]，[Datura stramonium L.])