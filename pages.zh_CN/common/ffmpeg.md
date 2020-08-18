# ffmpeg

> 视频转换工具

- 从视频中提取声音并保存成 MP3 文件：

`ffmpeg -i {{video.mp4}} -vn {{sound}}.mp3`

- 将视频或 GIF 里的图帧转换为单独的，按排序命名的图片：

`ffmpeg -i {{video.mpg|video.gif}} {{frame_%d.png}}`

- 将排序命名的图片 (frame_1.jpg、frame_2.jpg ...) 合并为视频或 GIF：

`ffmpeg -i {{frame_%d.jpg}} -f image2 {{video.mpg|video.gif}}`

- 快速提取视频指定时刻的一帧图像并保存大小为128x128像素的图片：

`ffmpeg -ss {{mm:ss}} -i {{video.mp4}} -frames 1 -s {{128x128}} -f image2 {{image.png}}`

- 指定开始时间和结束时间来剪辑视频（缺省结束时间为视频结束时间）：

`ffmpeg -ss {{mm:ss}} -to {{mm2:ss2}} -i {{video.mp4}} -codec copy {{output.mp4}}`

- 将 AVI 视频转换为 MP4. AAC 声频 @ 128kbit，h264 视频 @ CRF 23：

`ffmpeg -i {{input_video}}.avi -codec:audio aac -b:audio 128k -codec:video libx264 -crf 23 {{output_video}}.mp4`

- Remux MKV 视频到 MP4，无需重新编码音频或视频流：

`ffmpeg -i {{input_video}}.mkv -codec copy {{output_video}}.mp4`

- 将 MP4 视频转换为 VP9 编解码器为获得最佳质量，使用 CRF 值（建议范围 15-35）和 -b：视频必须为 0 ：

`ffmpeg -i {{input_video}}.mp4 -codec:video libvpx-vp9 -crf {{30}} -b:video 0 -codec:audio libopus -vbr on -threads {{number_of_threads}} {{output_video}}.webm`

[#]: contributors: ([潘潘]，[李峰]，[蜂子🐝ℋ]，[Mr. Rat Ellipse])