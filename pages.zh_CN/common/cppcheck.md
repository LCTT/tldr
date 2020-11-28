# cppcheck

> 一个静态 C/C++ 代码分析工具
> 相较于语法错误，此工具更加着重于找寻编译器不能发现的漏洞类型

- 递归查询当前的文件夹，在屏幕上显示进度并且把错误信息记录到一个文件('cppcheck.log')中：

`cppcheck . 2> cppcheck.log`

- 递归检查一个给定的文件夹，并且不显示进度：

`cppcheck --quiet {{path/to/directory}}`

- 检查一个给定的文件，并指定执行哪种测试（默认情况下只显示错误）：

`cppcheck --enable={{error|warning|style|performance|portability|information|all}} {{path/to/file.cpp}}`

- 罗列出可用的测试，并经由给定的搜索模式进行筛选：

`cppcheck --errorlist | grep "{{search_pattern}}"`

- 检查给定的文件，并忽略特定的测试：

`cppcheck --suppress={{test_id1}} --suppress={{test_id2}} {{path/to/file.cpp}}`

- 检查当前的文件夹，并给位于其外部的 include 文件提供路径（例如外部库）：

`cppcheck -I {{include/directory_1}} -I {{include/directory_2}} .`

- 检查一个Microsoft Visual Studio 项目（`*.vcxproj`）或解决方案（`*.sln`）：

`cppcheck --project={{path/to/project.sln}}`

[#]: contributors: ([琳小梁]，[张益兴])