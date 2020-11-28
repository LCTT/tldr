# certbot

> 让我们对自动获取和更新 TLS 证书的代理进行加密
> `letsencrypt` 的继任品

- 通过 Webroot 授权获取新证书，但不会自动安装新证书：

`sudo certbot certonly --webroot --webroot-path {{path/to/webroot}} --domain {{subdomain.example.com}}`

- 通过 nginx 授权获取新证书，自动安装新证书：

`sudo certbot --nginx --domain {{subdomain.example.com}}`

- 通过 Apache 授权获取新证书，自动安装新证书：

`sudo certbot --apache --domain {{subdomain.example.com}}`

- 全部续订让我们加密在 30 天或更短时间内过期的证书（不要忘记在以后重新启动任何使用它们的服务器）：

`sudo certbot renew`

- 模拟获取新证书，但不要将任何新证书实际保存到磁盘：

`sudo certbot --webroot --webroot-path {{path/to/webroot}} --domain {{subdomain.example.com}} --dry-run`

- 改为获取不受信任的测试证书：

`sudo certbot --webroot --webroot-path {{path/to/webroot}} --domain {{subdomain.example.com}} --test-cert`

[#]: contributors: ([王兴宇，Linux & BC]，[玉叶])