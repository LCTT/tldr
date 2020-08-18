# fswebcam

> 类 unix 系统的轻便网络摄像工具

- 拍照：

`fswebcam {{filename}}`

- 指定分辨率大小拍照：

`fswebcam -r {{width}}x{{height}} {{filename}}`

- 指定设备进行拍照（默认设备为： /dev/video0）：

`fswebcam -d {{device}} {{filename}}`

- 拍照时附带时间戳（由 strftime 来格式时间戳）：

`fswebcam --timestamp {{timestamp}} {{filename}}`

[#]: contributors: ([李峰])