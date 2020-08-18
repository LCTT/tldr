# cppclean

> 在 C++ 项目中查找未使用的代码

- 在一个工程的目录中运行：

`cppclean {{path/to/project}}`

- 在标题位于“inc1/”和“inc2/”文件夹中的项目上运行：

`cppclean {{path/to/project}} --include-path={{inc1}} --include-path={{inc2}}`

- 针对指定文件“main.cpp”运行：

`cppclean {{main.cpp}}`

- 在当前目录上运行，不包括 build 目录：

`cppclean {{.}} --exclude={{build}}`

[#]: contributors: ([琳小梁]，[潘潘]，[王兴宇，Linux & BC]，[6 °分离]，[好名字可以让你的朋友更容易记住你])