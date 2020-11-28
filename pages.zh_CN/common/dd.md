# dd

> 转换并复制一个文件

- 从一个 isohybrid 文件（如 archlinux-xxx.iso）制作一个可引导 USB 驱动器，并显示进度：

`dd if={{file.iso}} of=/dev/{{usb_drive}} status=progress`

- 以 4MB 为一个数据块，将驱动器克隆到另一个驱动器上，忽略错误并显示进度：

`dd if=/dev/{{source_drive}} of=/dev/{{dest_drive}} bs=4M conv=noerror status=progress`

- 使用内核随机驱动程序生成一个 100 个随机字节的文件：

`dd if=/dev/urandom of={{随机文件}} bs=100 count=1`

- 测试一块硬盘的写入性能：

`dd if=/dev/zero of={{file_1GB}} bs=1024 count=1000000`

- 检查正在进行的 dd 操作的进度（从另一个 shell 运行此命令）：

`kill -USR1 $(pgrep ^dd)`

[#]: contributors: ([王兴宇]，[Datura stramonium L.]，[Frederick]，[白宦成])