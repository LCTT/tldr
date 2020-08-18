# find

> 在给定的目录树中递归地查找文件或目录

- 查找特定后缀的文件：

`find {{root_path}} -name '{{*.ext}}'`

- 查找匹配多个模式之一的文件：

`find {{root_path}} -name '{{*pattern_1*}}' -or -name '{{*pattern_2*}}'`

- 查找匹配给定名称的目录：

`find {{root_path}} -type d -name {{*lib*}}`

- 查找匹配给定路径模式的文件：

`find {{root_path}} -path '{{**/lib/**/*.ext}}'`

- 对搜索到的每个文件执行一个命令，在要执行的命令中使用 `{}` 表示搜索到的文件名：

`find {{root_path}} -name '{{*.ext}}' -exec {{wc -l {} }}\;`

- 查找最近 1天（24小时）内被修改过的文件：

`find {{root_path}} -mtime {{-1}}`

- 按指定文件大小，且不区分大小写来匹配文件名进行文件查找：

`find {{root_path}} -size {{+500k}} -size {{-10M}} -iname '{{*.TaR.gZ}}'`

- 删除符合文件名称模式，且（上次修改后）超过 180 天的文件：

`find {{root_path}} -name '{{*.ext}}' -mtime {{+180}} -delete`

- 查找匹配给定文件类型，同时（查找过程中）排除某些特定路径：

`find {{root_path}} -name '{{*.py}}' -not -path '{{*/site-packages/*}}'`

[#]: contributors: ([KIP]，[梦还在继续]，[王兴宇，Linux & BC]，[毅如既往]，[张爱峰]，[A01孙行者¹²³⁴5]，[Shannon]，[钟杰]，[Drake]，[易金金]，[Trekcy]，[吴政行]，[Basil]，[lc]，[Finder])