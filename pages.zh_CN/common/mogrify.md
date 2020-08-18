# mogrify

> 对多个图像执行操作，例如调整大小，裁剪，翻转和添加效果
> 更改将直接应用于原始文件

- 将文件夹中的所有 JPEG 图像调整为其初始大小的 50％：

`mogrify -resize {{50%}} {{*.jpg}}`

- 将所有以 DSC 开头的图像调整为 800x600 ：

`mogrify -resize {{800x600}} {{DSC*}}`

- 将文件夹中的所有 PNG 图像转换为 JPEG ：

`mogrify -format {{jpg}} {{*.png}}`

- 将当前目录中所有图像文件的饱和度减半：

`mogrify -modulate {{100,50}} {{*}}`

- 使当前目录中所有图像文件的亮度加倍：

`mogrify -modulate {{200}} {{*}}`

[#]: contributors: ([潘潘])