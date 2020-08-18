# git mv

> 移动或重命名文件并更新git索引
> 主页: <https://git-scmcom/docs/git-mv>

- 在repo中移动文件并将移动添加到下一个提交：

`git mv {{path/to/file}} {{new/path/to/file}}`

- 重命名文件并将重命名添加到下一个提交：

`git mv {{filename}} {{new_filename}}`

- 覆盖目标路径中的文件（如果存在）：

`git mv --force {{file}} {{target}}`

[#]: contributors: ([颉])