# join

> 在公共字段上加入两个已排序文件的行

- 在第一个（默认）字段上加入两个文件：

`join {{file1}} {{file2}}`

- 使用 file2 的 field1 加入 file1 的 field3 ：

`join -1 3 -2 1 {{file1}} {{file2}}`

- 为 file1 的每个不可操作的行生成一行：

`join -a 1 {{file1}} {{file2}}`

[#]: contributors: ([潘潘])