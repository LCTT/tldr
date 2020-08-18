# read

> 用于从标准输入中检索数据的 BASH 内置函数

- 从键盘输入获取数据：

`read {{variable}}`

- 将输入的每一行存储为数组的值：

`read -a {{array}}`

- 当用read输入时启用backspace和GNU readline热键：

`read -e {{variable}}`

- 指定要读取的最大字符数：

`read -n {{character_count}} {{variable}}`

- 使用特定字符作为分隔符，而不是换行符：

`read -d {{new_delimiter}} {{variable}}`

- 不使用反斜杠（ \ ）充当转义符：

`read -r {{variable}}`

- 在输入前显示提示：

`read -p {{"Enter your input here: "}} {{variable}}`

- 不回显键入的字符（静默模式）：

`read -s {{variable}}`

[#]: contributors: ([Datura stramonium L.])