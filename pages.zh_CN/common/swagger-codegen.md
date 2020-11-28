# swagger-codegen

> 根据swagger文件(符合OpenAPI/swagger规范)生成提供RESTAPI Web服务的代码以及文档

- 根据指定 swagger 的文件生成对应编程语言 RESTAPI  服务的代码：

`swagger-codegen generate -i {{swagger_file}} -l {{language}}`

- 生成 RESTAPI 服务的 java 代码并基于 RXJava2 框架：

`swagger-codegen generate -i {{http://petstore.swagger.io/v2/swagger.json}} -l {{java}} --library {{retrofit2}} -D{{useRxJava2}}={{true}}`

- 列出支持的编程语言类型：

`swagger-codegen langs`

- generate 命令的帮助文档：

`swagger-codegen help {{generate}}`

[#]: contributors: ([航海])