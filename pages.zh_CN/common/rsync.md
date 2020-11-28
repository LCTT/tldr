# rsync

> 在本地和远端主机间传输文件（非两个远端主机之间）
> 可以传输单个文件或者匹配某个模式的多个文件

- 传输本地文件到远端：

`rsync {{path/to/file}} {{remote_host_name}}:{{remote_host_location}}`

- 下载远端文件到本地：

`rsync {{remote_host_name}}:{{remote_file_location}} {{local_file_location}}`

- 以归档（保持属性）和压缩（使用 zipped ）模式传输文件，同时显示详细的、友好可读的进度：

`rsync -azvhP {{path/to/file}} {{remote_host_name}}:{{remote_host_location}}`

- 传输远端主机目录及子目录到本地：

`rsync -r {{remote_host_name}}:{{remote_directory_location}} {{local_directory_location}}`

- 只从远端下载有更新的文件：

`rsync -ru {{remote_host_name}}:{{remote_directory_location}} {{local_directory_location}}`

- 通过 SSH 传输文件，并删除只存在于本地远端没有的文件：

`rsync -e ssh --delete {{remote_host_name}}:{{remote_file}} {{local_file}}`

- 通过 SSH 传输文件并显示全局进度：

`rsync -e ssh --info=progress2 {{remote_host_name}}:{{remote_file}} {{local_file}}`

[#]: contributors: ([󠀀]，[皓月当空])