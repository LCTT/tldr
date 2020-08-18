# nix-collect-garbage

> 删除未使用或者不可达的nix（一种linux包管理器）存储路径
> 可以使用 `nix-env --list-generations`列出Generations

- 删除所有未被使用的存储路径，包括所有配置的当前版本：

`sudo nix-collect-garbage --delete-old`

- 模拟删除旧的存储路劲（dry run模式是不真实生效，显示执行过程，可供验证使用）：

`sudo nix-collect-garbage --delete-old --dry-run`

- 删除所有超过30天的存储路径：

`sudo nix-collect-garbage --delete-older-than {{30d}}`

[#]: contributors: ([杨振宇aiven])