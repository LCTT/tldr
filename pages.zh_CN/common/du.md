# du

> 磁盘使用率：估计和汇总文件、文件夹空间使用率

- 列出给定文件夹及其子文件夹的大小
（使用给定单位 B/KB/MB ）：

`du -{{b|k|m}} {{path/to/folder}}`

- 以可读形式列出文件夹和任何子文件夹的大小（即自动为每个大小选择适当的单位）：

`du -h {{path/to/folder}}`

- 用可读的方式显示单个文件夹的大小：

`du -sh {{path/to/folder}}`

- 以人类易读的格式显示一个文件夹及其里面所有文件和文件夹的大小：

`du -ah {{path/to/folder}}`

- 显示指定目录和子目录的大小，N指定子目录深度：

`du -h --max-depth=N {{path/to/folder}}`

- 列出当前目录下所有子目录下所有以 .jpg 结尾的文件，并以合适的单位展示占用的空间大小：

`du -ch */*.jpg`

[#]: contributors: ([玉叶]，[Yang]，[习习]，[张涛]，[winlans]，[Datura stramonium L.])