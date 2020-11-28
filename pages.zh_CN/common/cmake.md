# cmake

> 跨平台构建系统生成程序
> 根据目标系统的不同，它会生成 Makefile、Visual Studio 项目文件或其它文件

- 生成一个 Makefile，并使用它编译源文件与它位于同一文件夹中的项目：

`cmake && make`

- 生成一个 Makefile，并使用它编译在单独的 “build” 文件夹中的项目（源代码外构建）：

`cmake -H. -B{{build}} && make -C {{build}}`

- 在交互模式下运行 cmake（它将询问每个变量，而不是使用默认值）：

`cmake -i`

[#]: contributors: ([仁人]，[王兴宇]，[Datura stramonium L.])