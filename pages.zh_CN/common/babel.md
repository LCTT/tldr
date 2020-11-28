# babel

> JavaScript 代码转译器，将 ES6/ES7 语法转换为 ES5 语法

- 转译指定文件并显示在标准输出上：

`babel {{path/to/file}}`

- 将指定的输入文件转换并输出到特定文件：

`babel {{path/to/input_file}} --out-file {{path/to/output_file}}`

- 监听指定文件，发生更改后转译文件：

`babel {{path/to/input_file}} --watch`

- 转译指定目录下的所有文件：

`babel {{path/to/input_directory}}`

- 转译时忽略指定文件（多个文件可以用逗号隔开）：

`babel {{path/to/input_directory}} --ignore {{ignored_files}}`

- 转译并压缩 js 代码：

`babel {{path/to/input_file}} --minified`

- 为代码输出格式选择预设：

`babel {{path/to/input_file}} --presets {{presets}}`

- 显示所有可选项：

`babel --help`

[#]: contributors: ([琳小梁]，[jim.大团结]，[李峰])