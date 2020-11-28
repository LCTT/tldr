# xxd

> 把二进制文件转换成十六进制表示（hexdump），或反之

- 将二进制文件转成十六进制并显示输出：

`xxd {{input_file}}`

- 将二进制文件转换为十六进制并将其保存为文本文件：

`xxd {{input_file}} {{output_file}}`

- 显示 10 列的输出，每列一个八位元（字节）：

`xxd -c {{10}} {{input_file}}`

- 仅显示长度不超过 32 字节的输出：

`xxd -l {{32}} {{input_file}}`

- 以纯模式显示输出，列之间没有任何间隙：

`xxd -p {{input_file}}`

- 将明文十六进制恢复为二进制，并将其保存为二进制文件：

`xxd -r -p {{input_file}} {{output_file}}`

[#]: contributors: ([王兴宇]，[Datura stramonium L.])