# fsck

> 检查文件系统的完整性或进行修复应在运行命令时确保文件系统已被卸载

- 检查文件系统 /dev/sda，报告任何已损坏的块：

`fsck {{/dev/sda}}`

- 检查文件系统 /dev/sda，报告任何已损坏的块并以交互方式让用户选择修复每个块：

`fsck -r {{/dev/sda}}`

- 检查文件系统 /dev/sda，报告任何损坏的块并自动修复它们：

`fsck -a {{/dev/sda}}`

[#]: contributors: ([潘潘]，[Jack])