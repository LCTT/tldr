# chmod

> 更改文件或目录的权限，权限组分为所属者（u）、所属组（g）、其他人（o）权限包括读（r）、写（w）、执行（x）

- 给文件/目录所属者增加执行权限：

`chmod u+x {{file}}`

- 给文件/目录所属者增加读和写权限：

`chmod u+rw {{file_or_directory}}`

- 移除文件/目录所属组的执行权限：

`chmod g-x {{file}}`

- 给所有人（包括其他成员）增加对文件/目录的读和执行权限：

`chmod a+rx {{file}}`

- 给文件/目录赋予其他人跟所属组相同的权限：

`chmod o=g {{file}}`

- 以递归方式修改权限，使目录所属组和其他人新增读权限，该目录下的包括子目录和文件都会被相同修改：

`chmod -R g+w,o+w {{directory}}`

[#]: contributors: ([David Ricardo Shen]，[大树.])