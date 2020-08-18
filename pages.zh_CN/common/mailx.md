# mailx

> 发送、或是接收电子邮件

- 以主题 subject 给地址 to_addr 发送电子邮件
命令行键入后，必须打入邮件内容，以回车键分段，最后以 Ctrl+D 键结束结束后退出命令行，邮件随即发出：

`mailx -s "{{subject}}" {{to_addr}}`

- 跟第 1 条命令相同，只是内容不必在命令行键入后再以键盘输入，而是以 echo 中的 content 作为内容，以管道操作送入邮件命令行，键入命令行后，邮件随即发出：

`echo "{{content}}" | mailx -s "{{subject}}" {{to_addr}}`

- 跟第 1 条命令相同，只是内容不必在命令行键入后再以键盘输入，而是以定向操作将文本文件 content.txt 送入邮件命令行，键入命令行后，邮件随即发出：

`mailx -s "{{subject}}" {{to_addr}} < {{content.txt}}`

- 跟第 1 条命令相同，只是多加了一个抄送给 邮件地址为 cc_addr 一项：

`mailx -s "{{subject}}" -c {{cc_addr}} {{to_addr}}`

- 跟第 1 条命令相同，只是多加了一个邮件发出地址为 from_addr 一项注意：这个邮件发出地址，最好是合法的一个邮件地址，否则有可能被一些邮件服务器作为垃圾邮件处理、或是直接被退回：

`mailx -s "{{subject}}" -r {{from_addr}} {{to_addr}}`

- 跟第 1 条命令相同，只是多加了把文件 file 作为电子邮件的附件一项：

`mailx -a {{file}} -s "{{subject}}" {{to_addr}}`

[#]: contributors: ([潘潘])