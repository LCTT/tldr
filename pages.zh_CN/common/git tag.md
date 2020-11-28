# git tag

> 创建、展示、删除或校验标签
> 标签是对特定提交的静态引用
> 主页地址: <https://git-scmcom/docs/git-tag>

- 展示所有标签：

`git tag`

- 以指定名称创建一个指向当前提交的标签：

`git tag {{tag_name}}`

- 以指定名称创建一个指向指定提交的标签：

`git tag {{tag_name}} {{commit}}`

- 创建标签并添加注释：

`git tag {{tag_name}} -m {{tag_message}}`

- 按名称删除指定标签：

`git tag -d {{tag_name}}`

- 拉取上游标签更新：

`git fetch --tags`

- 列出发源于指定提交的所有标签：

`git tag --contains {{commit}}`

[#]: contributors: ([李峰])