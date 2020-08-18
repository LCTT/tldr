# sox

> 声音文件格式转换: 播放，记录和转换音频文件
> 可通过扩展辨别音频格式

- 将两个音频文件合并成一个：

`sox -m {{input_audiofile1}} {{input_audiofile2}} {{output_audiofile}}`

- 按照指定时间长度来剪切一个音频文件：

`sox {{input_audiofile}} {{output_audiofile}} trim {{start}} {{end}}`

- 标准化音频文件(将音量调整到最大峰值级别，不进行剪辑)：

`sox --norm {{input_audiofile}} {{output_audiofile}}`

- 反转并保存音频文件：

`sox {{input_audiofile}} {{output_audiofile}} reverse`

- 输出音频文件的统计数据：

`sox {{input_audiofile}} -n stat`

- 将音频文件的音量增加2倍：

`sox -v 2.0 {{input_audiofile}} {{output_audiofile}}`

[#]: contributors: ([香行子])