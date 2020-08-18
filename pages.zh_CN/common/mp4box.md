# mp4box

> MPEG-4 系统工具盒：混流到 MP4 容器中

- 显示一个 MP4 文件的信息：

`mp4box -info {{filename}}`

- 添加 SRT 字幕到一个 MP4 文件：

`mp4box -add {{input_subs.srt}}:lang=eng -add {{input.mp4}} {{output.mp4}}`

- 合并一个文件的音频和另一个文件的视频到一个 MP4 文件：

`mp4box -add {{input1.mp4}}#audio -add {{input2.mp4}}#video {{output.mp4}`

[#]: contributors: ([王兴宇，Linux & BC]，[玉叶]，[jim.大团结])