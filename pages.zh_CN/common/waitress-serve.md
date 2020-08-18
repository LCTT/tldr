# waitress-serve

> 纯 Python WSGI HTTP 服务器

- 运行一个 Python web 应用：

`waitress-serve {{import.path:wsgi_func}}`

- 监听本地 8080 端口：

`waitress-serve --listen={{localhost}}:{{8080}} {{import.path:wsgi_func}}`

- 在一个Unix socket上启动服务：

`waitress-serve --unix-socket={{path/to/socket}} {{import.path:wsgi_func}}`

- 使用4个线程处理请求：

`waitress-serve --threads={{4}} {{import.path:wsgifunc}}`

- 调用一个返回 WSGI 对象的工厂方法：

`waitress-serve --call {{import.path.wsgi_factory}}`

- 将 URL 模式设为 https：

`waitress-serve --url-scheme={{https}} {{import.path:wsgi_func}}`

[#]: contributors: ([东先生])