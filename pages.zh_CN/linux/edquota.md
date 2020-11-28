# edquota

> 编辑用户或组的配额默认情况下，它在所有具有配额的文件系统上运行
> 配额信息永久存储在文件系统根目录下的“quotauser”和“quotagroup”文件中

- 编辑当前用户的配额：

`edquota --user $(whoami)`

- 编辑特定用户的配额：

`sudo edquota --user {{username}}`

- 编辑组的配额：

`sudo edquota --group {{group}}`

- 将操作限制到给定的文件系统（默认情况下，edquota对具有配额的所有文件系统进行操作）：

`sudo edquota --file-system {{filesystem}}`

- 编辑默认宽限期：

`sudo edquota -t`

- 将配额复制到其他用户：

`sudo edquota -p {{reference_user}} {{destination_user1}} {{destination_user2}}`

[#]: contributors: ([潘潘]，[Judie])