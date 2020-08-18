# flac

> 编码、解码和测试 FLAC 文件

- 将 wav 文件编码为 flac（这将在与 wav 文件相同的位置创建 flac 文件）：

`flac {{path/to/file.wav}}`

- 对一个 wav 文件 flac 编码, 并指定输出文件：

`flac -o {{path/to/output.flac}} {{path/to/file.wav}}`

- 对一个 flac 文件 wav 解码, 并指定输出文件：

`flac -d -o {{path/to/output.wav}} {{path/to/file.flac}}`

- 测试 flac 文件的编码正确性：

`flac -t {{path/to/file.flac}}`

[#]: contributors: ([jim.大团结]，[Judie])