# cradle elastic

> 管理 Cradle 实例的 ElasticSearch 实例

- 截断 ElasticSearch 的索引：

`cradle elastic flush`

- 截断特定包的 ElasticSearch 索引：

`cradle elastic flush {{package_name}}`

- 提交 ElasticSearch 架构：

`cradle elastic map`

- 提交特定包的 ElasticSearch 架构：

`cradle elastic map {{package_name}}`

- 填充所有包的 ElasticSearch 索引：

`cradle elastic populate`

- 填充特定包的 ElasticSearch 索引：

`cradle elastic populate {{package_name}}`

[#]: contributors: ([潘潘])