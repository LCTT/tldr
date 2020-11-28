# salt-key

> 管理 salt 主控上的下级密钥
> 需要在 salt 主控运行 salt ，类似于 root 或 sudo

- 显示所有已接受、未接受和拒绝的下级密钥：

`salt-key -L`

- 接受某个下级密钥：

`salt-key -a {{MINION_ID}}`

- 拒绝某个下级密钥：

`salt-key -r {{MINION_ID}}`

- 打印所有公钥的指纹：

`salt-key -F`

[#]: contributors: ([硬核老王（📺Linux中国）]，[Datura stramonium L.])