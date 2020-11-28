# pv

> 监控通过管道的数据进程

- 打印文件内容并显示进度条：

`pv {{file}}`

- 测量管道间的数据流的速率和数量（`-s` 是可选的）：

`command1 | pv -s {{expected_amount_of_data_for_eta}} | command2`

- 过滤文件，查看进度和输出数据量：

`pv -cN in {{big_text_file}} | grep {{pattern}} | pv -cN out > {{filtered_file}}`

- 附加到已运行的进程并查看其文件读取进度：

`pv -d {{PID}}`

- 读取一个错误的文件，并像 `dd conv=sync,noerror` 一样跳过错误：

`pv -EE {{path/to/faulty_media}} > image.img`

- 读取指定数据量后停止读取，速率限制为1K/s：

`pv -L 1K -S {{maximum_file_size_to_be_read}}`

[#]: contributors: ([王興與]，[󠀀]，[王兴宇，Linux 中國])