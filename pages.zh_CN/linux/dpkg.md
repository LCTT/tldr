# dpkg

> Debian 包管理器

- 安装一个包：

`dpkg -i {{path/to/file.deb}}`

- 删除一个包：

`dpkg -r {{package_name}}`

- 列出已安装的程序包：

`dpkg -l {{pattern}}`

- 列出包内容：

`dpkg -L {{package_name}}`

- 列出本地包文件的内容：

`dpkg -c {{path/to/file.deb}}`

- 找出哪个包拥有文件：

`dpkg -S {{file_name}}`

[#]: contributors: ([琳小梁]，[Datura stramonium L.])