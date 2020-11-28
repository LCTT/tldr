# phpcs

> 字元化 PHP、JavaScript 和 CSS 文件，以检测是否违反了已定义的编码标准

- 嗅探指定目录中的问题(默认为PEAR标准)：

`phpcs {{path/to/directory}}`

- 显示已安装的编码标准列表：

`phpcs -i`

- 指定要验证的编码标准：

`phpcs {{path/to/directory}} --standard {{standard}}`

- 指定嗅探时要包含的文件扩展名：

`phpcs {{path/to/directory}} --extensions {{file_extension(s)}}`

- 指定输出报告的格式（例如 “full”、 “xml”、 “json”、 “summary”）：

`phpcs {{path/to/directory}} --report {{format}}`

- 设置在嗅探过程中使用的配置变量：

`phpcs {{path/to/directory}} --config-set {{key}} {{value}}`

- 处理前要加载的以逗号分隔的文件列表：

`phpcs {{path/to/directory}} --bootstrap {{file(s)}}`

- 不要递归进入子目录：

`phpcs {{path/to/directory}} -l`

[#]: contributors: ([王兴宇，Linux 中國]，[启威])