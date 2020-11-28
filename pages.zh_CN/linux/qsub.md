# qsub

> 提交一个脚本到队列管理系统 TORQUE

- 提交一个脚本，使用默认设置 (依赖于 TORQUE 设置)：

`qsub {{script.sh}}`

- 提交一个脚本，指定唤醒运行时限为 1 小时 2 分钟 3 秒：

`qsub -l walltime={{1}}:{{2}}:{{3}} {{script.sh}}`

- 提交一个脚本，在 2 个节点上执行，每个节点使用 4 个核：

`qsub -l nodes={{2}}:ppn={{4}} {{script.sh}}`

- 提交一个脚本到指定队列注意不同队列会有不同的最大、最小运行时限：

`qsub -q {{queue_name}} {{script.sh}}`

[#]: contributors: ([东先生])