# perl

> Perl 5 语言解释器

- 解释执行一个 Perl 脚本：

`perl {{script.pl}}`

- 对一个脚本进行语法检查：

`perl -c {{script.pl}}`

- 解释执行一条 perl 语句：

`perl -e {{perl_statement}}`

- 用 perldebug 命令，在调试模式下运行一个Perl脚本：

`perl -d {{script.pl}}`

- 遍历一个文件的所有行，并使用查找/替换表达式直接修改该文件：

`perl -p -i -e 's/{{find}}/{{replace}}/g' {{filename}}`

- 在文件上运行一个查找/替换表达式，并将原文件以指定的扩展名保存：

`perl -p -i'.old' -e 's/{{find}}/{{replace}}/g' {{filename}}`

- 在一个文件上运行一个多行的查找/替换表达式，并将结果保存在新的文件中：

`perl -p0e 's/{{foo\nbar}}/{{foobar}}/g' {{input_file}} > {{output_file}}`

[#]: contributors: ([好名字可以让你的朋友更容易记住你]，[jim.大团结]，[王兴宇])