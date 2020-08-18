# reflector

> Arch Linux 上用来获取和排序镜像列表的脚本

- 获取所有镜像源，并按下载速度排序并保存它们：

`sudo reflector --sort {{rate}} --save {{/etc/pacman.d/mirrorlist}}`

- 仅获取德国 HTTPS 镜像：

`reflector --country {{Germany}} --protocol {{https}}`

- 只获取最近 10 个同步镜像：

`reflector --latest {{10}}`

[#]: contributors: ([Datura stramonium L.])