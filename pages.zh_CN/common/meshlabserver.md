# meshlabserver

> MeshLab 3D 网格处理软件的命令行界面
> 显示当前过滤器脚本 > 保存脚本 ):

- 将 STL 文件转换为 OBJ 文件：

`meshlabserver -i {{input.stl}} -o {{output.obj}}`

- 将 WRL 文件转换为 OFF 文件，包括输出网格中的顶点和面法线：

`meshlabserver -i {{input.wrl}} -o {{output.off}} -om vn fn`

- 将所有可用处理过滤器的列表转储到文件中：

`meshlabserver -d {{filename}}`

- 使用在 MeshLab GUI 中创建的过滤器脚本处理 3D 文件（过滤器>显示当前过滤器脚本>保存脚本）：

`meshlabserver -i {{input.ply}} -o {{output.ply}} -s {{filter_script.mlx}}`

- 使用过滤器脚本处理 3D 文件，将过滤器的输出写入日志文件：

`meshlabserver -i {{input.x3d}} -o {{output.x3d}} -s {{filter_script.mlx}} -l {{logfile}}`

[#]: contributors: ([潘潘])