# dc

> 一个任意精度的计算器，使用逆波兰表达式（RPN）

- 以交互模式运行计算器：

`dc`

- 执行文件中的 dc 脚本：

`dc -f {{file}}`

- 计算 4 乘以 5 （4 5 *），减去 17（17 -），并使用 `echo` 打印（p）该输出：

`echo "4 5 * 17 - p"| dc`

- 将小数位数设置为 7 [7 k]，计算 5 除以 -3 [5 _3 /] ，并打印 [p] rint（使用 dc -e）：

`dc -e "7 k 5 _3 / p"`

- 计算黄金比例，phi：设置小数位数为100 [100 k]，平方根为5 [5 v]加1 [1 +]，除以2 [2 /]，并打印[p] rint 结果：

`dc -e "100 k 5 v 1 + 2 / p"`

[#]: contributors: ([琳小梁]，[潘潘]，[王兴宇，Linux & BC]，[玉叶])