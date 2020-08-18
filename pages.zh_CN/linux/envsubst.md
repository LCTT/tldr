# envsubst

> 用文本中的环境变量替换 shell 格式字符串
> 要替换的字符串应该是 $ {var} 或 $ var 格式

- 替换 stdin 中的环境变量并输出到 stdout ：

`echo '{{$HOME}}' | envsubst`

- 替换输入文件中的环境变量并输出到 stdout ：

`envsubst < {{path/to/input}}`

- 替换输入文件中的环境变量并输出到文件：

`envsubst < {{path/to/input}} > {{path/to/output}}`

- 从空格分隔的列表中替换输入中的环境变量：

`envsubst {{variables}} < {{path/to/input}}`

[#]: contributors: ([潘潘])