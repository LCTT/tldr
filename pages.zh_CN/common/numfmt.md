# numfmt

> 将数字与人类可读的字符串进行转换

- 将1.5K（SI单位）转换为1500：

`numfmt --from={{si}} {{1.5K}}`

- 将第 5 个字段（ 1 个索引）转换为 IEC 单位而不转换标题：

`ls -l | numfmt --header={{1}} --field={{5}} --to={{iec}}`

- 转换为 IEC 单位，填充 5 个字符，左对齐：

`du -s * | numfmt --to={{iec}} --format={{"%-5f"}}`

[#]: contributors: ([潘潘]，[Judie])