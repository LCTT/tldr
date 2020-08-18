# hyperfine

> 命令行基准测试工具
> 主页: <https://githubcom/sharkdp/hyperfine/>

- 运行一个基本的基准测试，至少运行 10 次：

`hyperfine '{{make}}'`

- 运行比较基准：

`hyperfine '{{make target1}}' '{{make target2}}'`

- 更改基准测试运行的最小数量：

`hyperfine --min-runs {{7}} '{{make}}'`

- 通过预热执行基准测试：

`hyperfine --warmup {{5}} '{{make}}'`

- 在每次基准测试运行之前运行命令（以清除缓存等）：

`hyperfine --prepare '{{make clean}}' '{{make}}'`

- 运行基准，其中每个运行的单个参数都会更改：

`hyperfine --prepare '{{make clean}}' --parameter-scan num_threads {{1}} {{10}} '{{make -j {num_threads}}}'`

[#]: contributors: ([潘潘]，[千柏]，[jim.大团结])