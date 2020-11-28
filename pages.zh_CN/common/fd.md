# fd

> 一个简单、快速和用户友好的“find”替代方案

- 在当前目录中查找与给定模式匹配的文件：

`fd {{pattern}}`

- 查找以“foo”开头的文件：

`fd {{'^foo'}}`

- 查找具有特定扩展名的文件：

`fd --extension {{txt}}`

- 在特定目录中查找文件：

`fd {{pattern}} {{path/to/dir}}`

- 在搜索中包含被忽略和隐藏的文件：

`fd --hidden --no-ignore {{pattern}}`

[#]: contributors: ([　]，[玉叶])