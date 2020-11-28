# pup

> HTML命令行解析工具

- 将一个 HTML 文件转换为整洁的、带缩进和颜色的格式：

`cat {{index.html}} | pup --color`

- 使用元素标记名过滤一个 HTML 文件：

`cat {{index.html}} | pup '{{tag}}'`

- 使用id过滤HTML文件：

`cat {{index.html}} | pup '{{div#id}}'`

- 使用属性值过滤HTML文件：

`cat {{index.html}} | pup '{{input[type="text"]}}'`

- 打印过滤后的HTML所有元素及其子节点的文本：

`cat {{index.html}} | pup '{{div}} text{}'`

- 以JSON格式打印HTML：

`cat {{index.html}} | pup '{{div}} json{}'`

[#]: contributors: ([阿涛]，[好名字可以让你的朋友更容易记住你])