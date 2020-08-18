# bmaptool

> 智能地创建或复制块映射（因此比 `cp` 或 `dd` 快）

- 从图像文件创建块映射：

`bmaptool create -o {{blockmap.bmap}} {{source.img}}`

- 将图像文件复制到 sdb 中：

`bmaptool copy --bmap {{blockmap.bmap}} {{source.img}} {{/dev/sdb}}`

- 将压缩图像文件复制到 sdb 中：

`bmaptool copy --bmap {{blockmap.bmap}} {{source.img.gz}} {{/dev/sdb}}`

- 不使用块映射将图像文件复制到 sdb 中：

`bmaptool copy --nobmap {{source.img}} {{/dev/sdb}}`

[#]: contributors: ([琳小梁]，[Datura stramonium L.])