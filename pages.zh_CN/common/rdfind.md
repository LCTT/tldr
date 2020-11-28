# rdfind

> 找到包含重复内容的文件并将其删除

- 识别给定目录中的所有重复项并输出摘要：

`rdfind -dryrun true {{path/to/directory}}`

- 用硬链接替换所有副本：

`rdfind -makehardlinks true {{path/to/directory}}`

- 用符号链接或软链接替换所有重复项：

`rdfind -makesymlinks true {{path/to/directory}}`

- 删除所有重复项，不忽略空文件：

`rdfind -deleteduplicates true -ignoreempty false {{path/to/directory}}`

[#]: contributors: ([Datura stramonium L.])