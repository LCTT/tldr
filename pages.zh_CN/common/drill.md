# drill

> 执行各种 DNS 查询

- 查找与主机名（A 记录）关联的 IP：

`drill {{hostname.com}}`

- 查找与给定域名（ MX 记录）关联的邮件服务器：

`drill mx {{hostname.com}}`

- 获取给定域名的所有类型的记录：

`drill any {{hostname.com}}`

- 指定要查询的备用 DNS 服务器：

`drill {{hostname.com}} @{{8.8.8.8}}`

- 对 IP 地址（PRT 记录）执行反向 DNS 查找：

`drill -x {{8.8.8.8}}`

- 从根服务器到域名执行 DNSSEC 跟踪：

`drill -TD {{hostname.com}}`

- 显示域名的 DNSKEY 记录：

`drill -s dnskey {{hostname.com}}`

[#]: contributors: ([琳小梁]，[Datura stramonium L.])