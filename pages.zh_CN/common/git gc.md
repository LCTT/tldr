# git gc

> 通过清理无用文件优化本地仓库
> 主页: <https://git-scmcom/docs/git-gc>

- 优化仓库：

`git gc`

- 深度清理，时间更久：

`git gc --aggressive`

- 不 prune 过期对象（默认会删除所有过期的、不可达的且未被打包的松散对象prune 过程相当于执行"git prune --expire"）：

`git gc --no-prune`

- 取消所有进度报告：

`git gc --quiet`

- 查看完整的使用说明：

`git gc --help`

[#]: contributors: ([Jangrui]，[庄秋彬])