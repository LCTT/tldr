# gnuplot

> 以多种格式输出的图形绘图仪

- 启动交互式图形绘制shell ：

`gnuplot`

- 绘制指定图形定义文件的图形：

`gnuplot {{path/to/definition.plt}}`

- 通过在加载定义文件之前执行命令来设置输出格式：

`gnuplot -e "{{set output "path/to/filename.png" size 1024,768}}" {{path/to/definition.plt}}`

- gnuplot 退出后，保持图形图预览窗口：

`gnuplot --persist {{path/to/definition.plt}}`

[#]: contributors: ([潘潘])