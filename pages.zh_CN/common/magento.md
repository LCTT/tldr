# magento

> 用于管理 Magento PHP 框架的 CLI 

- 启用一个或多个空格分隔的模块：

`magento module:enable {{module(s)}}`

- 禁用一个或多个空格分隔的模块：

`magento module:disable {{module(s)}}`

- 启用模块后更新数据库：

`magento setup:upgrade`

- 更新代码和依赖注入配置：

`magento setup:di:compile`

- 部署静态资产：

`magento setup:static-content:deploy`

- 启用维护模式：

`magento maintenance:enable`

- 禁用维护模式：

`magento maintenance:disable`

- 列出所有可用命令：

`magento list`

[#]: contributors: ([潘潘])