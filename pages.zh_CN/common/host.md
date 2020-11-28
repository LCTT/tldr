# host

> 查询 DNS 服务器

- 查询某个域名的 A 记录，AAAA 记录，MX 记录：

`host {{domain}}`

- 查询某个域名的 field (CNAME 记录、TXT 记录等)：

`host -t {{field}} {{domain}}`

- 查询 IP 地址对应的域名服务器：

`host {{ip_address}}`

- 在指定 DNS 服务器上查询：

`host {{domain}} {{8.8.8.8}}`

[#]: contributors: ([jrg])