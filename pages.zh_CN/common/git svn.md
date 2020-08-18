# git svn

> Subversion 存储库和 Git 之间的双向操作
> 主页： <https://git-scmcom/docs/git-svn>

- 克隆 SVN 存储库：

`git svn clone {{https://example.com/subversion_repo}} {{local_dir}}`

- 从给定的修订号开始克隆 SVN 存储库：

`git svn clone -r{{1234}}:HEAD {{https://svn.example.net/subversion/repo}} {{local_dir}}`

- 从远程 SVN 存储库更新本地克隆：

`git svn rebase`

- 从远程 SVN 存储库获取更新而不更改 git HEAD：

`git svn fetch`

- 回到 SVN 存储库：

`git svn dcommit`

[#]: contributors: ([潘潘]，[玉叶])