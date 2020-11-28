# kompose

> 将 docker-compose 应用程序转换为 Kubernetes 的工具

- 将 dockerized 应用程序部署到 Kubernetes：

`kompose up -f {{docker-compose.yml}}`

- 从 Kubernetes 中删除实例化的服务 / 环境：

`kompose down -f {{docker-compose.yml}}`

- 将 docker-compose 文件转换为 Kubernetes 资源文件：

`kompose convert -f {{docker-compose.yml}}`

[#]: contributors: ([Datura stramonium L.])