# minikube

> 在本地运行 Kubernetes 的工具

- 启动集群：

`minikube start`

- 获取集群的 IP 地址：

`minikube ip`

- 访问通过节点端口公开的名为 my_service 的服务并获取 URL ：

`minikube service {{my_service}} --url`

- 在浏览器中打开 kubernetes 面板中心：

`minikube dashboard`

[#]: contributors: ([潘潘]，[王兴宇，Linux & BC]，[Mr. Ren])