# cpio

> 把文件复制进或复制出压缩包
> 支持以下存档格式：cpio 的自定义二进制文件、旧 ascii、新 ascii、crc、HPUX 二进制文件、HPUX 旧 ascii、旧 tar 和 POSIX1 tar

- 从标准输入中获取文件名列表，并将其以  cpio 二进制格式添加到存档中：

`echo "{{file1}} {{file2}} {{file3}}" | cpio -o > {{archive.cpio}}`

- 复制目录中的所有文件和目录，并以 [v]erbose 模式将它们添加( [o]nto )到存档中：

`find {{path/to/directory}} | cpio -ov > {{archive.cpio}}`

- 检查（P[i]ck ）存档中的所有文件，在需要时以 [v]erbose 模式生成目录（ [d]irectories ）：

`cpio -idv < {{archive.cpio}}`

[#]: contributors: ([琳小梁]，[Datura stramonium L.])