# wasm-opt

> 优化 WebAssembly 二进制文件

- 应用默认优化并写入给定文件：

`wasm-opt -O {{input.wasm}} -o {{output.wasm}}`

- 应用所有优化并写入给定文件（花费更多时间，但生成最佳代码）：

`wasm-opt -O4 {{input.wasm}} -o {{output.wasm}}`

- 优化文件大小：

`wasm-opt -Oz {{input.wasm}} -o {{output.wasm}}`

- 将二进制文件的文本表示形式打印到控制台：

`wasm-opt {{input.wasm}} --print`

[#]: contributors: ([Datura stramonium L.])