# umount

> 取消文件系统与其挂载点的链接，使其不再可访问
> 使用中的文件系统无法卸载

- 卸载文件系统，通过传递已挂载设备路径来卸载文件系统：

`umount {{path/to/device_file}}`

- 卸载文件系统，通过传递已挂载目录路径来卸载文件系统：

`umount {{path/to/mounted_directory}}`

- 卸载全部已挂载的文件系统(排除 `proc` 文件系统)：

`umount -a`

[#]: contributors: ([Mr. Ren]，[石头])