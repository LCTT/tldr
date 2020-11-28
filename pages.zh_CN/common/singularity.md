# singularity

> 管理 Singularity 容器和镜像

- 下载远程镜像：

`singularity pull --name {{container.simg}} {{shub://vsoch/hello-world}}`

- 使用最新的 Singularity 镜像格式重构远程镜像：

`singularity build {{container.simg}} {{docker://godlovedc/lolcow}}`

- 从一个镜像启动容器并从中获取一个 shell：

`singularity shell {{container.simg}}`

- 从镜像启动一个容器并运行其中的命令：

`singularity exec {{container.simg}} {{command}}`

- 从镜像启动一个容器并执行其内部运行脚本：

`singularity run {{container.simg}}`

- 从清单文件中构建一个 Singularity 镜像：

`sudo singularity build {{container.simg}} {{recipe}}`

[#]: contributors: ([王興與·區塊鏈·Linux中國])