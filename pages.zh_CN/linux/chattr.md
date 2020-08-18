# chattr

> 修改文件或文件夹的属性

- 使文件或目录对更改和删除不可变，即使是超级用户：

`chattr +i {{path/to/file_or_directory}}`

- 使文件或目录可变：

`chattr -i {{path/to/file_or_directory}}`

- 递归地使整个文件夹和内容不可变：

`chattr -R +i {{folder}}`

[#]: contributors: ([子不语]，[启威]，[陈俊龙])