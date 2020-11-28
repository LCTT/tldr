# curl

> 上传数据至服务器，或从服务器下载数据
> 支持常见的协议，包括 HTTP、FTP 和 POP3 等

- 下载 URL 的内容至文件：

`curl {{http://example.com}} -o {{filename}}`

- 下载文件，以 URL 中给出的文件名保存文件：

`curl -O {{http://example.com/filename}}`

- 下载文件，并跟随 URL [L] 重定向，并自动继续 [C]（恢复）以前的文件传输：

`curl -O -L -C - {{http://example.com/filename}}`

- 仅显示文档信息（头部）：

`curl -I`

- 发送表单编码的数据（POST 请求类型为 `application/x-www-form-urlencoded`）：

`curl -d {{'name=bob'}} {{http://example.com/form}}`

- 使用自定义的 HTTP 请求方式，发送包含额外请求头的 HTTP 请求：

`curl -H {{'X-My-Header: 123'}} -X {{PUT}} {{http://example.com}}`

- 发送 JSON 格式的数据，指定合适的内容类型头：

`curl -d {{'{"name":"bob"}'}} -H {{'Content-Type: application/json'}} {{http://example.com/users/1234}}`

- 指定用户名和密码访问服务：

`curl -u myusername:mypassword {{http://example.com}}`

- 将客户端证书和密钥传递给一个资源，并跳过证书验证：

`curl --cert {{client.pem}} --key {{key.pem}} --insecure {{https://example.com}}`

[#]: contributors: ([Femtoyue]，[琳小梁]，[王兴宇，Linux & BC]，[Sellente_Wang]，[Essen]，[盛曦 姜]，[Judie]，[公孙林]，[丫仔]，[王兴宇，Linux 中國]，[漠问纷飞]，[Justice])