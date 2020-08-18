# ssh-keygen

> 生成ssh密钥，用于用户验证，免密登陆或其他验证等

- 交互式地生成密钥：

`ssh-keygen`

- 指定密钥生成的保存位置：

`ssh-keygen -f ~/.ssh/{{filename}}`

- -t 指定密钥类型 ed25519是一种密钥类型 -a 在为DH-GEX产生候选素数时的测试次数，此参数应结合-T参数默认是100次，通常不怎么用此参数：

`ssh-keygen -t ed25519 -a 100`

- 生成rsa类型的密钥，长度4096位，以邮件地址作注释：

`ssh-keygen -t rsa -b 4096 -C "{{email}}"`

- 从主机检索密钥指纹（用于在首次通过 SSH 连接主机时确认主机的真实性）：

`ssh-keygen -l -F {{remote_host}}`

- 在 MD5 Hex 中检索密钥的指纹：

`ssh-keygen -l -E md5 -f ~/.ssh/{{filename}}`

- 更改密钥的密码可不设置密码：

`ssh-keygen -p -f ~/.ssh/{{filename}}`

[#]: contributors: ([潘潘]，[卜楞儿])