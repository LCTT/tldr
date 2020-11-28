# espeak

> 将文本转为语音通过默认音频设备播放

- 朗读出一句话：

`espeak "I like to ride my bike."`

- 朗读出文件内容：

`espeak -f {{filename}}`

- 将转化的语音保存为 audio 文件，而不读出来：

`espeak -w {{filename.wav}} "It's GNU plus Linux"`

- 换一种嗓音：

`espeak -v {{voice}}`

[#]: contributors: ([王兴宇，Linux & BC]，[李峰])