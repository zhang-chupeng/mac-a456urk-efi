### a456urk ketx驱动

​	tips：需要关闭SIP


关闭SIP操作：
* 重启电脑
* 进入恢复模式（recovery模式）
* 进入终端  -（不点击重装系统等按钮，直接进入终端）
* csrutil status 查看SIP状态 一般显示为enable
* csrutil disable 关闭SIP
* csrutil 查看SIP状态是否为disable 关闭


```shell
sudo su
```

```shell
sudo mount -uw /
```

```shell
killall Finder 
```

* 用open 打开下面的路径 
* 将驱动放在/system/library/extensions

​				/library/extensions

最后运行kext Utility

重启系统
