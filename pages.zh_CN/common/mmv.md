# mmv

> 批量移动和重命名文件

- 将具有特定扩展名的所有文件重命名为其他扩展名：

`mmv "*{{.old_extension}}" "#1{{.new_extension}}"`

- 将 report6part4.txt 复制到 ./french/rapport6partie4.txt 以及所有类似命名的文件：

`mmv -c {{"report*part*.txt"}} {{"./french/rapport#1partie#2.txt"}}`

- 将所有 .txt 文件附加到一个文件中：

`mmv -a {{"*.txt"}} {{"all.txt"}}`

- 将文件名中的日期从 M-D-Y 格式转换为 D-M-Y 格式：

`mmv {{"[0-1][0-9]-[0-3][0-9]-[0-9][0-9][0-9][0-9].txt"}} {{"#3#4-#1#2-#5#6#7#8.txt"}}`

[#]: contributors: ([潘潘]，[玉叶])