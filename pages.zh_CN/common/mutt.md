# mutt

> 电子邮件命令行客户端

- 打开指定邮箱：

`mutt -f {{mailbox}}`

- 发送电子邮件，指定主题和抄送收件人：

`mutt -s {{subject}} -c {{cc@example.com}} {{recipient@example.com}}`

- 发送带有附件的电子邮件：

`mutt -a {{file1}} {{file2}} -- {{recipient@example.com}}`

- 指定要作为消息正文包含的文件：

`mutt -i {{file}} {{recipient@example.com}}`

- 指定一个包含消息头与消息体，格式为RFC 5322的草稿文件：

`mutt -H {{file}} {{recipient@example.com}}`

[#]: contributors: ([阿涛]，[Datura stramonium L.])