# electrum

> 符合人体工程学的比特币钱包和私钥管理

- 创建一个新钱包：

`electrum -w {{new_wallet.dat}} create`

- 从种子脱机还原现有钱包：

`electrum -w {{recovery_wallet.dat}} restore -o`

- 脱机创建签名的事务：

`electrum mktx {{recipient}} {{amount}} -f 0.0000001 -F {{from}} -o`

- 显示所有钱包接收地址：

`electrum listaddresses -a`

- 签署一条消息：

`electrum signmessage {{address}} {{message}}`

- 验证一条消息：

`electrum verifymessage {{address}} {{signature}} {{message}}`

- 仅连接到特定的电子服务器实例：

`electrum -p socks5:{{127.0.0.1}}:9050 -s {{56ckl5obj37gypcu.onion}}:50001:t -1`

[#]: contributors: ([潘潘]，[王兴宇，Linux & BC])