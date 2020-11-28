# sdk

> 用于管理多个软件开发工具包的并行版本的工具
> 支持 Java，Groovy，Scala，Kotlin，Gradle，Maven，Vertx 等许多语言

- 安装指定版本的Gradle：

`sdk install {{gradle}} {{gradle_version}}`

- 切换至指定版本的Gradle：

`sdk use {{gradle}} {{gradle_version}}`

- 查看当前的gradle版本：

`sdk current {{gradle}}`

- 列出所有可安装的软件开发工具包：

`sdk list`

- 将Gradle升级到最新版本：

`sdk upgrade {{gradle}}`

- 卸载指定版本的Gradle：

`sdk rm {{gradle}} {{gradle_version}}`

[#]: contributors: ([阿涛]，[玉叶]，[　]，[󠀀])