# phpcpd

> 一个 PHP 代码的复制和粘贴检测器

- 分析指定文件或目录的重复代码：

`phpcpd {{path/to/file_or_directory}}`

- 使用变量名模糊匹配来分析：

`phpcpd --fuzzy {{path/to/file_or_directory}}`

- 指定相同行的最小数目，默认5：

`phpcpd --min-lines {{number_of_lines}} {{path/to/file_or_directory}}`

- 指定相同标识的最小数目，默认5：

`phpcpd --min-tokens {{number_of_tokens}} {{path/to/file_or_directory}}`

- 分析时排除指定目录（必须相对与源文件）：

`phpcpd --exclude {{path/to/excluded_directory}} {{path/to/file_or_directory}}`

- 将结果输出为PHP-CPD的XML文件：

`phpcpd --log-pmd {{path/to/log_file}} {{path/to/file_or_directory}}`

[#]: contributors: ([阿涛]，[王兴宇，Linux & BC]，[玉叶])