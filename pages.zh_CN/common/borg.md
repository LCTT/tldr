# borg

> 重复数据消除备份工具
> 创建可作为文件系统装载的本地或远程备份

- 初始化一个本地的存储库：

`borg init {{/path/to/repo_folder}}`

- 把文件夹备份到仓库中，创建一个叫  "Monday" 的归档：

`borg create --progress {{/path/to/repo_folder}}::{{Monday}} {{/path/to/source_folder}}`

- 列出存储库中的所有存档：

`borg list {{/path/to/repo_folder}}`

- 从远程存储库中的 "Monday" 存档中提取特定文件夹，不包括所有 *.ext 文件：

`borg extract {{user}}@{{host}}:{{/path/to/repo_folder}}::{{Monday}} {{path/to/target_folder}} --exclude '{{*.ext}}'`

- 通过删除超过 7 天的所有存档，列出更改来修剪存储库：

`borg prune --keep-within {{7d}} --list {{/path/to/repo_folder}}`

- 以 FUSE 文件系统装载一个存储库：

`borg mount {{/path/to/repo_folder}}::{{Monday}} {{/path/to/mountpoint}}`

- 显示有关创建存档的帮助：

`borg create --help`

[#]: contributors: ([琳小梁]，[潘潘]，[Mr. Ren]，[Judie]，[玉叶])