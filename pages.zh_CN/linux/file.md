# file

> 判定文件类型

- 输出指定文件的文件描述，即使没有文件扩展名也能正常工作：

`file {{filename}}`

- 判定压缩文件内部文件的文件类型：

`file -z {{foo.zip}}`

- 允许 file 命令判定特殊文件或设备文件：

`file -s {{filename}}`

- 在第一次文件类型匹配时不停止，一直匹配到文件结尾：

`file -k {{filename}}`

- 输出文件的 mime 类型字符串：

`file -i {{filename}}`

[#]: contributors: ([王兴宇]，[牛祺君])