# ebuild

> 与 Gentoo Portage 系统的低级接口

- 创建或更新包清单：

`ebuild {{path/to/file.ebuild}} manifest`

- 清除生成文件的临时生成目录：

`ebuild {{path/to/file.ebuild}} clean`

- 获取不存在的源：

`ebuild {{path/to/file.ebuild}} fetch`

- 将源提取到临时生成目录：

`ebuild {{path/to/file.ebuild}} unpack`

- 编译提取的源：

`ebuild {{path/to/file.ebuild}} compile`

- 将包安装到临时安装目录：

`ebuild {{path/to/file.ebuild}} install`

- 将临时文件安装到活动文件系统：

`ebuild {{path/to/file.ebuild}} qmerge`

- 获取、解包、编译、安装和 qmerge 指定的 ebuild 文件：

`ebuild {{path/to/file.ebuild}} merge`

[#]: contributors: ([玉叶])