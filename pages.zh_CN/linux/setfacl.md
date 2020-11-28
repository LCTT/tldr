# setfacl

> 设置文件访问控制列表（ACL）

- 编辑文件的ACL规则（用户的读写权限）：

`setfacl -m u:{{username}}:rw {{file}}`

- 编辑文件默认对所有用户的ACL规则：

`setfacl -d -m u::rw {{file}}`

- 移除文件对用户的ACL规则：

`setfacl -x u:{{username}} {{file}}`

- 移除文件所有的ACL规则：

`setfacl -b {{file}}`

[#]: contributors: ([盛曦 姜])