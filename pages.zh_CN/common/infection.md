# infection

> 一个 PHP 的突变测试框架

- 使用配置文件分析代码（如果不存在，则创建一个）：

`infection`

- 使用特定数量的线程：

`infection --threads {{number_of_threads}}`

- 指定一个最小变异分数指示器（ MSI ）：

`infection --min-msi {{percentage}}`

- 指定最小覆盖代码 MSI：

`infection --min-covered-msi {{percentage}}`

- 使用特定的测试框架（默认为 phpunit ）：

`infection --test-framework {{phpunit|phpspec}}`

- 只改变测试所涵盖的代码行：

`infection --only-covered`

- 显示已应用的突变代码：

`infection --show-mutations`

- 指定日志详细性：

`infection --log-verbosity {{default|all|none}}`

[#]: contributors: ([玉叶])