# dig

> DNS 查询套件

- 查找与域名相关联的 IP（A 记录）：

`dig +short {{hostname.com}}`

- 查找与指定域名相关连的邮件服务器（MX 记录）：

`dig +short {{hostname.com}} MX`

- 列出所有与指定域名相关连的所有记录：

`dig {{hostname.com}} ANY`

- 指定备用 DNS 服务器进行查询：

`dig @{{8.8.8.8}} {{hostname.com}}`

- 根据给定 IP 反向查询 DNS 记录 （PTR 记录）：

`dig -x {{8.8.8.8}}`

- 查找一个域的授权 DNS 服务器并显示 SOA 记录：

`dig +nssearch {{hostname.com}}`

- 进行迭代查询并显示解析域名的整个跟踪路径：

`dig +trace {{hostname.com}}`

[#]: contributors: ([琳小梁]，[盛曦 姜]，[∠( ᐛ 」∠)＿])