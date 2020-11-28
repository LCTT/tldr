# locust

> 负载测试工具，用于确定系统可以处理的并发用户数

- 使用 locustfile.py 对 Web 界面进行负载测试 example.com ：

`locust --host={{http://example.com}}`

- 使用其他测试文件：

`locust --locustfile={{test_file.py}} --host={{http://example.com}}`

- 在没有 Web 界面的情况下运行测试，每秒产生 1 个用户，直到有 100 个用户：

`locust --no-web --clients={{100}} --hatch-rate={{1}} --host={{http://example.com}}`

- 以主模式启动 locust ：

`locust --master --host={{http://example.com}}`

- 将 locust slave 连接到 master ：

`locust --slave --host={{http://example.com}}`

- 在不同的机器上将 locust slave 连接到 master ：

`locust --slave --master-host={{master_hostname}} --host={{http://example.com}}`

[#]: contributors: ([潘潘])