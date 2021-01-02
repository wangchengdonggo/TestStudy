### 1.桌面没有命令行

~~~markdown
虚拟机本机安装测试机，连接桌面发现右键没有打开终端（open terminal）选项，着实不太方便，也搜了下网上资料，可以在 [菜单] - Applications - System Tools - Terminal 打开终端，也可以在 Applications - System Tools - Terminal 上点击右键 Add this launcher to desktop 会在桌面创建一个图标，但都没有直接在桌面右键，打开一个终端来的方便，
安装下面这个包后，重启系统就可以啦：

yum -y install nautilus-open-terminal


~~~

### 2.用到yum命令安装插件时发现一下错误

![image-20201226180635989](C:\Users\EDZ\AppData\Roaming\Typora\typora-user-images\image-20201226180635989.png)



~~~markdown
原因：centos6 20201130 停止维护了 官方源已经没有用了 镜像源也没用了
解决方法：
替换新的源： vault.centos.org

修改 /etc/yum.repos.d 中的 CentOS-Base.repo

1.注释所有的 mirrorlist
2.取消所有的 baseurl 注释
3.将 baseurl 中的mirrorlist.centos.org 改为 vault.centos.org
~~~

