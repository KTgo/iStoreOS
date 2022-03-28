# iStoreOS 固件

## 介绍

iStoreOS 是提供给入门级 OpenWRT 爱好者使用的固件，主要是为了简化操作，避免入门用户走进太多坑。其中包括：

* 提供拨号向导，简化拨号流程
* 简化 DNS 配置
* 简化硬盘格式化流程（坑最多）
* 提供 Samba 设置向导（原始的 OpenWRT 没提供 Samba 密码设置的功能）
* Docker 配置向导（未完成）
* 远程下载设置向导（未完成）

iStoreOS 还提供了软件中心：iStore，尽可能解决插件之间的依赖关系，可让大家自由自在安装插件。

除此之外，为了方便大家折腾不出问题，避免掉坑里，我们还做了很多防坑操作，比如 ARS2 固件里面有：

* 救援模式，即是固件完全刷坏，也可以进入救援模式救回来
* 沙箱模式，通过 U 盘进入沙箱模式，不管如何安装插件搞坏了系统，拔掉 U 盘就回到上个状态

当然 iStoreOS 还有整套易有云 APP 的协助，可以远程管理系统，远程访问插件，远程访问文件，备份相册，看电影等。满足了很多用户折腾半天都搞不定的场景需求。

## 使用方法

* 默认IP http://192.168.100.1
* 默认 eth0 是 WAN 口，其它都是 LAN。
* 如果只有一个网口，则默认是 WAN，可以通过一些方式获取 WAN 口的 IP 去访问路由器

其它离线安装包，请靠自己的能力去寻找。这里不提供任何离线安装包。

## 自己制作固件

iStoreOS 来源于官方的 OpenWRT Release 分支源码，几乎都是通过 OpenWRT 标准组件形式实现，所有插件源代码如下：

* https://github.com/linkease/nas-packages-luci
* https://github.com/linkease/nas-packages
* https://github.com/linkease/istore
* https://github.com/linkease/openwrt-themedog

iStoreOS 就是在 OpenWRT 最基础最原始的固件基础上，加上了上面插件的能力来实现

## 测试用例以及其它信息

请查看 wiki 侧边栏：

[Wiki](https://github.com/linkease/istoreos/wiki)

## 更多 iStoreOS 功能，请关注我们的 B 站账号

[酷友社 B 站账号](https://space.bilibili.com/1492058311?spm_id_from=333.788.0.0)
[酷友社 Youtube](https://www.youtube.com/channel/UCvENMyIFurJi_SrnbnbyiZw)

## 问题反馈

* 本项目 issue 反馈重大问题
* 视频下方评论
