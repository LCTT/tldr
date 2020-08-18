# hg clone

> 在新目录中创建现有存储库的副本

- 将存储库克隆到指定的目录：

`hg clone {{remote_repository_source}} {{destination_path}}`

- 将存储库克隆到特定分支的头部，忽略后面的提交：

`hg clone --branch {{branch}} {{remote_repository_source}}`

- 仅使用“.hg”克隆存储库：

`hg clone --noupdate {{remote_repository_source}}`

- 将存储库克隆到特定的修订、标记或分支，保留整个历史：

`hg clone --updaterev {{revision}} {{remote_repository_source}}`

- 将存储库克隆到特定的修订版本，而不使用任何新的历史记录：

`hg clone --rev {{revision}} {{remote_repository_source}}`

[#]: contributors: ([仁人])