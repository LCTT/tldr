# msmtp

> SMTP 客户端
> 它从标准输入读取文本并发送至 SMTP 服务

- 用配置在`~/.msmtprc`的默认账户发送邮件：

`echo {{"Hello world"}} | msmtp {{to@example.org}}`

- 用配置在 `~/.msmtprc`的指定账户发送邮件：

`echo {{"Hello world"}} | msmtp --account={{account_name}} {{to@example.org}}`

- 发送没有配置账户的邮件密码应在`~/.msmtprc` 中指定：

`echo {{"Hello world"}} | msmtp --host={{localhost}} --port={{999}} --from={{from@example.org}} {{to@example.org}}`

[#]: contributors: ([琳小梁]，[青榉]，[jim.大团结])