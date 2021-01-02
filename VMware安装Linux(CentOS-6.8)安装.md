## VMware Workstation Pro安装

### 1.安装如下步骤进行操作

![image-20201230212018509](C:\Users\92588\Desktop\study-测试\笔记\img\image-20201230212018509.png)

### ![image-20201230212031005](C:\Users\92588\Desktop\study-测试\笔记\img\image-20201230212031005.png)

![image-20201230212051189](C:\Users\92588\Desktop\study-测试\笔记\img\image-20201230212051189.png)

![image-20201230212106637](C:\Users\92588\Desktop\study-测试\笔记\img\image-20201230212106637.png)

![image-20201230212116771](C:\Users\92588\Desktop\study-测试\笔记\img\image-20201230212116771.png)

![image-20201230212145844](C:\Users\92588\Desktop\study-测试\笔记\img\image-20201230212145844.png)

![image-20201230212210763](C:\Users\92588\Desktop\study-测试\笔记\img\image-20201230212210763.png)

### 2.打开VMware,输入如下激活码进行激活

~~~markdown
ZF3R0-FHED2-M80TY-8QYGC-NPKYF
YF390-0HF8P-M81RQ-2DXQE-M2UT6
ZF71R-DMX85-08DQY-8YMNC-PPHV8
~~~



## VMware上安装CentOS-6.8系统

### 1.新建虚拟机

![image-20201230213252101](C:\Users\92588\Desktop\study-测试\笔记\img\image-20201230213252101.png)

![image-20201230213313953](C:\Users\92588\Desktop\study-测试\笔记\img\image-20201230213313953.png)

![image-20201230213329804](C:\Users\92588\Desktop\study-测试\笔记\img\image-20201230213329804.png)

![image-20201230213353236](C:\Users\92588\Desktop\study-测试\笔记\img\image-20201230213353236.png)

![image-20201230213812289](C:\Users\92588\Desktop\study-测试\笔记\img\image-20201230213812289.png)

![image-20201230213824945](C:\Users\92588\Desktop\study-测试\笔记\img\image-20201230213824945.png)

### 2.编辑虚拟机

![image-20201230213907968](C:\Users\92588\Desktop\study-测试\笔记\img\image-20201230213907968.png)

![image-20201230214107031](C:\Users\92588\Desktop\study-测试\笔记\img\image-20201230214107031.png)

### 3.启动虚拟机

![image-20201230214216806](C:\Users\92588\Desktop\study-测试\笔记\img\image-20201230214216806.png)

![image-20201230214232632](C:\Users\92588\Desktop\study-测试\笔记\img\image-20201230214232632.png)

![image-20201230214245446](C:\Users\92588\Desktop\study-测试\笔记\img\image-20201230214245446.png)

![image-20201230214346958](C:\Users\92588\Desktop\study-测试\笔记\img\image-20201230214346958.png)

![image-20201230214407346](C:\Users\92588\Desktop\study-测试\笔记\img\image-20201230214407346.png)

![image-20201230214501806](C:\Users\92588\Desktop\study-测试\笔记\img\image-20201230214501806.png)



![image-20201230214530474](C:\Users\92588\Desktop\study-测试\笔记\img\image-20201230214530474.png)

**设置主机名**

![image-20201230214855804](C:\Users\92588\Desktop\study-测试\笔记\img\image-20201230214855804.png)

选择时区--**Asia/Shanghai**

![image-20201230214947778](C:\Users\92588\Desktop\study-测试\笔记\img\image-20201230214947778.png)

设置管理员**Root Password**（一定要记住！）

![image-20201230215029739](C:\Users\92588\Desktop\study-测试\笔记\img\image-20201230215029739.png)

分区--选最后一项--**Create Custom Layout** 自定义硬盘分区

注释：Use All Space 使用所有的空间

  Replace Existing Linux System(s) 替换已存在的Linux系统

  Shrink Current System 收缩进当前系统

  Use Free Spaace 使用空闲的空间

  Create Custom Layout 自定义硬盘分区

![image-20201230215226596](C:\Users\92588\Desktop\study-测试\笔记\img\image-20201230215226596.png)

分区

creat--Standard Partition--creat--mount point（挂载点）和File System Type（系统文件类型）

**分别创建/boot区、swap交换分区、根分区/**

注释：Linux系统最简单的分区方案：

1、分/boot区，给200M，/boot放启动文件。

2、分交换分区（交换空间）swap，看内存总大小，如果内存足够大，这个空间就要设置太大了。如果内存小于2G。那么这个空间设置成内存的2倍大小。

3、所有空间给/（根分区）

![image-20201230215331114](C:\Users\92588\Desktop\study-测试\笔记\img\image-20201230215331114.png)

![image-20201230215426762](C:\Users\92588\Desktop\study-测试\笔记\img\image-20201230215426762.png)

![image-20201230215633702](C:\Users\92588\Desktop\study-测试\笔记\img\image-20201230215633702.png)

![image-20201230215814553](C:\Users\92588\Desktop\study-测试\笔记\img\image-20201230215814553.png)

format格式化警告：格式化硬盘会破坏硬盘中所有数据--**Format**

![image-20201230215847135](C:\Users\92588\Desktop\study-测试\笔记\img\image-20201230215847135.png)

写入硬盘--**Write changes to disk**

![img](https://img2018.cnblogs.com/blog/1528076/201811/1528076-20181104140640262-1278397512.png)

安装boot引导

![image-20201230215949200](C:\Users\92588\Desktop\study-测试\笔记\img\image-20201230215949200.png)

![image-20201230220027876](C:\Users\92588\Desktop\study-测试\笔记\img\image-20201230220027876.png)

![image-20201230220209820](C:\Users\92588\Desktop\study-测试\笔记\img\image-20201230220209820.png)

#### 安装完成,进行重启即可



![image-20201230220315206](C:\Users\92588\Desktop\study-测试\笔记\img\image-20201230220315206.png)

![image-20201230220328196](C:\Users\92588\Desktop\study-测试\笔记\img\image-20201230220328196.png)

![image-20201230220346734](C:\Users\92588\Desktop\study-测试\笔记\img\image-20201230220346734.png)

### 4.初始化设置

![image-20201230220451525](C:\Users\92588\Desktop\study-测试\笔记\img\image-20201230220451525.png)

![image-20201230220513731](C:\Users\92588\Desktop\study-测试\笔记\img\image-20201230220513731.png)

![image-20201230220557643](C:\Users\92588\Desktop\study-测试\笔记\img\image-20201230220557643.png)

![image-20201230220634820](C:\Users\92588\Desktop\study-测试\笔记\img\image-20201230220634820.png)

![image-20201230220657206](C:\Users\92588\Desktop\study-测试\笔记\img\image-20201230220657206.png)

### 5.root帐号登录

![image-20201230220755861](C:\Users\92588\Desktop\study-测试\笔记\img\image-20201230220755861.png)

![image-20201230220816800](C:\Users\92588\Desktop\study-测试\笔记\img\image-20201230220816800.png)

![image-20201230220832827](C:\Users\92588\Desktop\study-测试\笔记\img\image-20201230220832827.png)

![image-20201230220846790](C:\Users\92588\Desktop\study-测试\笔记\img\image-20201230220846790.png)

### 6.安装完成

### 7.安装后的一些设置

#### 1》yum命令的使用

~~~~markdown
用到yum命令安装插件时发现错误
原因：centos6 20201130 停止维护了 官方源已经没有用了 镜像源也没用了
解决方法：
替换新的源： vault.centos.org
修改 /etc/yum.repos.d 中的 CentOS-Base.repo
1.注释所有的 mirrorlist
2.取消所有的 baseurl 注释
3.将 baseurl 中的mirrorlist.centos.org 改为 vault.centos.org

~~~~



#### 2》点击鼠标没有命令行

~~~markdown
虚拟机本机安装测试机，连接桌面发现右键没有打开终端（open terminal）选项，着实不太方便，也搜了下网上资料，可以在 [菜单] - Applications - System Tools - Terminal 打开终端，也可以在 Applications - System Tools - Terminal 上点击右键 Add this launcher to desktop 会在桌面创建一个图标，但都没有直接在桌面右键，打开一个终端来的方便，
安装下面这个包后，重启系统就可以啦：

yum -y install nautilus-open-terminal
~~~

#### 3》由于不能和主机进行复制，所以要安装Tools

~~~~markdown
1.在vmware工具栏找到虚拟机-》安装Vmware Tools
2.在桌面有一个文件夹VMware Tools点进去将VMware Tools-10.xxxxxxxxxx.tar.gz复制到桌面
3.在做桌面右击鼠标Open in Terminal 
4.tar -xzv -f VMware Tools-10.xxxxx。。文件名可以用TAB键补齐。进行文件夹解压
5.解压完后，Terminal进入桌面新生成的vmware-tools-distrib（cd vmware-tools-distrib)
6.执行安装（./vmware-install.pl）
7.重启虚拟机就可以使用了

~~~~

可参考：https://www.cnblogs.com/yujianadu/p/10454915.html

