# pkgmk

> 制作一个二进制软件包，以供 CRUX 上的 `pkgadd` 使用

- 制作并下载软件包：

`pkgmk -d`

- 在制作完成后安装该软件包：

`pkgmk -d -i`

- 在制作完成后升级该软件包：

`pkgmk -d -u`

- 制作软件包时忽略指纹：

`pkgmk -d -if`

- 制作软件包时忽略 MD5 校验

：

`pkgmk -d -im`

- 更新软件包指纹：

`pkgmk -uf`

[#]: contributors: ([王興與]，[王兴宇]，[Datura stramonium L.])