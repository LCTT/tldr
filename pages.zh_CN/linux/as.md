# as

> GNU 汇编器
> 主要用于组装 `gcc` 的输出，供 `ld` 使用

- 汇编一个文件，将输出写入 a.out：

`as {{file.s}}`

- 汇编指定源文件：

`as {{file.s}} -o {{out.o}}`

- 通过跳过空白和注释预处理更快地生成输出（应仅用于受信任的编译器）：

`as -f {{file.s}}`

- 将一个指定路径包括到目录列表当中，用于搜索在 .include 指令中指定的文件：

`as -I {{path/to/directory}} {{file.s}}`

[#]: contributors: ([王兴宇，Linux 中國]，[Datura stramonium L.])