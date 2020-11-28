# mount

> 提供对一个目录中的整个文件系统的访问

- 显示所有挂载的文件系统：

`mount`

- 将设备挂载到目录：

`mount -t {{filesystem_type}} {{path/to/device_file}} {{path/to/target_directory}}`

- 将 CD-ROM 设备（文件类型为 ISO9660）挂载到 /cdrom （只读）：

`mount -t {{iso9660}} -o ro {{/dev/cdrom}} {{/cdrom}}`

- 挂载 /etc/fstab 中定义的所有文件系统：

`mount -a`

- 挂载 /etc/fstab 中描述的特定文件系统（例如："/dev/sda1 /my_drive ext2 defaults 0 2"）：

`mount {{/my_drive}}`

[#]: contributors: ([王兴宇]，[仁人])