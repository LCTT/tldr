# rpm

> RPM包管理器

- 显示 httpd 包的版本：

`rpm -q {{httpd}}`

- 列出所有匹配的版本：

`rpm -qa '{{mariadb*}}'`

- 识别文件的所有者并显示包的版本：

`rpm -qf {{/etc/postfix/main.cf}}`

- 列出软件包所含的文件：

`rpm -ql {{kernel}}`

- 显示 RPM 文件中的脚本：

`rpm -qp --scripts {{some.rpm}}`

- 显示对应包的安装文件的改动、丢失或者错误：

`rpm -Va '{{php-*}}'`

[#]: contributors: ([王兴宇，Linux 中國]，[苏保平]，[盛曦 姜]，[Alien])