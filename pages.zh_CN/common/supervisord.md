# supervisord

> Supervisor 是一个在类Unix系统上用来管理某些进程的基于客户端/服务端模式的系统
> Supervisord 是 supervisor 的服务端；我们主要通过一个配置文件来管理它

- 根据一个指定的配置文件来启动 supervisord：

`supervisord -c {{path/to/file}}`

- 在前台运行 supervisord：

`supervisord -n`

[#]: contributors: ([_xyc])