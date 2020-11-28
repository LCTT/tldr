# nginx

> Nginx 网页服务器
> 主页: <https://nginxorg/en/>

- 使用默认配置文件启动服务器：

`nginx`

- 使用自定义配置文件启动服务器：

`nginx -c {{config_file}}`

- 使用配置文件中所有相对路径的前缀启动服务器：

`nginx -c {{config_file}} -p {{prefix/for/relative/paths}}`

- 在不影响正在运行的服务器的情况下测试配置：

`nginx -t`

- 通过发送一个信号不停止服务来重新加载配置：

`nginx -s reload`

[#]: contributors: ([启威])