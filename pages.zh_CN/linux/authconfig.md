# authconfig

> 命令行界面，用于配置系统身份认证资源

- 显示当前配置（预演）：

`authconfig --test`

- 配置服务器使用不同的口令算法：

`authconfig --update --passalgo={{algorithm}}`

- 使用 LDAP 身份验证：

`authconfig --update --enableldapauth`

- 终止 LDAP 身份验证：

`authconfig --update --disableldapauth`

- 使用网络信息服务（NIS）：

`authconfig --update --enablenis`

- 使用 KRB5：

`authconfig --update --enablekrb5`

- 使用 Winbind （AD）身份验证：

`authconfig --update --enablewinbindauth`

- 使用本地身份验证：

`authconfig --update --enablelocauthorize`

[#]: contributors: ([潘潘]，[rabbittony刘晓东-工作时间失联])