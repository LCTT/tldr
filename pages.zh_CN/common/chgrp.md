# chgrp

> 改变文件或文件夹的所属用户组

- 改变一个文件/文件夹所属的用户组：

`chgrp {{group}} {{path/to/file_or_directory}}`

- 递归修改目录及目录内所有项目的用户组：

`chgrp -R {{group}} {{path/to/folder}}`

- 修改符号链接的用户组：

`chgrp -h {{group}} {{path/to/symlink}}`

- 以参考文件的用户组来设置一个文件或目录所属的用户组：

`chgrp --reference={{path/to/reference_file}} {{path/to/file_or_directory}}`

[#]: contributors: ([Jangrui]，[王兴宇，Linux & BC]，[xavier lee]，[Frederick])