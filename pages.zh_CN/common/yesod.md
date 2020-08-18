# yesod

> 基于 Haskell 的 web 框架 Yesod 的帮助工具
> 所有 Yesod 命令都通过 stack 项目管理器调用

- 在 my-project 目录中创建一个新的 scaffolded 站点，sqlite 作为后端：

`stack new {{my-project}} {{yesod-sqlite}}`

- 在 Yesod scaffolded 站点中安装 Yesod CLI 工具：

`stack build yesod-bin cabal-install --install-ghc`

- 启动开发服务器：

`stack exec -- yesod devel`

- 使用更改的模板 haskell 依赖项触摸文件：

`stack exec -- yesod touch`

- 使用 Keter 部署应用程序( Yesod 的部署管理器)：

`stack exec -- yesod keter`

[#]: contributors: ([潘潘]，[jim.大团结]，[󠀀]，[mao da])