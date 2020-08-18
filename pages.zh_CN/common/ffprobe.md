# ffprobe

> 多媒体流分析工具

- 显示媒体文件的所有可用流（stream）信息：

`ffprobe -v error -show_entries {{input.mp4}}`

- 显示媒体文件的时间：

`ffprobe -v error -show_entries format=duration -of default=noprint_wrappers=1:nokey=1 {{input.mp4}}`

- 显示视频的帧速率：

`ffprobe -v error -select_streams v:0 -show_entries stream=avg_frame_rate -of default=noprint_wrappers=1:nokey=1 {{input.mp4}}`

- 显示视频的宽度或高度：

`ffprobe -v error -select_streams v:0 -show_entries stream={{width|height}} -of default=noprint_wrappers=1:nokey=1 {{input.mp4}}`

- 显示视频的平均比特率：

`ffprobe -v error -select_streams v:0 -show_entries stream=bit_rate -of default=noprint_wrappers=1:nokey=1 {{input.mp4}}`

[#]: contributors: ([Datura stramonium L.])