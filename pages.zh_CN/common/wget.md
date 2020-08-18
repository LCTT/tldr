# wget

> 从网络上下载文件
> 支持 HTTP, HTTPS和FTP

- 将URL的内容下载保存为文件（在本例中称为“foo”）：

`wget {{https://example.com/foo}}`

- 下载 URL 指向的内容并保存到文件中(该例子中的文件名是 bar )：

`wget -O {{bar}} {{https://example.com/foo}}`

- 下载一个网页及其所有资源(脚本，格式，图片，等等)：

`wget --page-requisites --convert-links {{https://example.com/somepage.html}}`

- 下载指定网站全部内容，相邻下载间隔3秒：

`wget --mirror --page-requisites --convert-links --wait=3 {{https://example.com}}`

- 下载指定目录及其递归子目录下的全部文件(不含网页中嵌套内容)：

`wget --mirror --no-parent {{https://example.com/somepath/}}`

- 使用 FTP 协议下载 URL 指向的内容：

`wget --ftp-user={{username}} --ftp-password={{password}} {{ftp://example.com}}`

- 继续处于中断的下载：

`wget -c {{https://example.com}}`

- 启用安静模式以减少输出：

`wget -q {{https://example.com}}`

[#]: contributors: ([Mr. Rat Ellipse]，[Justice]，[Datura stramonium L.])