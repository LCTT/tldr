# eyeD3

> 读取和操作 MP3 文件的元数据
> 主页：<https://eyed3readthedocsio/en/latest/>

- 查看有关 MP3 文件的信息：

`eyeD3 {{filename.mp3}}`

- 设置 MP3 文件的标题：

`eyeD3 --title {{"A Title"}} {{filename.mp3}}`

- 设置目录中的所有 MP3 文件的唱片名：

`eyeD3 --album {{"Album Name"}} {{*.mp3}}`

- 为一个 MP3 文件设置封面：

`eyeD3 --add-image {{front_cover.jpeg}}:FRONT_COVER: {{filename.mp3}}`

[#]: contributors: ([王兴宇，Linux & BC]，[玉堂白鹤]，[󠀀])