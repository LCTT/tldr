# stat

> 显示文件和文件系统信息

- 显示文件属性，如文件大小、权限、创建及访问时间等：

`stat {{file}}`

- 同上，但以更整齐的格式显示：

`stat -t {{file}}`

- 显示文件所在文件系统的信息：

`stat -f {{file}}`

- 仅显示八进制格式的文件权限：

`stat -c "%a %n" {{file}}`

- 显示文件的所属用户及所属用户组：

`stat -c "%U %G" {{file}}`

- 用字节为单位显示文件的大小：

`stat -c "%s %n" {{file}}`

[#]: contributors: ([叫我阿文]，[王兴宇，Linux & BC]，[唐老鸭]，[Shawn]，[小白]，[Z.J]，[王兴宇，Linux 中國])