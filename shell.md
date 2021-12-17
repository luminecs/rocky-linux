## 安装

## 格式化

mkfs.xfs /dev/sdb

mkfs.xfs -f /dev/sdb

## 查找磁盘

sudo fdisk -l

## 挂载磁盘

mount /dev/sdb1 /mnt/sdb1

设置开机自动挂载

修改 `/etc/fstab` 文件，追加一行
```
/dev/sdb1               /mnt/sdb1               xfs     defaults        1 2
```

## 压缩、解压

## 定时任务

