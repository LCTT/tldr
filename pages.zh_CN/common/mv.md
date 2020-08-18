# mv

> 移动或重命名文件和目录

- 在任意位置移动文件：

`mv {{source}} {{target}}`

- 覆盖已有的目标文件时不给任何提示：

`mv -f {{source}} {{target}}`

- 若指定目录已有同名文件，则先询问是否覆盖旧文件：

`mv -i {{source}} {{target}}`

- 如果目标已存在该文件，则不覆盖：

`mv -n {{source}} {{target}}`

- 显示文件移动的详情，移动后显示文件：

`mv -v {{source}} {{target}}`

[#]: contributors: ([i禹州]，[吴逸绿]，[王兴宇]，[大树.]，[1]，[柠檬])