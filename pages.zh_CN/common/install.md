# install

> 复制文件并设置属性
> 将文件(通常是可执行的)复制到“/usr/local/bin”这样的系统位置，给它们适当的权限/所有权

- 将文件复制到目标：

`install {{path/to/source}} {{path/to/destination}}`

- 将文件复制到目标，设置它们的所有权：

`install -o {{user}} {{path/to/source}} {{path/to/destination}}`

- 将文件复制到目标，设置它们的组所有权：

`install -g {{user}} {{path/to/source}} {{path/to/destination}}`

- 将文件复制到目标，设置它们的“模式”：

`install -m {{+x}} {{path/to/source}} {{path/to/destination}}`

- 复制文件并将源文件的访问/修改时间应用于目标文件：

`install -p {{path/to/source}} {{path/to/destination}}`

[#]: contributors: ([仁人])