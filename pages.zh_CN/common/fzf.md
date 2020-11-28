# fzf

> 命令行模糊搜索

- 从任意位置开始查找所有文件：

`find {{path/to/search}} -type f | fzf`

- 在运行的进程上启动 finder ：

`ps aux | fzf`

- 使用 Shift + Tab 选择多个文件并写入文件：

`find {{path/to/search_files}} -type f | fzf -m > {{filename}}`

- 使用给定查询启动查找程序：

`fzf -q "{{query}}"`

- 在以 core 开头并以 go，rb 或 py 结尾的条目上启动 finder ：

`fzf -q "^core go$ | rb$ | py$"`

- 在与 pyc 不匹配的条目上启动查找器并完全匹配travis ：

`fzf -q "!pyc 'travis"`

[#]: contributors: ([潘潘]，[ACG-SAKURA])