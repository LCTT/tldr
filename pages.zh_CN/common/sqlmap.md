# sqlmap

> 检测并发现SQL注入点

- 对单个目标地址运行sqlmap：

`python sqlmap.py -u {{"http://www.target.com/vuln.php?id=1"}}`

- 在POST请求里发送数据（data字段代表POST请求）：

`python sqlmap.py -u {{"http://www.target.com/vuln.php" --data={{"id=1"}}`

- 更改参数分隔符（默认为&）：

`python sqlmap.py -u {{"http://www.target.com/vuln.php"}} --data={{"query=foobar;id=1"}} --param-del={{";"}}`

- 从./txt/user-agents.txt文件里选取并使用一个随机的User-Agent：

`python sqlmap.py -u {{"http://www.target.com/vuln.php"}} --random-agent`

- 提供HTTP协议的用户凭证：

`python sqlmap.py -u {{"http://www.target.com/vuln.php"}} --auth-type {{Basic}} --auth-cred {{"testuser:testpass"}}`

[#]: contributors: ([盛曦 姜])