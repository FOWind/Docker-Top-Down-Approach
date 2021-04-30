# 搭建 Docker CE 源码编写环境

## 查看 Docker-CE 源码

当我们首次打开源码，在默认环境下 VSCode 会提示项目太大，不能有效追踪文件变化。

![too many file](./img/too-many-file.png)

这时需要修改 Linux 的内核参数，使用下面的命令修改就可以

```shell
sudo su
echo 'fs.inotify.max_user_watches=524288' > /etc/sysctl.conf 
sysctl -p
```

## GOPATH 问题处理

## 开始 DEBUG 模式

### docker/cli 打下第一个断点

### moby/moby 打下第一个断点
