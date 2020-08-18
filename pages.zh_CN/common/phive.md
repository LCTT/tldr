# phive

> phive（Phar 安装验证环境）用来加强 PHP 应用部署的安全

- 显示可用的别名化的 Phar 列表：

`phive list`

- 安装一个指定的 Phar 到本地目录：

`phive install {{alias|url}}`

- 全局安装一个指定的 Phar：

`phive install {{alias|url}} --global`

- 安装一个指定的 Phar 到目标目录：

`phive install {{alias|url}} --target {{path/to/directory}}`

- 更新所有的 Phar 文件为最新版本：

`phive update`

- 移除一个指定的 Phar 文件：

`phive remove {{alias|url}}`

- 移除未使用的 Phar 文件：

`phive purge`

- 列出所有可用命令：

`phive help`

[#]: contributors: ([王興與·區塊鏈·Linux中國])