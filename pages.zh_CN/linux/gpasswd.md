# gpasswd

> 管理 /etc/group 和 /etc/gshadow 

- 定义组管理员：

`sudo gpasswd -A {{user1,user2}} {{group}}`

- 设置组成员列表：

`sudo gpasswd -M {{user1,user2}} {{group}}`

- 为已命名组创建密码：

`gpasswd {{group}}`

- 把user用户添加到group 组：

`gpasswd -a {{user}} {{group}}`

- 把user用户从group 组里面删除：

`gpasswd -d {{user}} {{group}}`

[#]: contributors: ([潘潘]，[jim.大团结]，[阿不])