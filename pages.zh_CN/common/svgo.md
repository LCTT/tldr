# svgo

> SVG 优化器：基于 Nodejs 优化可缩放失量图形文件的工具
> 其应用了一系列的转换规则（插件），这些插件可以单独开关

- 使用默认插件优化指定 SVG 文件（替换掉原文件）：

`svgo {{test.svg}}`

- 优化指定 SVG 文件，将结果保存到指定文件：

`svgo {{test.svg}} {{test.min.svg}}`

- 优化指定目录内所有 SVG 文件（替换掉原文件）：

`svgo -f {{path/to/folder/with/svg/files}}`

- 优化指定目录的所有 SVG 文件，保存到指定目录：

`svgo -f {{path/to/input/folder}} -o {{path/to/output/folder}}`

- 优化从其他命令传来的 SVG 内容，将结果保存到指定文件：

`{{cat test.svg}} | svgo -i - -o {{test.min.svg}}`

- 优化指定 svg 文件并打印结果：

`svgo {{test.svg}} -o -`

- 优化处理时确保指定插件已启用：

`svgo --enable={{plugin_name}}`

- 显示可用插件：

`svgo --show-plugins`

[#]: contributors: ([李峰])