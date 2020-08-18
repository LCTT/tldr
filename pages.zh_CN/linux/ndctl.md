# ndctl

> 用于管理非易失性 DIMM 的实用程序

- 创建'fsdax'模块命名空间：

`ndctl create-namespace --mode={{fsdax}}`

- 把命名空间模块名修改为 'raw'：

`ndctl create-namespace --reconfigure={{namespaceX.Y}} --mode={{raw}}`

- 检查扇区模式命名空间的一致性，并根据需要进行修复：

`ndctl check-namespace --repair {{namespaceX.Y}}`

- 列出所有命名空间、区域和总线（包括禁用的命名空间、区域和总线）：

`ndctl list --namespaces --regions --buses --idle`

- 列出一个名称空间并包含附加信息：

`ndctl list -vvv --namespace={{namespaceX.Y}}`

- 运行监视器以监视“ACPI.NFIT”总线上nvdimm的运行状况：

`ndctl monitor --bus={{ACPI.NFIT}}`

- 移除命名空间（如果适用）或将其重置为初始状态：

`ndctl destroy-namespace --force {{namespaceX.Y}}`

[#]: contributors: ([~_~小白（）]，[runningwater]，[蔚然]，[Judie])