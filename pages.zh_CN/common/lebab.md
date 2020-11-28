# lebab

> 用于将代码转换为ES6 / ES7的JavaScript工具
> 必须为所有示例提供转换

- 列出文档：

`lebab --help`

- 使用一个或多个以逗号分隔的转换进行透明：

`lebab --transform {{transformation}}`

- 将文件透明到 stdout ：

`lebab {{path/to/input_file}}`

- 将文件透明到指定的输出文件：

`lebab {{path/to/input_file}} --out-file {{path/to/output_file}}`

- 在指定目录，glob 或文件中就地替换所有 .js 文件：

`lebab --replace {{directory|glob|file}}`

[#]: contributors: ([潘潘]，[Eski])