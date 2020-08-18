# git format-patch

> 准备 patch 文件通过电子邮件发送其他地方的提交
> 另请参阅 git am ，它可以应用生成的 patch 文件
> 主页： <https://git-scmcom/docs/git-format-patch>

- 为所有未删除的提交创建一个自动命名的 .patch文件：

`git format-patch {{origin}}`

- 为 stdout 的 2 个修订版之间的所有提交写一个 .patch 文件：

`git format-patch {{revision_1}}..{{revision_2}}`

- 为最后的 3 个提交生成一个 .patch 文件：

`git format-patch -{{3}}`

[#]: contributors: ([潘潘]，[庄秋彬]，[玉叶])