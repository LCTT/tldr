# chown

> 更改文件和文件夹所属用户和用户组

- 改变一个文件/目录的拥有者：

`chown {{user}} {{path/to/file_or_directory}}`

- 更改一个文件/文件夹的所属用户和用户组：

`chown {{user}}:{{group}} {{path/to/file_or_directory}}`

- 递归改变一个目录及其内容的所属用户：

`chown -R {{user}} {{path/to/folder}}`

- 改变一个符号链接的所属用户：

`chown -h {{user}} {{path/to/symlink}}`

- 以参考文件的所属用户来设置一个文件或目录的所属用户：

`chown --reference={{path/to/reference_file}} {{path/to/file_or_directory}}`

[#]: contributors: ([Jangrui]，[王兴宇]，[Frederick]，[📶㊙古浪雨💯💎💎💎💎💎])