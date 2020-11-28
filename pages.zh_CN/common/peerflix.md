# peerflix

> 串流视频或者音频种子到一个媒体播放器

- 串流种子中最大的媒体文件：

`peerflix "{{torrent_url|magnet_link}}"`

- 列出种子（以磁力链接给出）中所有可串流的文件：

`peerflix "{{magnet:?xt=urn:btih:0123456789abcdef0123456789abcdef01234567}}" --list`

- 串流以 URL 给出的种子中最大的文件到 VLC 播放器：

`peerflix "{{http://example.net/music.torrent}}" --vlc`

- 串流种子文件中最大的文件到 MPlayer，并显示字幕：

`peerflix "{{torrent_url|magnet_link}}" --mplayer --subtitles {{subtitle-file.srt}}`

- 串流一个种子文件里的所有文件到 Airplay：

`peerflix "{{torrent_url|magnet_link}}" --all --airplay`

[#]: contributors: ([王興與·區塊鏈·Linux中國]，[XXX]，[Mr. Ren])