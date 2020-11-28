# samtools

> 处理高通量序列（基因组学）数据的工具
> 用于以读取/写入/编辑/索引/查看SAM/BAM/CRAM 格式的数据

- 转换 SAM 输入文件为 BAM 流并保存到文件：

`samtools view -S -b {{input.sam}} > {{output.bam}}`

- 从标准输入（`-`）获取输入，并打印 SAM 标头和任何与特定区域重叠的读取到标准输出：

`{{other_command}} | samtools view -h - chromosome:start-end`

- 染色体：

`samtools sort {{input}} -o {{output.bam}}`

- 对文件进行排序并保存到 BAM（输出格式由输出文件的扩展名自动确定）：

`samtools index {{sorted_input.bam}}`

- 索引一个排序后的 BAM 文件（{{sorted_input.bam.bai}}）：

`samtools flagstat {{sorted_input}}`

- 打印一个文件的比对统计信息：

`samtools idxstats {{sorted_indexed_input}}`

- 对每个索引（染色体/对照）进行计数比对：

`samtools merge {{output}} {{input1 input2 …}}`

- 合并多个文件：

`samtools split {{merged_input}}`

[#]: contributors: ([王興與·區塊鏈·Linux中國])