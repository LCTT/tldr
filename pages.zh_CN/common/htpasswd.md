# htpasswd

> 创建和管理 htpasswd 文件来用基本认证手段来保护 Web 服务器上的文件夹

- 创建或重写 htpasswd 文件：

`htpasswd -c {{path/to/file}} {{user_name}}`

- 将用户添加到 htpasswd 文件或更新现有用户：

`htpasswd {{path/to/file}} {{user_name}}`

- 在批处理模式下将用户添加到 htpasswd 文件，而不需要交互式密码提示（用于脚本使用）：

`htpasswd -b {{path/to/file}} {{user_name}} {{password}}`

- 从 htpasswd 中删除用户：

`htpasswd -D {{path/to/file}} {{user_name}}`

- 验证用户密码：

`htpasswd -v {{path/to/file}} {{user_name}}`

[#]: contributors: ([东先生]，[玉叶]，[Frederick])