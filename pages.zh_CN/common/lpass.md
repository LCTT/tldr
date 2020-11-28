# lpass

> LastPass 密码管理工具的命令行界面

- 通过在提示时输入主密码登录你的 LastPass 帐户：

`lpass login {{username}}`

- 显示登录状态：

`lpass status`

- 列出按类别分组的所有站点：

`lpass ls`

- 为标识符为 myinbox 的 gmail.com 生成新密码并添加到 LastPass ：

`lpass generate --username {{username}} --url {{gmail.com}} {{myinbox}} {{password_length}}`

- 显示某项的密码：

`lpass show {{myinbox}} --password`

[#]: contributors: ([潘潘]，[蔚然])