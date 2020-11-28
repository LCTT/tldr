# sendmail

> 用命令行发送邮件

- 将文本文件 message.txt 中的内容发送给本地用户 user_name 的邮件目录中：

`sendmail {{user_name}} < {{message.txt}}`

- 将文本文件 message.txt 中的内容发送给邮件地址为 test@gmail.com 的收件人，并以 you@yourdomain.com 作为发件人的地址（假设此地址在邮件服务器中已设置）：

`sendmail -f {{you@yourdomain.com}} {{test@gmail.com}} < {{message.txt}}`

- 跟上一条命令完全相同，所不同的是以文件 file.zip 作为附件：

`sendmail -f {{you@yourdomain.com}} {{test@gmail.com}} < {{file.zip}}`

[#]: contributors: ([潘潘])