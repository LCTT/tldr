# beanstalkd

> 简单通用的工作队列服务器

- 启动 beanstalkd 进程，在端口 11300 侦听：

`beanstalkd`

- 启动 beanstalkd 进程，在指定的地址和端口侦听：

`beanstalkd -l {{ip_address}} -p {{port_number}}`

- 保存保留工作队列于磁盘：

`beanstalkd -b {{path/to/persistence_directory}}`

- 每 500 毫秒同步保存队列的目录：

`beanstalkd -b {{path/to/persistence_directory}} -f {{500}}`

[#]: contributors: ([琳小梁]，[潘潘]，[Judie])