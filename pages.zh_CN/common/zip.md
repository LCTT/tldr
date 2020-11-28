# zip

> 把文件打包和压缩（存档）成 zip 格式的

- 递归打包和压缩目录及目录里的内容：

`zip -r {{compressed.zip}} {{/path/to/dir}}`

- 压缩时排除不想添加的文件：

`zip -r {{compressed.zip}} {{path/to/dir}} -x {{path/to/exclude}}`

- 使用最高级的压缩效率 [9] 归档文件：

`zip -r -{{9}} {{compressed.zip}} {{/path/to/dir}}`

- 打包和压缩多个目录和文件：

`zip -r {{compressed.zip}} {{/path/to/dir1 /path/to/dir2 /path/to/file}}`

- 创建一个加密的归档（提示用户输入密码）：

`zip -e -r {{compressed.zip}} {{path/to/dir}}`

- 把文件添加到一个存在的 zip 文件：

`zip {{compressed.zip}} {{path/to/file}}`

- 删除 zip 文件中指定的文件：

`zip -d {{compressed.zip}} "{{foo/*.tmp}}"`

- 把目录和内容归档成多个分割的 zip 文件（例如：每部分3GB）：

`zip -r -s {{3g}} {{compressed.zip}} {{path/to/dir}}`

[#]: contributors: ([Johnny.Li])