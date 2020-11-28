# dmidecode

> 以人类可读方式显示硬件信息 DMI 表（也叫 SMBIOS）
> 需要管理员权限运行

- 列出 DMI 表所有内容：

`sudo dmidecode`

- 显示 BIOS 版本：

`sudo dmidecode -s bios-version`

- 显示系统的序列号：

`sudo dmidecode -s system-serial-number`

- 列出 BIOS 具体内容：

`sudo dmidecode -t bios`

- 列出 CPU 信息：

`sudo dmidecode -t processor`

- 列出内存信息：

`sudo dmidecode -t memory`

[#]: contributors: ([琳小梁]，[jrg])