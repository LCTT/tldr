# scrapy

> Web 爬虫框架

- 创建一个工程：

`scrapy startproject {{project_name}}`

- 创建一个爬虫（在项目目录中）：

`scrapy genspider {{spider_name}} {{website_domain}}`

- 编缉爬虫 (在项目目录下）：

`scrapy edit {{spider_name}}`

- 运行爬虫 （在项目目录下面）：

`scrapy crawl {{spider_name}}`

- 当 scrapy 获取到一个页面时，将其源码输出到标准输出：

`scrapy fetch {{url}}`

- 在默认浏览器中打开 scrapy 探测到的网页（禁用  javascript 以获得额外的保真度）：

`scrapy view {{url}}`

- 针对某个 url 打开一个 scrapy shell，以便在 Python shell（或 ipython）中交互性操作页面源码：

`scrapy shell {{url}}`

[#]: contributors: ([硬核老王（📺Linux中国）]，[Datura stramonium L.])