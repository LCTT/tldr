# sbatch

> 向 SLURM 调度程序提交批处理脚本

- 提交批处理作业：

`sbatch {{path/to/job.sh}}`

- 使用自定义名称提交批处理作业：

`sbatch --job-name={{myjob}} {{path/to/job.sh}}`

- 提交时间限制为 30 分钟的批处理作业：

`sbatch --time={{00:30:00}} {{path/to/job.sh}}`

- 提交作业并请求多个节点：

`sbatch --nodes={{3}} {{path/to/job.sh}}`

[#]: contributors: ([Datura stramonium L.])