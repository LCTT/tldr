# cradle sql

> 管理 Cradle SQL 数据库

- 重建数据库架构：

`cradle sql build`

- 重建特定包的数据库架构：

`cradle sql build {{package_name}}`

- 清空整个数据库：

`cradle sql flush`

- 清空特定包的数据库表：

`cradle sql flush {{package_name}}`

- 填充所有包的表：

`cradle sql populate`

- 填充特定包的表：

`cradle sql populate {{package_name}}`

[#]: contributors: ([潘潘])