# inkscape

> SVG (可缩放矢量图形) 编辑程序
> 使用-z 不打开 GUI, 只处理控制台中的文件

- 在 Inkscape GUI 中打开 SVG 文件：

`inkscape {{filename.svg}}`

- 将 SVG 文件导出到具有默认格式 (PNG) 和默认分辨率 (90 DPI) 的位图中：

`inkscape {{filename.svg}} -e {{filename.png}}`

- 将 SVG 文件导出为 600x400 像素的位图（可能会出现宽高比失真）：

`inkscape {{filename.svg}} -e {{filename.png}} -w {{600}} -h {{400}}`

- 将给定 ID 的单个对象导出到位图中：

`inkscape {{filename.svg}} -i {{id}} -e {{object.png}}`

- 将 SVG 文档导出为 PDF ，将所有文本转换为路径：

`inkscape {{filename.svg}} --export-pdf={{filename.pdf}} --export-text-to-path`

- 使用 id="path123 " 复制对象, 将重复的90度旋转, 保存文件, 然后退出 Inkscape：

`inkscape {{filename.svg}} --select=path123 --verb=EditDuplicate --verb=ObjectRotate90 --verb=FileSave --verb=FileQuit`

[#]: contributors: ([潘潘]，[Judie])