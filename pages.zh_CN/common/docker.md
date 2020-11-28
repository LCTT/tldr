# docker

> 管理 Docker 容器和镜像

- 列出当前正在运行的 docker 容器：

`docker ps`

- 列出所有 docker 容器 （包括正在运行的和已经停止的容器）：

`docker ps -a`

- 从一个镜像启动一个容器，并为此容器指定一个名称：

`docker run --name {{container_name}} {{image}}`

- 启动或停止一个已存在的容器：

`docker {{start|stop}} {{container_name}}`

- 从一个 docker registry 获取一个镜像：

`docker pull {{image}}`

- 在一个已经在运行的容器中打开一个 shell：

`docker exec -it {{container_name}} {{sh}}`

- 删除一个已经停止的容器：

`docker rm {{container_name}}`

- 获得一个容器的日志并在输出中实时更新：

`docker logs -f {{container_name}}`

[#]: contributors: ([HCL]，[程睿]，[DD])