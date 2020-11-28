# nikto

> Web服务器扫描程序，对多个项目的Web服务器执行综合测试

- 对目标主机执行基本的 Nikto 扫描：

`perl nikto.pl -h {{192.168.0.1}}`

- 对指定端口号进行基本扫描：

`perl nikto.pl -h {{192.168.0.1}} -p {{443}}`

- 用完整的 URL 语法扫描端口和协议：

`perl nikto.pl -h {{https://192.168.0.1:443/}}`

- 在同一扫描任务中扫描多个端口：

`perl nikto.pl -h {{192.168.0.1}} -p {{80,88,443}}`

- 将插件和数据库更新到最新：

`perl nikto.pl -update`

[#]: contributors: ([Datura stramonium L.])