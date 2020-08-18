# wasm-objdump

> 显示 WebAssembly 二进制文件的信息

- 显示给定二进制文件的头信息：

`wasm-objdump -h {{file.wasm}}`

- 反汇编给定二进制文件并输出结果：

`wasm-objdump -d {{file.wasm}}`

- 显示每个节（section）的详细信息：

`wasm-objdump --details {{file.wasm}}`

- 显示指定节（section）的详细信息：

`wasm-objdump --section '{{import}}' --details {{file.wasm}}`

[#]: contributors: ([Datura stramonium L.])