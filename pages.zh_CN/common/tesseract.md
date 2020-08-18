# tesseract

> 文字识别引擎

- 识别图片中的文字并保存在 "output.txt" 文件中：

`tesseract {{image.png}} {{output}}`

- 指定 ISO 639-2 语言编码中的一种语言（默认为英语）用法：deu =Deutsch = German：

`tesseract -l deu {{image.png}} {{output}}`

- 列出 ISO 639-2 语言编码标准中所有可用语言：

`tesseract --list-langs`

- 指定分段模式 (默认为3个段落)：

`tesseract -psm {{0_to_10}} {{image.png}} {{output}}`

- 查看所有分段模式的详细信息：

`tesseract --help-psm`

[#]: contributors: ([Mr. Ren])