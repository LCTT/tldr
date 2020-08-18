# ufraw-batch

> 将照像机中的RAW格式的文件转换为标准图片文件

- 简便地将 RAW 格式的文件转换为 jpg 格式的文件：

`ufraw-batch --out-type=jpg {{input_file(s)}}`

- 简便地将 RAW 格式的文件转换为 png 格式的文件：

`ufraw-batch --out-type=png {{input_file(s)}}`

- 从原文件中提取预览的图片：

`ufraw-batch --embedded-image {{input_file(s)}}`

- 保存文件大小不超过给定最大数值 MAX1 和 MAX2 的文件：

`ufraw-batch --size=MAX1,MAX2 {{input_file(s)}}`

[#]: contributors: ([清上石])