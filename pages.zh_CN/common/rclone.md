# rclone

> 一个从许多云服务器中复制/同步/移动文件和目录命令行程序

- 列出 rclone 远程目录的内容：

`rclone lsf {{remote_name}}:{{path/to/directory}}`

- 将文件或目录从本地源复制到远程主机指到目录或文件：

`rclone copy {{path/to/source_file_or_directory}} {{remote_name}}:{{path/to/destination_directory}}`

- 将文件或目录从远程源复制到本地的目标路径：

`rclone copy {{remote_name}}:{{path/to/source_file_or_directory}} {{path/to/destination_directory}}`

- 将本地源同步到远程目标，仅更改目标文件（夹）：

`rclone sync {{path/to/file_or_directory}} {{remote_name}}:{{path/to/directory}}`

- 将文件或目录从本地源移动到远程目标文件或目录：

`rclone move {{path/to/file_or_directory}} {{remote_name}}:{{path/to/directory}}`

- 删除远程源的文件或目录（使用 `--dry-run` 进行测试，实际是直接删除）：

`rclone --dry-run delete {{remote_name}}:{{path/to/file_or_directory}}`

- 挂载 rclone 到本地目录（实验性）：

`rclone mount {{remote_name}}:{{path/to/directory}} {{path/to/mount_point}}`

- 如果 CTRL-C 失败，则卸载 rclone 远程源（实验性）：

`fusermount -u {{path/to/mount_point}}`

[#]: contributors: ([Nonamev]，[Datura stramonium L.])