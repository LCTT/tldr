# assimp

> 用于打开资源导入库的命令行客户端
> 支持加载 40+ 种 3D 文件格式，并导出为几种常用的 3D 格式

- 列出所有支持的导入格式：

`assimp listext`

- 列出所有支持的导出格式：

`assimp listexport`

- 使用默认参数将文件转换为支持的输出格式之一：

`assimp export {{input_file.stl}} {{output_file.obj}}`

- 使用自定义参数转换文件
（ assimp 源代码中的 dox_cmd.h 文件列出了可用参数）：

`assimp export {{input_file.stl}} {{output_file.obj}} {{parameters}}`

- 显示 3D 文件内容的摘要：

`assimp info {{path/to/file}}`

- 列出所有支持的子命令（即“verb”）：

`assimp help`

- 获取特定子命令的帮助（例如特定于它的参数）：

`assimp {{subcommand}} --help`

[#]: contributors: ([王兴宇，Linux & BC]，[Datura stramonium L.]，[玉叶])