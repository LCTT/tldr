# openssl

> OpenSSL 加密工具集

- 生成 2048 bit RSA 私钥并将其保存到文件中：

`openssl genrsa -out {{文件名.key}} 2048`

- 生成要发送到证书颁发机构的证书签名请求：

`openssl req -new -sha256 -key {{filename.key}} -out {{filename.csr}}`

- 从有效期为几天的证书签名请求生成自签名证书：

`openssl x509 -req -days {{days}} -in {{filename.csr}} -signkey {{filename.key}} -out {{filename.crt}}`

- 显示证书信息：

`openssl x509 -in {{filename.crt}} -noout -text`

- 显示域证书的开始日期和到期日期：

`openssl s_client -connect {{host}}:{{port}} 2>/dev/null | openssl x509 -noout -dates`

- 显示由 SSL/TLS 服务器提供的证书：

`openssl s_client -connect {{host}}:{{port}} </dev/null`

- 显示 HTTPS 服务器的完整证书链：

`openssl s_client -connect {{host}}:443 -showcerts </dev/null`

[#]: contributors: ([Datura stramonium L.]，[白宦成])