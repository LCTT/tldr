# repren

> 多模式字符串替换和文件重命名工具
> 主页：<https://githubcom/jlevy/repren> 

- 对匹配该字符串的 png 文件试运行重命名操作：

`repren --dry-run --rename --literal --from '{{find_string}}' --to '{{replacement_string}}' {{*.png}}`

- 对匹配该正则表达式的 jpg 和 jpeg 文件试运行重命名操作：

`repren --rename --dry-run --from '{{regular_expression}}' --to '{{replacement_string}}' {{*.jpg}} {{*.jpeg}}`

- 对 csv 文件的内容用正则表达式进行查找和替换：

`repren --from '{{([0-9]+) example_string}}' --to '{{replacement_string \1}}' {{*.csv}}`

- 通过模式文件，同时对文件进行重命名和内容替换：

`repren --patterns {{path/to/patfile.ext}} --full {{*.txt}}`

- 忽略大小写进行重命名：

`repren --rename --insensitive --patterns {{path/to/patfile.ext}} *`

[#]: contributors: ([王興與·璃霓思硬核]，[王兴宇，Linux & BC])