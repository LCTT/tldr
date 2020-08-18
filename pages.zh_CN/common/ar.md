# ar

> 创建、修改或提取存档文件（a、so、o）

- 提取存档所有成员：

`ar -x {{libfoo.a}}`

- 列出存档的成员：

`ar -t {{libfoo.a}}`

- 替换或添加文件到存档：

`ar -r {{libfoo.a}} {{foo.o}} {{bar.o}} {{baz.o}}`

- 插入对象文件索引（相当于使用 `ranlib` ）：

`ar -s {{libfoo.a}}`

- 使用文件和附带的对象文件索引创建存档：

`ar -rs {{libfoo.a}} {{foo.o}} {{bar.o}} {{baz.o}}`

[#]: contributors: ([琳小梁]，[󠀀]，[Datura stramonium L.])