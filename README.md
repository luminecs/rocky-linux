# Rocky Linux 使用总结

## 把用户添加到 root 用户

Linux 普通用户 sudo su 无法执行，提示不在 sudoers 中。

```
su root
chmod 777 /etc/sudoers
# 在root all下增加该用户的一行数据，保存退出。最后恢复文件权限
chmod 440 /etc/sudoers
```

## 安装爱普生L4169打印机驱动

[驱动下载链接](https://epson.com/support/wa00821)

驱动备份

## 修改用户密码

切换到 root 用户，输入 passwd username，输入两次即可。
