# bup

> 基于 git packfile 格式的备份系统，提供快速增量保存和全局去除冗余

- 在指定的本地目录初始化一个备份仓库：

`bup -d {{path/to/repository}} init`

- 正式备份前对给定的文件夹进行准备：

`bup -d {{path/to/repository}} index {{path/to/folder}}`

- 将文件夹备份到存储库：

`bup -d {{path/to/repository}} save -n {{backup_name}} {{path/to/folder}}`

- 显示目前在仓库储存的备份快照：

`bup -d {{path/to/repository}} ls`

- 恢复指定的备份快照至一个目标目录下：

`bup -d {{path/to/repository}} restore -C {{path/to/target_directory}} {{backup_name}}`

[#]: contributors: ([潘潘]，[Datura stramonium L.]，[6 °分离]，[玉叶]，[holy4god])