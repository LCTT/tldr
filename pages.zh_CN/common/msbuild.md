# msbuild

> Visual Studio 项目解决方案的微软编译工具

- 在当前目录编译第一个项目文件：

`msbuild`

- 编译一个指定项目：

`msbuild {{path/to/project_file}}`

- 设置一个或多个以分号分隔的目标进行构建：

`msbuild {{path/to/project_file}} /target:{{targets}}`

- 设置一个或多个以分号分隔的属性：

`msbuild {{path/to/project_file}} /property:{{name=value}}`

- 设置编译器版本来执行：

`msbuild {{path/to/project_file}} /toolsversion:{{version}}`

- 在日志末尾显示有关项目配置方式的详细信息：

`msbuild {{path/to/project_file}} /detailedsummary`

- 显示详细帮助信息：

`msbuild /help`

[#]: contributors: ([潘潘]，[jim.大团结])