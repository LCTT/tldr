# apt-key

> 用于 Debian 和 Ubuntu 上 APT 包管理器的密钥管理程序

- 列出受信任的密钥：

`apt-key list`

- 添加密钥到受信任的密钥库：

`apt-key add {{public_key_file.asc}}`

- 从受信任的密钥库移除密钥：

`apt-key del {{key_id}}`

- 将远程密钥添加到受信任的密钥库：

`wget -qO - {{https://host.tld/filename.key}} | apt-key add -`

- 仅从具有密钥 ID 的密钥服务器添加密钥：

`apt-key adv --keyserver {{pgp.mit.edu}} --recv {{KEYID}}`

[#]: contributors: ([Datura stramonium L.])