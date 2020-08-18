# git clone

> 克隆已存在的仓库
> 主页：<https://git-scmcom/docs/git-clone>

- 克隆一个已存在仓库：

`git clone {{remote_repository_location}}`

- 克隆现有存储库及其子模块：

`git clone --recursive {{remote_repository_location}}`

- 从本地机器克隆：

`git clone -l`

- 静默克隆：

`git clone -q`

- 克隆现有的存储库，并将其截断到指定的修订数，这样可以节省大量的时间：

`git clone --depth {{10}} {{remote_repository_location}}`

[#]: contributors: ([ZH]，[CL]，[Justice])