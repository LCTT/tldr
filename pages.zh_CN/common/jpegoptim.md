# jpegoptim

> 优化 JPEG 图片

- 无损优化一系列指定文件：

`jpegoptim {{image1.jpeg}} {{image2.jpeg}} {{imageN.jpeg}}`

- 优化 JPEG 图片，去除其中所有无关紧要的数据：

`jpegoptim --strip-all {{image1.jpeg}} {{image2.jpeg}} {{imageN.jpeg}}`

- 强制转换图片为渐进格式：

`jpegoptim --all-progressive {{image1.jpeg}} {{image2.jpeg}} {{imageN.jpeg}}`

- 限制输出文件大小不超过指定大小：

`jpegoptim --size={{250k}} {{image1.jpeg}} {{image2.jpeg}} {{imageN.jpeg}}`

[#]: contributors: ([李峰])