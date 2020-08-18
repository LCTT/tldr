# ioping

> 实时监控 I/O 延迟

- 在当前目录下使用默认值显示磁盘 I/O 延迟：

`ioping .`

- 使用 10 次请求，每次 1MB 数据来测量 /tmp 的延迟：

`ioping -c 10 -s 1M /tmp`

- 测量 /dev/sda 的寻道速率：

`ioping -R /dev/sda`

- 测量 /dev/sda 的磁盘串行速度：

`ioping -RL /dev/sda`

[#]: contributors: ([王兴宇，Linux & BC]，[luog])