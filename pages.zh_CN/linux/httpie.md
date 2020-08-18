# httpie

> 一个用户友好的命令行HTTP工具

- 发送GET请求（没有请求数据的默认方法）：

`http {{https://example.com}}`

- 发送 POST 请求（带请求数据的默认方法）：

`http {{https://example.com}} {{hello=World}}`

- 发送带有重定向输入的 POST 请求：

`http {{https://example.com}} < {{file.json}}`

- 使用给定的 json 正文发送 PUT 请求：

`http PUT {{https://example.com/todos/7}} {{hello=world}}`

- 使用给定的请求头发送删除请求：

`http DELETE {{https://example.com/todos/7}} {{API-Key:foo}}`

- 显示整个 HTTP 交换（请求和响应）：

`http -v {{https://example.com}}`

- 下载文件：

`http --download {{https://example.com}}`

[#]: contributors: ([潘潘]，[Judie])