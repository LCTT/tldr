# csvformat

> 转换 CSV 文件为自定义输出格式
> 包含在 csvkit 中

- 转换为以 tab 键作为分割符的文件 (TSV)：

`csvformat -T {{data.csv}}`

- 转换分隔符为自定义字符：

`csvformat -D "{{custom_character}}" {{data.csv}}`

- 将行尾转换为回车＋换行：

`csvformat -M "{{\r\n}}" {{data.csv}}`

- 尽量减少使用引号字符：

`csvformat -U 0 {{data.csv}}`

- 尽量增加引号字符的使用：

`csvformat -U 1 {{data.csv}}`

[#]: contributors: ([东先生])