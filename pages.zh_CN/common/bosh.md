# bosh

> 用于部署和管理 bosh 控制器的命令行工具

- 为 bosh 调度器创建本地别名：

`bosh alias-env {{environment_name}} -e {{ip_address|url}} --ca-cert {{ca_certificate}}`

- 列出环境：

`bosh environments`

- 登录到 bosh 调度器：

`bosh login -e {{environment}} `

- 列出部署：

`bosh -e {{environment}} deployments`

- 列出环境虚拟机：

`bosh -e {{environment}} vms -d {{deployment}}`

- ssh 进入虚拟机：

`bosh -e {{environment}} ssh {{virtual_machine}} -d {{deployment}}`

- 上传 bosh 干细胞：

`bosh -e {{environment}} upload-stemcell {{stemcell_file|url}}`

- 显示当前云端配置：

`bosh -e {{environment}} cloud-config`

[#]: contributors: ([琳小梁]，[玉叶])