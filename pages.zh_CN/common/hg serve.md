# hg serve

> 为浏览存储库启动独立的Mercurial Web服务器

- 启动 Web 服务器实例：

`hg serve`

- 在指定端口上启动 Web 服务器实例：

`hg serve --port {{port}}`

- 在指定的侦听地址上启动 Web 服务器实例：

`hg serve --address {{address}}`

- 使用特定标识符启动 Web 服务器实例：

`hg serve --name {{name}}`

- 使用指定的主题启动Web服务器实例（请参阅模板目录）：

`hg serve --style {{style}}`

- 使用指定的 SSL 证书包启动 Web 服务器实例：

`hg serve --certificate {{path/to/certificate}}`

[#]: contributors: ([潘潘]，[Judie])