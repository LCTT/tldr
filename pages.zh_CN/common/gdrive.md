# gdrive

> Google 云端硬盘交互命令行工具
> 可以从Google云端硬盘文件管理器或 id 网址获取文件夹/文件 ID

- 将本地文件或目录上传到指定文件夹：

`gdrive upload -p {{id}} {{path/to/file_or_folder}}`

- 按ID将文件或目录下载到当前目录：

`gdrive download {{id}}`

- 通过所给 id 下载到指定的本地路径：

`gdrive download --path {{path/to/folder}} {{id}}`

- 使用指定文件或文件夹创建一个新的修订：

`gdrive update {{id}} {{path/to/file_or_folder}}`

[#]: contributors: ([Jangrui])