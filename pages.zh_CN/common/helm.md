# helm

> K8s 包管理命令

- 创建一个 Chart：

`helm create {{chart_name}}`

- 添加一个新的 helm 仓库：

`helm repo add {{repo_name}}`

- 列举 helm 仓库：

`helm repo list`

- 更新 helm 仓库：

`helm repo update`

- 删除一个 helm 仓库：

`helm repo remove {{repo_name}}`

- 安装 helm 图：

`helm install {{repo_name}}/{{chart_name}}`

- 将 helm 图下载为 tar 存档：

`helm get {{chart_release_name}}`

- 更新 helm 依赖：

`helm dependency update`

[#]: contributors: ([潘潘]，[Destiny]，[梦还在继续])