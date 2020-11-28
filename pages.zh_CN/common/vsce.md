# vsce

> Visual Studio Code 的扩展管理器

- 列出指定的发布者创建的所有扩展：

`vsce list {{publisher}}`

- 将扩展发布为主要版本、次要版本或修补程序版本：

`vsce publish {{major|minor|patch}}`

- 取消发布扩展：

`vsce unpublish {{extension_id}}`

- 将当前工作目录打包为 .vsix 文件：

`vsce package`

- 显示与扩展名关联的元数据：

`vsce show {{extension_id}}`

[#]: contributors: ([Datura stramonium L.])