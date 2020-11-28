# losetup

> 设置管理回还设备

- 列出所有回环设备的详细信息：

`losetup -a`

- 把文件附加在回环设备上：

`sudo losetup /dev/{{loop}} /{{path/to/file}}`

- 卸载所有回环设备：

`sudo losetup -D`

- 卸载指定的回环设备：

`sudo losetup -d /dev/{{loop}}`

[#]: contributors: ([Mr. Ren])