# browser-sync

> 开启本地 web 服务器，并让浏览器实时响应文件更改

- 从特定目录开启一个服务器：

`browser-sync start --server {{path/to/directory}} --files {{path/to/directory}}`

- 从特定本地目录开启一个服务，用于监测某个目录下的 css 文件：

`browser-sync start --server --files '{{path/to/directory/*.css}}'`

- 创建配置文件：

`browser-sync init`

- 从配置文件开启 browser-sync ：

`browser-sync start --config {{config_file}}`

[#]: contributors: ([琳小梁]，[6 °分离]，[白宦成])