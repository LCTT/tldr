# youtube-dl

> 从 YouTube 和其他网站下载视频的工具
> 主页：<http://rg3githubio/youtube-dl/> 

- 下载一个视频或者播放列表：

`youtube-dl {{https://www.youtube.com/watch?v=oHg5SJYRHA0}}`

- 下载视频中的音频并转换为 MP3 格式：

`youtube-dl -x --audio-format {{mp3}} {{url}}`

- 以自定义的名称将下载的视频保存为 MP4 格式：

`youtube-dl --format {{mp4}} -o {{"%(title)s by %(uploader)s on %(upload_date)s in %(playlist)s.%(ext)s"}} {{url}}`

- 下载一个视频，并保存其描述、元数据、注释、子标题和缩略图：

`youtube-dl --write-description --write-info-json --write-annotations --write-sub --write-thumbnail {{url}}`

- 从一个播放列表，下载所有未被标注“NSFW”或年龄限制在 7 岁的“Let's Play”视频：

`youtube-dl --match-title {{"let's play"}} --age-limit {{7}} --reject-title {{"nsfw"}} {{playlist_url}}`

[#]: contributors: ([Namhaid]，[王兴宇，Linux & BC]，[东先生]，[Mr. Ren])