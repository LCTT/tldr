# convert

> Imagemagick 图片转换工具

- 将图片从 JPG 转换成 PNG：

`convert {{image.jpg}} {{image.png}}`

- 将图片尺寸缩小为原始的 50%：

`convert {{image.png}} -resize 50% {{image2.png}}`

- 在保持图片原始宽高比的情况下放大到 640x480：

`convert {{image.png}} -resize 640x480 {{image2.png}}`

- 横向拼接图片：

`convert {{image1.png}} {{image2.png}} {{image3.png}} +append {{image123.png}}`

- 通过一系列图片创建 gif ，相互间隔 100ms：

`convert {{image1.png}} {{image2.png}} {{image3.png}} -delay {{100}} {{animation.gif}}`

[#]: contributors: ([琳小梁]，[李峰]，[Mr. Rat Ellipse])