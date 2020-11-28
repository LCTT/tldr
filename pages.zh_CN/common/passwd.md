# passwd

> 用户更改密码的工具


- 更改当前用户的密码：

`passwd {{new_password}}`

- 更改指定用户的密码：

`passwd {{username}} {{new_password}}`

- 获取当前用户的密码状态：

`passwd -S`

- 置空账户的密码（相当于设置该账号无密码）：

`passwd -d`

[#]: contributors: ([王兴宇]，[jim.大团结])