# lwp-request

> 简单的命令行版 HTTP 客户端
> 以 libwww-perl 构建

- 发出一个简单的 GET 请求：

`lwp-request -m GET {{http://example.com/some/path}}`

- 以 POST 请求上传一个文件：

`cat {{/path/to/file}} | lwp-request -m POST {{http://example.com/some/path}}`

- 使用自定义用户代理发送请求：

`lwp-request -H 'User-Agent: {{user_agent}} -m {{METHOD}} {{http://example.com/some/path}}`

- 使用 HTTP 身份验证发出请求：

`lwp-request -C {{username}}:{{password}} -m {{METHOD}} {{http://example.com/some/path}}`

- 发出请求并打印请求头：

`lwp-request -U -m {{METHOD}} {{http://example.com/some/path}}`

- 生成请求并打印响应头和状态链：

`lwp-request -E -m {{METHOD}} {{http://example.com/some/path}}`

[#]: contributors: ([王兴宇，Linux & BC]，[Datura stramonium L.])