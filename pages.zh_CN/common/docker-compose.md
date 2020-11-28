# docker-compose

> 运行和管理多个 docker 容器应用

- 使用当前路径中的 `docker-compose.yml` 配置创建并启动全部容器：

`docker-compose up -d`

- 启动 `docker-compose.yml` 配置的所有容器，如有必要重新构建：

`docker-compose up --build`

- 根据参数中的 compose.yml 路径，启动其中配置的容器：

`docker-compose --file {{path/to/file}} up`

- 停止所有正在运行的容器（不影响非 docker-compose 管理的容器）：

`docker-compose stop`

- 停止并移除所有当前 docker-compose.yml 所管理容器及其配置的网络，镜像和挂载：

`docker-compose down`

- 追踪所有 compose 管理的容器的日志：

`docker-compose logs --follow`

[#]: contributors: ([琳小梁]，[Sellente_Wang]，[Yaphet K])