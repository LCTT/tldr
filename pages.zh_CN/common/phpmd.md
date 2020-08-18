# phpmd

> 一个PHP规则检测器，用于检查常见的潜在问题

- 显示可用规则和格式列表：

`phpmd`

- 使用逗号分隔的规则集扫描文件或目录以查找问题：

`phpmd {{path/to/file_or_directory}} {{xml|text|html}} {{rulesets}}`

- 指定规则的最低优先级阈值：

`phpmd {{path/to/file_or_directory}} {{xml|text|html}} {{rulesets}} --minimumpriority {{priority}}`

- 在分析中只包含指定的扩展：

`phpmd {{path/to/file_or_directory}} {{xml|text|html}} {{rulesets}} --suffixes {{extensions}}`

- 排除指定的逗号分隔目录：

`phpmd {{path/to/file_or_directory}} {{xml|text|html}} {{rulesets}} --exclude {{directory_patterns}}`

- 将结果输出到文件中，而不是控制台输出：

`phpmd {{path/to/file_or_directory}} {{xml|text|html}} {{rulesets}} --reportfile {{path/to/report_file}}`

- 忽略警告抑制PHPDoc注释的使用：

`phpmd {{path/to/file_or_directory}} {{xml|text|html}} {{rulesets}} --strict`

[#]: contributors: ([启威])