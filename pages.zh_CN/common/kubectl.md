# kubectl

> 针对 Kubernetes 集群运行命令的命令行工具

- 查看所有命名空间下的所有 pod：

`kubectl get pods --all-namespaces`

- 列出所有 pod 的详细信息（如节点名）：

`kubectl get pods -o wide`

- 更新 pod 的“unhealthy（不健康）”标签为真值：

`kubectl label pods {{name}} unhealthy=true`

- 列出不同类型的所有资源：

`kubectl get all`

- 查看所有节点的资源状态：

`kubectl top node`

- 查看默认命名空间下所有 pod 的资源状态：

`kubectl top pod`

- 打印主控节点的地址和集群服务信息：

`kubectl cluster-info`

[#]: contributors: ([王兴宇，Linux & BC]，[∠( ᐛ 」∠)＿])