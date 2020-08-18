# iconv

> 将文本从一种编码转换为另一种编码
> -

- 将文件转换为指定的编码，并输出到 stdout（标准输出，一般为屏幕）：

`iconv -f {{from_encoding}} -t {{to_encoding}} {{input_file}}`

- 将文件转换为当前语言环境的编码并输出到指定文件：

`iconv -f {{from_encoding}} {{input_file}} > {{output_file}}`

- 列出所有本机支持的编码：

`iconv -l`

[#]: contributors: ([　]，[ZH]，[一笑])