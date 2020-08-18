# stow

> 符号链接管理器
> 通常用于管理点文件

- 符号将所有文件递归链接到给定目录：

`stow --target={{path/to/target_directory}} {{file1 folder1 file2 folder2}}`

- 从给定目录中递归删除符号链接：

`stow --delete --target={{path/to/target_directory}} {{file1 folder1 file2 folder2}}`

- 模拟以查看结果：

`stow --simulate --target={{path/to/target_directory}} {{file1 folder1 file2 folder2}}`

- 删除并重新链接：

`stow --restow --target={{path/to/target_directory}} {{file1 folder1 file2 folder2}}`

- 排除与正则表达式匹配的文件：

`stow --ignore={{regex}} --target={{path/to/target_directory}} {{file1 folder1 file2 folder2}}`

[#]: contributors: ([玉叶])