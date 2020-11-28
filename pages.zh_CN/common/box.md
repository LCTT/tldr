# box

> 用于构建和管理 Phar 的 PHP 应用程序

- 创建新的 Phar 文件：

`box build`

- 使用特定的配置文件生成新的 Phar 文件：

`box build -c {{path/to/config}}`

- 显示关于 Phar PHP 扩展的信息：

`box info`

- 显示有关特定 Phar 文件的信息：

`box info {{path/to/phar_file}}`

- 验证在工作目录中找到的第一个配置文件：

`box validate`

- 验证特定 Phar 文件的签名：

`box verify {{path/to/phar_file}}`

- 显示所有可用的命令和选项：

`box help`

[#]: contributors: ([琳小梁]，[　])