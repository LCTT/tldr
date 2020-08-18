# chage

> 更改用户帐户和密码的有效期限

- 列出用户的密码信息：

`chage -l {{user_name}}`

- 使密码在 10 天后过期：

`sudo chage -M {{10}} {{user_name}}`

- 禁止该密码过期：

`sudo chage -M -1 {{user_name}}`

- 设置帐户到期日期
（译者注：过了这天，此帐号将不可用）：

`sudo chage -E {{YYYY-MM-DD}}`

- 强制用户在下次登录时更改密码：

`sudo chage -d 0`

[#]: contributors: ([玉叶]，[王兴宇，Linux 中國]，[Datura stramonium L.])