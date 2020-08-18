# gunicorn

> 一种 python 网站服务器支持 wsgi 和 http 协议

- 启动一个 python 网站应用例如flask：

`gunicorn {{import.path:app_object}}`

- 指定监听本机的8080端口：

`gunicorn --bind {{localhost}}:{{8080}} {{import.path:app_object}}`

- 开启在线重载使用此参数后，项目文件有更改， gunicorn 会自动重载而不需重启：

`gunicorn --reload {{import.path:app_object}}`

- 开启4进程，用于响应请求：

`gunicorn --workers {{4}} {{import.path:app_object}}`

- 开启4线程，用于响应请求：

`gunicorn --threads {{4}} {{import.path:app_object}}`

- 以 HTTPS 协议运行应用：

`gunicorn --certfile {{cert.pem}} --keyfile {{key.pem}} {{import.path:app_object}}`

[#]: contributors: ([卜楞儿])