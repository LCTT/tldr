# qemu-img

> 用于快速仿真器虚拟硬盘图像创建和操作的工具

- 创建一个指定大小的磁盘镜像（单位为 GB ）：

`qemu-img create {{image_name.img}} {{gigabites}}G`

- 显示磁盘镜像的信息：

`qemu-img info {{image_name.img}}`

- 增大或者缩小镜像体积：

`qemu-img resize {{image_name.img}} {{gigabites}}G`

- 转储指定磁盘映像的每个扇区的分配状态：

`qemu-img map {{image_name.img}}`

[#]: contributors: ([Judie]，[Mr. Ren])