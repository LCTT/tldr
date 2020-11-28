# disown

> 允许子进程脱离关联它的 shell 继续运行
> 参考 `jobs` 命令

- 解除当前任务的关联：

`disown`

- 将一个指定的任务解除关联：

`disown %{{job_number}}`

- 将所有任务解除关联：

`disown -a`

[#]: contributors: ([王兴宇，Linux 中國]，[holy4god])