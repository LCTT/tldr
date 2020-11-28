# findmnt

> 找到你的文件系统

- 列出所有挂载的文件系统：

`findmnt`

- 寻找设备：

`findmnt {{/dev/sdb1}}`

- 寻找挂载点：

`findmnt {{/}}`

- 寻找指定类型的文件系统：

`findmnt -t {{ext4}}`

- 寻找有特定标识的文件系统：

`findmnt LABEL={{BigStorage}}`

[#]: contributors: ([潘潘]，[大家都说名字太长了不容易被人记住])