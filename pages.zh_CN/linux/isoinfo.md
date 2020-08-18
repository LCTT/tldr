# isoinfo

> 用于转储或者校验 ISO 磁盘映像的实用程序

- 列出 ISO 映像中包含的所有文件：

`isoinfo -f -i {{path/to/image.iso}}`

- 从 ISO 镜像中提取特定文件并将其发送到标准输出 （STDOUT）：

`isoinfo -i {{path/to/image.iso}} -x {{/PATH/TO/FILE/INSIDE/ISO.EXT}}`

- 显示 ISO 磁盘映像的头信息：

`isoinfo -d -i {{path/to/image.iso}}`

[#]: contributors: ([王兴宇，Linux & BC]，[玉叶]，[jim.大团结]，[Datura stramonium L.])