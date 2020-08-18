# ldconfig

> 为共享库依赖项配置符号链接和缓存

- 更新符号链接并重建缓存（通常在安装新库时运行）：

`sudo ldconfig`

- 更新给定目录的符号链接：

`sudo ldconfig -n {{path/to/directory}}`

- 打印缓存中的库并检查给定的库是否存在：

`ldconfig -p | grep {{library_name}}`

[#]: contributors: ([飞鸿影🌴])