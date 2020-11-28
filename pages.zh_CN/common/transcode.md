# transcode

> 提供视频及音频文件的转码功能，并可以在不同多媒体格式之间进行转换

- 创建一个可以消除镜头抖动的稳定配置文件：

`transcode -J stabilize -i {{input_file}}`

- 使用稳定配置文件消除镜头抖动，并使用XviD编码器输出视频文件：

`transcode -J transform -i {{input_file}} -y xvid -o {{output_file}}`

- 将一个视频文件的分辨率转换为640x480并使用XviD编码器输出为MPEG4编码的视频文件：

`transcode -Z 640x480 -i {{input_file}} -y xvid -o {{output_file}}`

[#]: contributors: ([好名字可以让你的朋友更容易记住你])