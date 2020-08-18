# timeout

> 限定运行一个命令的时间

- 如果运行时间超过 3 秒，运行 `sleep 10` 并终止：

`timeout {{3s}} {{sleep 10}}`

- 指定在时间限制过期后发送到命令的信号（默认情况下，发送期限）：

`timeout --signal {{INT}} {{5s}} {{sleep 10}}`

[#]: contributors: ([东先生]，[󠀀]，[Datura stramonium L.])