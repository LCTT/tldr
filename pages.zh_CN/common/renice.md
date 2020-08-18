# renice

> 更改一个或多个正在运行的进程的调度优先级（精密度值）精密度值范围从 -20（对进程最有利）到 19（对进程最不利）

- 更改运行中的进程的优先级：

`renice -n {{niceness_value}} -p {{pid}}`

- 更改一个用户的所有进程的优先级：

`renice -n {{niceness_value}} -u {{user}}`

- 更改属于一个流程组的所有流程的优先级：

`renice -n {{niceness_value}} --pgrp {{process_group}}`

[#]: contributors: ([王興與·區塊鏈·Linux中國]，[Judie])