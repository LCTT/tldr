# mvn

> Apache Maven
> 一个构建和管理 JAVA 项目的工具

- 编译一个项目：

`mvn compile`

- 编译并使用一种发布格式打包已编译好的代码，如 .jar 文件：

`mvn package`

- 编译并打包，跳过单元测试：

`mvn package -Dmaven.test.skip=true`

- 从本地的 maven 仓库安装一个已构建好的包（在此同时将调用编译和打包命令）：

`mvn install`

- 从目标文件夹删除编译过的 artifact：

`mvn clean`

- 清理并打包：

`mvn clean package`

- 清理并使用一个配置文件进行打包：

`mvn clean -P{{profile}} package`

- 在 main 方法中运行一个类：

`mvn exec:java -Dexec.mainClass="{{com.example.Main}}" -Dexec.args="{{arg1 arg2}}"`

[#]: contributors: ([阿涛]，[好名字可以让你的朋友更容易记住你])