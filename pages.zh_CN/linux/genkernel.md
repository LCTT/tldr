# genkernel

> Gentoo Linux编译安装内核的工具

- 自动编译并安装通用内核：

`sudo genkernel all`

- 只构建并安装 bzImage或initramfs或kernel或ramdisk：

`sudo genkernel {{bzImage|initramfs|kernel|ramdisk}}`

- 在编译安装前，生效内核配置的变更：

`sudo genkernel --menuconfig all`

- 使用自定义的命名生成内核：

`sudo genkernel --kernname={{custom_name}} all`

- 使用自定义路径的内核源码，而不是默认目录/usr/src/linux：

`sudo genkernel --kerneldir={{path/to/directory}} all`

[#]: contributors: ([Sellente_Wang])