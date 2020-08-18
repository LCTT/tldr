# postcss

> PostCSS 是使用 JS 插件转译样式的工具
> 主页地址: <https://postcssorg>

- 转译样式文件：

`postcss {{path/to/file}}`

- 转译样式文件并输出到指定文件：

`postcss {{path/to/file}} --output {{path/to/file}}`

- 转译样式文件并输出到指定目录：

`postcss {{path/to/file}} --dir {{path/to/directory}}`

- 解析转译样式文件并替换原文：

`postcss {{path/to/file}} --replace`

- 指定 PostCSS 使用定制解析器：

`postcss {{path/to/file}} --parser {{parser}}`

- 指定 PostCSS 使用定制语法：

`postcss {{path/to/file}} --syntax {{syntax}}`

- 监听样式文件改变：

`postcss {{path/to/file}} --watch`

- 显示可用选项和示例：

`postcss --help`

[#]: contributors: ([李峰])