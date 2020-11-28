# locate

> 快速查找文件名

- 在数据库中查找文件信息注意：数据库定期更新（通常周期是每周或每天）：

`locate {{pattern}}`

- 按确切的文件名称查找文件（没有包含通配符的查找模式将被视为 `*模式*`）：

`locate */{{filename}}`

- 更新文件数据库必须首先执行此条命令，你才能查询到最近新增的文件：

`sudo updatedb`

[#]: contributors: ([王兴宇，Linux & BC]，[Mr. Ren]，[Drake]，[jim.大团结]，[Datura stramonium L.])