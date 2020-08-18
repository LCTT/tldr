# pass

> 安全地存储和读取密码或其他敏感数据
> 所有的数据都是用 GPG 加密的，并且使用一个 git 存储库进行管理

- 使用一个 gpg-id 来初始化加密存储：

`pass init {{gpg_id}}`

- 保存一个新密码（如果没有指定密码会提示输入）：

`pass insert {{path/to/data}}`

- 将密码（数据文件的第一行）复制到剪贴板：

`pass -c {{path/to/data}}`

- 列出整个存储树：

`pass`

- 生成具有给定长度的新随机密码，并将其复制到剪贴板：

`pass generate -c {{path/to/data}} {{num}}`

- 对底层存储库运行某个 git 命令：

`pass git {{git_arguments}}`

[#]: contributors: ([王兴宇，Linux 中國]，[张益兴])