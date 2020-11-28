# bedtools

> 基因组分析任务的利器
> 用于以 bam、bed、gff/gtf、vcf 格式对数据进行相交、分组、转换和计数

- 相对于序列的链将两个文件相交，并将结果保存到 path / to / output_file：

`bedtools intersect -a {{path/to/file_1}} -b {{path/to/file_2}} -s > {{path/to/output_file}}`

- 使用左外连接将两个文件相交，即报告 file_1 中的每个要素，如果与 file_2 不重叠则报为NULL：

`bedtools intersect -a {{path/to/file_1}} -b {{path/to/file_2}} -lof > {{path/to/output_file}}`

- 使用更有效的算法来交叉两个预先排序的文件：

`bedtools intersect -a {{path/to/file_1}} -b {{path/to/file_2}} -sorted > {{path/to/output_file}}`

- 基于前三和第五列分组文件 path / to / file ，并通过总结汇总第六列：

`bedtools groupby -i {{path/to/file}} -c 1-3,5 -g 6 -o sum`

- 将 bam-formated 文件转换为 bed-formated 文件：

`bedtools bamtobed -i {{path/to/file}}.bam > {{path/to/file}}.bed`

- 查找 file_1.bed 中的所有特征，在 file_2.bed 中找到最近的一个，并在额外的列中写下他们的距离（输入文件必须排序）：

`bedtools closest -a {{path/to/file_1}}.bed -b {{path/to/file_2}}.bed -d`

[#]: contributors: ([琳小梁]，[潘潘]，[Judie])