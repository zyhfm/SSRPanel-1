koolshare Lede X64 Nuc
固件特性
64位4.14.72内核，4G以上内存和多核心支持，多核NAT
Intel自动省电降频，自动睿频，AES指令集加速，超线程 ，intel QAT硬件加速支持
独有的Koolshare软件中心加成。。。
安装方法
下载后可直接在LEDE WEB升级。也可解压缩后使用ImageWriter等工具直接将img写入U盘或者硬盘。
如果原来已经刷过openwrt系统，可将Lede-*.img上传到tmp,然后使用命令： dd if=/tmp/Lede-*.img of=/dev/sda写入。此命令将会清除原盘所有数据和分区，请注意备份。
默认WEB 192.168.1.1 用户名 root 密码 koolshare
技术支持
BUG反馈：Koolshare论坛LEDE版块

LEDE内测体验交流QQ群：103366563 用户交流反馈TG群 固件更新日志发布TG频道

最近更新 2018-09-30
注意：2.13以前版本固件升级到最新版本会丢失所有配置
Nuc点击菜单：系统-进阶设置-模式切换-nuc模式
升级前注意保存配置！
