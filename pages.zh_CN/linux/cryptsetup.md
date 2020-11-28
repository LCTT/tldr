# cryptsetup

> 管理普通 dm-crypt 和 LUKS（ Linux 统一密钥设置）加密卷

- 初始化 LUKS 卷（覆盖分区上的所有数据）：

`cryptsetup luksFormat {{/dev/sda1}}`

- 打开LUKS卷并在 /dev/mapper/{{target}} 创建解密映射：

`cryptsetup luksOpen {{/dev/sda1}} {{target}}`

- 删除现有映射：

`cryptsetup luksClose {{target}}`

- 更改 LUKS 卷的密码：

`cryptsetup luksChangeKey {{/dev/sda1}}`

[#]: contributors: ([潘潘])