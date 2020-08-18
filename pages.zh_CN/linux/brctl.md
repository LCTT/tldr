# brctl

> 以太网网桥管理

- 列出当前系统中已经存在的网桥的信息：

`sudo brctl show`

- 创建一个网桥接口，默认这个网桥上没有任何接口关联：

`sudo brctl add {{bridge_name}}`

- 删除当前系统中存在的网桥：

`sudo brctl del {{bridge_name}}`

- 将一个网络接口关联到当前已经存在的网桥：

`sudo brctl addif {{bridge_name}} {{interface_name}}`

- 将一个接口从一个已经存在的网桥删除：

`sudo brctl delif {{bridge_name}} {{interface_name}}`

[#]: contributors: ([王兴宇]，[Arno | xinest])