# rename

> 重命名多个文件

- 使用 Perl 兼容正则表达式来重命名文件（用 “bar” 替换任何发现的 “foo”）：

`rename {{'s/foo/bar/'}} {{\*}}`

- 在不执行重命名的情况下，显示即将发生的重命名：

`rename -n {{'s/foo/bar/'}} {{\*}}`

- rename -f {{'s/foo/bar/'}} {{\*}}：

`rename -f {{'s/foo/bar/'}} {{\*}}`

- 将文件名转为小写（在大小写不敏感的文件系统中，使用 `-f` 选项来避免出现 "already exists" 错误）：

`rename 'y/A-Z/a-z/' {{\*}}`

- 用下划线替换空格：

`rename 's/\s+/_/g' {{\*}}`

[#]: contributors: ([Jack_YT.]，[vimtoy]，[陈森]，[Datura stramonium L.]，[王兴宇，Linux 中國])