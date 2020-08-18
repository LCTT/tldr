# kubeadm

> 建立和管理 kubernetes 集群的命令行界面

- 建立一个 Kubernetes 主节点：

`kubeadm init`

- 引导 kubernetes 工作节点并将其加入集群：

`kubeadm join --token {{token}}`

- 创建一个12小时有效期的新引导token：

`kubeadm token create --ttl {{12h0m0s}}`

- 检查 Kubernetes 集群是否可以升级以及可升级到哪些版本：

`kubeadm upgrade plan`

- 将 Kubernetes 集群升级到指定的版本：

`kubeadm upgrade apply {{version}}`

- 查看包含集群配置的 kubeadm configmap：

`kubeadm config view`

- 撤销 `kubeadm init` 或 `kubeadm join` 提供的设置：

`kubeadm reset`

[#]: contributors: ([Rooot]，[阿涛]，[王兴宇，Linux & BC]，[玉叶]，[好名字可以让你的朋友更容易记住你]，[Mr. Ren])