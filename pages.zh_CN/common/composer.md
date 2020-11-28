# composer

> PHP 项目的基于包的依赖管理器

- 添加项目的依赖包，将它添加到配置文件 `composer.json`：

`composer require {{user/package_name}}`

- 安装项目配置文件 `composer.json` 中所有依赖的包：

`composer install`

- 从项目中卸载包，移除`composer.json`依赖定义：

`composer remove {{user/package_name}}`

- 更新所有项目配置文件`composer.json`中依赖的包：

`composer update`

- 更新 composer 到最新版本：

`composer self-update`

[#]: contributors: ([琳小梁]，[启威])