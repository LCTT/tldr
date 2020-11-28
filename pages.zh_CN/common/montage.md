# montage

> Imagemagick 图像蒙太奇工具
> 将图像平铺到可自定义的网格中

- 将图像平铺到网格中，自动调整大于网格单元大小的图像：

`montage {{image1.png}} {{image2.jpg}} {{imageN.png}} montage.jpg`

- 将图像平铺到网格中，从最大图像自动计算网格单元大小：

`montage {{image1.png}} {{image2.jpg}} {{imageN.png}} -geometry +0+0 montage.jpg`

- 在平铺之前设置网格单元大小并调整图像大小以适应它：

`montage {{image1.png}} {{image2.jpg}} {{imageN.png}} -geometry 640x480+0+0 montage.jpg`

- 限制网格中的行数和列数，导致输入图像溢出到多个输出剪辑中：

`montage {{image1.png}} {{image2.jpg}} {{imageN.png}} -geometry +0+0 -tile 2x3 montage_%d.jpg`

- 在平铺之前调整大小并裁剪图像以完全填充其网格单元格：

`montage {{image1.png}} {{image2.jpg}} {{imageN.png}} -geometry +0+0 -resize 640x480^ -gravity center -crop 640x480+0+0 montage.jpg`

[#]: contributors: ([潘潘])