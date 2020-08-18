# restic

> 快速、安全、高效的备份程序

- 在指定的目录初始化备份存储库：

`restic init -r {{path/to/repository}}`

- 在指定存储库里对 “my_folder” 进行备份：

`restic -r {{path/to/repository}} backup {{path/to/my_folder}}`

- 显示指定存储库现存的快照：

`restic -r {{path/to/repository}} snapshots`

- 根据指定备份快照对指定目录进行回复：

`restic -r {{path/to/repository}} restore {{snapshot_id}} {{path/to/target}}`

- 根据指定备份快照回复指定目录，保存到目标目录：

`restic -r {{path/to/repository}} --include {{path/to/restore}} --target {{path/to/target}} restore {{snapshot_id}}`

- 清理存储库，只保留每个备份里最近的快照：

`restic forget --keep-last 1 --prune`

[#]: contributors: ([李峰])