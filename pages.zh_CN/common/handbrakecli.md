# handbrakecli

> HandBrake 视频转换工具的命令行界面

- 将视频文件转换为 MKV (AAC 160kbit 音频 和 x264 CRF20 视频)：

`handbrakecli -i {{input.avi}} -o {{output.mkv}} -e x264 -q 20 -B 160`

- 调整视频文件尺寸为 320x240：

`handbrakecli -i {{input.mp4}} -o {{output.mp4} -w 320 -l 240`

- 列出可用预设：

`handbrakecli --preset-list`

- 使用 Android 预设将 AVI 视频转换为 MP4：

`handbrakecli --preset="Android" -i {{input.ext}} -o {{output.mp4}}`

[#]: contributors: ([玉堂白鹤])