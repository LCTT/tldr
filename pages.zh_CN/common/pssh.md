# pssh

> 并行 SSH 程序

- 在两个列出的服务器，host1, host2 上运行命令 hostname 并显示结果：

`pssh -i -H "{{host1}} {{host2}}" {{hostname -i}}`

- 同第 1 条命令，但是将结果存入文件 path/to/output_dir 中：

`pssh -H {{host1}} -H {{host2}} -o {{path/to/output_dir}} {{hostname -i}}`

- 根据清单文件 path/to/hosts_file 中所列的服务器（每行一个服务器名），运行 hostname -i 的命令：

`pssh -i -h {{path/to/hosts_file}} {{hostname -i}}`

- 用root用户运行此命令（需要输入root密码）：

`pssh -i -h {{path/to/hosts_file}} -A -l {{root_username}} {{hostname -i}}`

- 同第 3 条命令，不过用选项 -x 引入 SSH 的选项，这里是 VisualHostKey=yes ：

`pssh -i -h {{path/to/hosts_file}} -x "{{-O VisualHostKey=yes}}" {{hostname -i}}`

- 按照 path/to/hosts_file 中的服务器清单运行命令，并限制同时连结数不超过10：

`pssh -i -h {{path/to/hosts_file}} -p {{10}} '{{cd dir; ./script.sh; exit}}'`

[#]: contributors: ([潘潘]，[姜太公钓鱼])