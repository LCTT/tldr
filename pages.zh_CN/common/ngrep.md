# ngrep

> 使用正则表达式过滤网络流量数据包

- 捕获所有接口的通信：

`ngrep -d any`

- 捕获特定接口的通信：

`ngrep -d {{eth0}}`

- 捕获 eth0 的端口22的通信：

`ngrep -d {{eth0}} port {{22}}`

- 捕获来自或到主机的通信：

`ngrep host {{www.example.com}}`

- 过滤接口 eth0 的关键词 'User-Agent:'：

`ngrep -d {{eth0}} '{{User-Agent:}}'`

[#]: contributors: ([jim.大团结])