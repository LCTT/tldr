# entr

> 当文件改变时运行某个命令

- 当任意子目录中的任意文件改变时，使用 `make` 重新构建：

`{{ag -l}} | entr {{make}}`

- 当在当前目录中任意 `.c` 源文件改变，使用 `make` 重新构建并运行测试：

`{{ls *.c}} | entr {{'make && make test'}}`

- 在执行 `ruby main.rb` 之前，给之前孶生的任何 ruby 子进程发送一个 `SIGTERM`：

`{{ls *.rb}} | entr -r {{ruby main.rb}}`

- 以改变的文件（`/_`）作为参数运行一个命令：

`{{ls *.sql}} | entr {{psql -f}} /_`

[#]: contributors: ([王兴宇，Linux & BC])