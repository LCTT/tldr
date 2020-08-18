# git bisect

> 用二分法查找出问题的提交
> Git 自动在提交图谱里来回跳转，逐渐缩小范围直到找到问题提交
> 主页地址: <https://git-scmcom/docs/git-bisect>

- 在指定问题提交和没有问题的提交（通常是早期的提交）之间开始二分查找：

`git bisect start {{bad_commit}} {{good_commit}}`

- 使用二分法选择提交，测试问题是否存在后对其进行标记，没问题 good，有问题 bad：

`git bisect {{good|bad}}`

- 定位到问题提交后，结束二分查找返回到之前的分支：

`git bisect reset`

- 在查找时跳过一次提交（例如，这次提交由其他问题引起测试失败）：

`git bisect skip`

[#]: contributors: ([李峰])