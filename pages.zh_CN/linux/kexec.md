# kexec

> 直接重新启动到新内核

- 加载新内核：

`kexec -l {{path/to/kernel}} --initrd={{path/to/initrd}} --command-line={{arguments}}`

- 使用当前引导参数加载新内核：

`kexec -l {{path/to/kernel}} --initrd={{path/to/initrd}} --reuse-cmdline`

- 提取当前加载的内核：

`kexec -e`

- 卸载当前的 kexec 目标内核：

`kexec -u`

[#]: contributors: ([Datura stramonium L.])