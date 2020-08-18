# datamash

> 用于对输入的文本数据文件执行基本的数字、文本和统计操作的工具

- 得到单列数字的最大值、最小值、平均值和中位数：

`seq 3 | datamash max 1 min 1 mean 1 median 1`

- 获取一列浮点数的平均值（浮点数必须使用 “ , ” 而不是 “ . ” ）：

`echo -e '1.0\n2.5\n3.1\n4.3\n5.6\n5.7' | tr '.' ',' | datamash mean 1`

- 求具有给定小数精度的单列数字的平均值：

`echo -e '1\n2\n3\n4\n5\n5' | datamash -R {{number_of_decimals_wanted}} mean 1`

- 获取忽略 “Na” 和 “NaN” （文字）字符串的单列数字的平均值：

`echo -e '1\n2\nNa\n3\nNaN' | datamash --narm mean 1`

[#]: contributors: ([Datura stramonium L.])