# patch

> 使用差异文件对一个或多个文件打补丁
> 注意差异文件包含了目标文件名和发生的变更的列表

- 应用一个补丁：

`patch < {{patch_file}}.diff`

- 应用一个补丁到当前文件夹：

`patch -p1 < {{patch_file}}.diff`

- 撤销一个补丁：

`patch -R < {{patch_file}}.diff`

[#]: contributors: ([XXX])