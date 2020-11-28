# exiftool

> 读写文件的元信息

- 从给定文件中删除所有 EXIF 元数据：

`exiftool -All= {{file}}`

- 将目录中的照片拍摄时间增加 1 小时：

`exiftool "-AllDates+=0:0:0 1:0:0" {{directory}}`

- 只在 JPEG 上减少 1 天 2 小时的拍照时间：

`exiftool "-AllDates-=0:0:1 2:0:0" -ext jpg`

- 仅将 DateTimeOriginal 更改 -1.5 小时，不保留备份：

`exiftool -DateTimeOriginal-=1.5 -overwrite_original`

- 根据 DateTimeOriginal 递归重命名所有 jpeg：

`exiftool '-filename<DateTimeOriginal' -d %Y-%m-%d_%H-%M-%S%%lc.%%e {{directory}} -r -ext jpg`

[#]: contributors: ([Datura stramonium L.])