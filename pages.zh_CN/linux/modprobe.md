# modprobe

> 从Linux核心里面参加或者移除一个模块

- 假装将模块加载到内核中，但实际上并没有这样做：

`sudo modprobe --dry-run {{module_name}}`

- 将模块加载到内核中：

`sudo modprobe {{module_name}}`

- 从内核中删除模块：

`sudo modprobe --remove {{module_name}}`

- 从内核中删除模块和依赖它的模块：

`sudo modprobe --remove-dependencies {{module_name}}`

- 显示一个核心模块的相依性：

`sudo modprobe --show-depends {{module_name}}`

[#]: contributors: ([潘潘]，[心飞扬])