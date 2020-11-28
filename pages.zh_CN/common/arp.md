# arp

> 显示并操作系统的 ARP 缓存

- 显示当前 arp 表：

`arp -a`

- 清除全部缓存：

`sudo arp -a -d`

- 删除指定条目：

`arp -d {{address}}`

- 创建一个条目：

`arp -s {{address}} {{mac_address}}`

[#]: contributors: ([王兴宇，Linux 中國]，[张益兴])