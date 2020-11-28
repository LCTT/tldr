# berks

> Chef 的 cookbook 依賴度管理器

- 安装 cookbook 的依赖性于本地存储库：

`berks install`

- 更新指定的 cookbook 极其依赖性：

`berks update {{cookbook}}`

- 上传 cookbook 至 Chef 服务器：

`berks upload {{cookbook}}`

- 显示 cookbook 的依赖性：

`berks contingent {{cookbook}}`

[#]: contributors: ([潘潘]，[Judie])