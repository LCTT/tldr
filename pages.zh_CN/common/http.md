# http

>  HTTPie：HTTP 客户端，一个用户友好的 cURL 替代品

- 从URL上下载一个文件（网页）到本地：

`http -d {{example.org}}`

- 发送编码的表单数据：

`http -f {{example.org}} {{name='bob'}} {{profile_picture@'bob.png'}}`

- 发送 JSON 对象：

`http {{example.org}} {{name='bob'}}`

- 指定 HTTP 方法：

`http {{HEAD}} {{example.org}}`

- 包括一个额外的请求头：

`http {{example.org}} {{X-MyHeader:123}}`

- 传递用于服务器身份验证的用户名和密码：

`http -a {{username:password}} {{example.org}}`

- 通过标准输入指定原始请求体：

`cat {{data.txt}} | http PUT {{example.org}}`

[#]: contributors: ([　]，[陶瑞]，[王兴宇]，[懒汉晨成])