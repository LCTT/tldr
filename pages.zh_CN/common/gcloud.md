# gcloud

> Google Cloud 平台的官方 CLI 工具

- 列出一个活动配置中的所有属性：

`gcloud config list`

- 设置活动项目：

`gcloud config set project {{project_name}}`

- SSH 链接一个虚拟实例：

`gcloud compute ssh {{user}}@{{instance}} `

- 显示项目中的所有 Google Compute Engine 实例 默认情况下会列出所有区域的实例：

`gcloud compute instances list`

- 通过密钥认证将 kubectl 客户端连接到 K8S 集群：

`gcloud container clusters get-credentials {{cluster_name}}`

- 更新所有 gcloud CLI 组件：

`gcloud components update`

- 显示指定命令的帮助：

`gcloud help {{command}}`

[#]: contributors: ([Jangrui])