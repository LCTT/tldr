# mknod

> 创建块或字符设备特殊文件

- 创建块设备：

`sudo mknod {{path/to/device_file}} b {{major_device_number}} {{minor_device_number}}`

- 创建字符设备：

`sudo mknod {{path/to/device_file}} c {{major_device_number}} {{minor_device_number}}`

- 创建一个 FIFO（队列）设备：

`sudo mknod {{path/to/device_file}} p`

- 创建一个带有默认 SELinux 安全上下文的设备文件：

`sudo mknod -Z {{path/to/device_file}} {{type}} {{major_device_number}} {{minor_device_number}}`

[#]: contributors: ([王兴宇，Linux & BC]，[玉叶]，[奇建]，[Cliff])