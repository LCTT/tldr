# vagrant

> 管理轻量级的，可复现的及可移植的开发环境

- 在当前文件夹中创建一个使用基本 Vagrant box的 Vagrantfile 配置文件：

`vagrant init`

- 使用 HashiCorp Atlas 的 Ubuntu 14.04（Trusty Tahr）框创建 Vagrantfile ：

`vagrant init ubuntu/trusty32`

- 启动并配置 vagrant 环境：

`vagrant up`

- 挂起该虚拟机：

`vagrant suspend`

- 通过 SSH 连接到该虚拟机：

`vagrant ssh`

[#]: contributors: ([潘潘]，[无人喝彩])