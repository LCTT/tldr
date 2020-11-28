# yarn

> JavaScript 和 Nodejs 的新型包管理器
> 主页：<https://yarnpkgcom> 

- 安装一个全局模块：

`yarn global add {{module_name}}`

- 安装 `package.json` 文件中依赖的所有文件：

`yarn install`

- 安装一个模块并将其保存为 package.json 文件的依赖项（添加 --dev 以保存为 dev 依赖项）：

`yarn add {{module_name}}@{{version}}`

- 卸载模组并在 `package.json` 中移除：

`yarn remove {{module_name}}`

- 通过交互创建一个 `package.json` 文件：

`yarn init`

- 验证一个模组和其他模组的依赖关系：

`yarn why {{module_name}}`

[#]: contributors: ([潘潘]，[王兴宇，Linux & BC]，[玉叶]，[ntnyq]，[Mr. Ren]，[jim.大团结])