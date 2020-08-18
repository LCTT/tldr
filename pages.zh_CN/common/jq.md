# jq

> 一个轻量级且灵活的命令行 JSON 处理器

- 以漂亮的打印格式输出 JSON 文件：

`jq . {{file.json}}`

- 在JSON文件中输出数组中的所有元素（或对象中的所有键值对）：

`jq .[] {{file.json}}`

- 将JSON对象从文件读取到数组中，然后输出它（与'jq.[]`'相反）：

`jq --slurp . {{file.json}}`

- 输出 JSON 文件的第一个元素：

`jq .[0] {{file.json}}`

- 从标准输入读取 JSON 文本，输出第一个元素的给定键的值：

`cat {{file.json}} | jq .[0].{{key_name}}`

- 从标准输入读取 JSON 文本，输出每个元素给定键对应的值：

`cat {{file.json}} | jq 'map(.{{key_name}})'`

[#]: contributors: ([Judie]，[良†]，[jim.大团结]，[王康🌀]，[骞树]，[AA-Walt])