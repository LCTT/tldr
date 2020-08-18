# rpcinfo

> 对一个 RPC 服务器发起一个 RPC 调用，并报告结果

- 显示注册在本机的所有 RPC 服务的完整表格：

`rpcinfo`

- 显示注册在本机的所有 RPC 服务的简明表格：

`rpcinfo -s {{localhost}}`

- 显示 rpcbind 在本机操作的统计表格：

`rpcinfo -m`

- 显示一个远程的 NFS 共享上的给定的服务（mountd）和版本（2）的列表：

`rpcinfo -l {{remote_nfs_server_ip}} {{mountd}} {{2}}`

- 删除所有传输的版本 1 的 mountd 服务的注册项：

`rpcinfo -d {{mountd}} {{1}}`

[#]: contributors: ([王興與·區塊鏈·Linux中國])