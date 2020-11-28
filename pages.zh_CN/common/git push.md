# git push

> 将更新推送到远端仓库
> 主页地址: <https://git-scmcom/docs/git-push>

- 将本地当前分支的更新推送到远端对应分支：

`git push`

- 将本地指定分支的更新推送到远端对应分支：

`git push {{remote_name}} {{local_branch}}`

- 将当前分支推送到远端，设置其在远端的分支名：

`git push {{remote_name}} -u {{remote_branch}}`

- 将本地所有分支的更新推送到指定远端的对应分支：

`git push --all {{remote_name}}`

- 删除指定远端的指定分支：

`git push {{remote_name}} --delete {{remote_branch}}`

- 删除没有本地对应项的远程分支：

`git push --prune {{remote_name}}`

- 推送新的标签到远端仓库：

`git push --tags`

[#]: contributors: ([潘潘]，[李峰]，[ntnyq])