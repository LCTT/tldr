# webtorrent

> Webtorrent 程序的命令行界面
> 支持 magnets, urls, info hashes and torrent 文件

- 下载一个 Torrent 文件：

`webtorrent download "{{torrent_id}}"`

- 将下载中的 Torrent 文件推流到 VLC  player 中播放：

`webtorrent download "{{torrent_id}}" --vlc`

- 将下载中的 Torrent 文件推流到DLNA设备中播放：

`webtorrent download "{{torrent_id}}" --dlna`

- 显示指定 Torrent 包含的文件列表：

`webtorrent download "{{torrent_id}}" --select`

- 指定要从 Torrent 下载的文件索引：

`webtorrent download "{{torrent_id}}" --select {{index}}`

- 种子指定的文件或目录：

`webtorrent seed {{path/to/file_or_directory}}`

- 为指定的文件路径创建新的 Torrent 文件：

`webtorrent create {{path/to/file}}`

- 显示磁力链接或 .torrent 文件的信息：

`webtorrent info {{path/to/file_or_magnet}}`

[#]: contributors: ([jim.大团结]，[玉叶]，[Mr. Ren])