# qemu

> 通用的计算机仿真化和虚拟化工具
> 支持大量 CPU 架构
> 主页: <https://wwwqemuorg>

- 从一个镜像模拟 i386 架构启动：

`qemu-system-i386 -hda {{image_name.img}}`

- 从一个镜像模拟 x64 架构启动：

`qemu-system-x86_64 -hda {{image_name.img}}`

- 使用 ISO 映像启动 QEMU 实例：

`qemu-system-i386 -hda {{image_name.img}} -cdrom {{os_image.iso}} -boot d`

- 例如，指定RAM的数量：

`qemu-system-i386 -m 256 -hda image_name.img -cdrom os-image.iso -boot d`

- 从物理设备启动（例如从USB启动到测试可启动介质）：

`qemu-system-i386 -hda /dev/{{storage_device}}`

[#]: contributors: ([Datura stramonium L.]，[Judie]，[jim.大团结]，[王兴宇]，[悄咪咪])