# lshw

> 以 root 用户列出有关硬件配置的详细信息

- 启动 GUI ：

`sudo lshw -X`

- 以表格格式列出所有硬件：

`sudo lshw -short`

- 以表格格式列出所有磁盘和存储控制器：

`sudo lshw -class disk -class storage -short`

- 将所有网络接口保存到 HTML 文件：

`sudo lshw -class network -html > {{interfaces.html}}`

[#]: contributors: ([潘潘])