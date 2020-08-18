# logwatch

> 在单个报告中汇总公共服务的许多不同日志（例如，apache，pam_unix，sshd 等）

- 在特定详细级别分析日期范围的日志：

`logwatch --range {{yesterday|today|all|help}} --detail {{low|medium|others}}'`

- 限制报告仅包括所选服务的信息：

`logwatch --range {{all}} --service {{apache|pam_unix|etc}}`

[#]: contributors: ([潘潘])