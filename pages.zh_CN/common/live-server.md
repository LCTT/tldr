# live-server

> 具有实时重新加载功能的简单开发HTTP服务器

- 提供index.html文件并在更改时重新加载：

`live-server`

- 指定为文件提供服务的端口（默认为8080）：

`live-server --port={{8081}}`

- 指定要服务的给定文件：

`live-server --open={{about.html}}`

- 代理所有路由到URL的请求：

`live-server --proxy={{/}}:{{http:localhost:3000}}`

[#]: contributors: ([Judie])