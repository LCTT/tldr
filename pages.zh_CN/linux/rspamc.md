# rspamc

> rspamd 服务器的命令行客户端

- 将一封电子邮件作为垃圾邮件来训练贝叶斯过滤器：

`rspamc learn_spam {{path/to/email_file}}`

- 将一封电子邮件作为非垃圾邮件来训练贝叶斯过滤器：

`rspamc learn_ham {{path/to/email_file}}`

- 手动生成一份电子邮件的报告：

`rspamc symbols {{path/to/email_file}}`

- 展示服务器统计数据：

`rspamc stat`

[#]: contributors: ([王興與·璃霓思硬核]，[王兴宇，Linux & BC]，[玉叶])