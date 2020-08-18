# hg commit

> 将所有已暂存或指定的文件提交到存储库

- 将暂存文件提交到存储库：

`hg commit`

- 提交特定文件或目录：

`hg commit {{path/to/file_or_directory}}`

- 提交特定消息：

`hg commit --message {{message}}`

- 提交与指定模式匹配的所有文件：

`hg commit --include {{pattern}}`

- 提交所有文件，不包括与指定模式匹配的文件：

`hg commit --exclude {{pattern}}`

- 使用交互模式提交：

`hg commit --interactive`

[#]: contributors: ([潘潘])