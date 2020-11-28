# json5

> 一个将json5文件转换为json的命令行工具

- 将 JSON5 的标准输入转换为 JSON 标准输出：

`echo {{input}} | json5`

- 将 JSON5 文件转换为 JSON 并输出到标准输出：

`json5 {{path/to/input_file.json5}}`

- 将 JSON5 文件转换为指定的 JSON 文件：

`json5 {{path/to/input_file.json5}} --out-file {{path/to/output_file.json}}`

- 验证 JSON5 文件：

`json5 {{path/to/input_file.json5}} --validate`

- 指定缩进的空格数（或标签的 “t” ）：

`json5 --space {{indent_amount}}`

- 查看可用选项：

`json5 --help`

[#]: contributors: ([潘潘]，[诗翔]，[徐律])