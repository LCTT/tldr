# duplicity

> 创建增量，压缩，加密和版本化备份
> 还可以将备份上载到各种后端服务

- 通过 FTPS 将目录备份到远程计算机，并使用密码对其进行加密：

`FTP_PASSWORD={{ftp_login_password}} PASSPHRASE={{encryption_password}} duplicity {{path/to/source/directory}} {{ftps://user@hostname/target/directory/path/}}`

- 将文件夹备份到 Amazon S3，每月进行一次完整备份：

`duplicity --full-if-older-than {{1M}} --use-new-style s3://{{bucket_name[/prefix]}}`

- 从存储在 WebDAV 共享上的备份中删除超过 1 年的版本：

`FTP_PASSWORD={{webdav_login_password}} duplicity remove-older-than {{1Y}} --force {{webdav[s]://user@hostname[:port]/some_dir}}`

- 列出可用的备份：

`duplicity collection-status "file://{{absolute/path/to/backup/folder}}"`

- 通过 ssh 列出存储在远程计算机上的备份中的文件：

`duplicity list-current-files --time {{YYYY-MM-DD}} scp://{{user@hostname}}/path/to/backup/dir`

- 将子目录从 GnuPG 加密的本地备份还原到给定位置：

`PASSPHRASE={{gpg_key_password}} duplicity restore --encrypt-key {{gpg_key_id}} --file-to-restore {{relative/path/restoredirectory}} file://{{absolute/path/to/backup/directory}} {{path/to/directory/to/restore/to}}`

[#]: contributors: ([琳小梁]，[潘潘])