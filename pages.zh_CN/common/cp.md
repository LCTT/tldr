# cp

> 复制文件或文件夹

- 将文件复制到另一个位置：

`cp {{path/to/file.ext}} {{path/to/copy.ext}}`

- 复制文件到另一个文件夹下并保持文件名：

`cp {{path/to/file.ext}} {{path/to/target_parent_folder}}`

- 将文件夹递归复制到指定位置：

`cp -r {{path/to/folder}} {{path/to/copy}}`

- 将文件夹用递归详细复制（在屏幕显示文件拷贝情况）：

`cp -vr {{path/to/folder}} {{path/to/copy}}`

- 复制文件夹的内容至另一个文件夹下：

`cp -r {{path/to/source_folder/*}} {{path/to/target_folder}}`

- 拷贝文本文件到别处，用交互模式（在覆盖前提示用户）：

`cp -i {{*.txt}} {{path/to/target_folder}}`

[#]: contributors: ([秦时明月]，[琳小梁]，[鹿饮溪]，[YjH]，[宋明亮]，[Mr. Ren]，[张益兴]，[深水海豚]，[王兴宇]，[Justice]，[Datura stramonium L.]，[ฅ农夫酸甜有点咸ฅ]，[小爱-李捷承])