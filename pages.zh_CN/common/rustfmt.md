# rustfmt

> “Rust” 代码格式化工具

- 格式化一个文件，并覆盖原文件：

`rustfmt {{source.rs}}`

- 显示出格式化一个文件所产生的任何变更：

`rustfmt --check {{source.rs}}`

- 在格式化代码前备份代码文件（原始文件将会被重命名为 .bk 后缀的文件）：

`rustfmt --backup {{source.rs}}`

[#]: contributors: ([Mr. Ren])