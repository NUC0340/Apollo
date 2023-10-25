# Linux 基础入门与实践

[Linux视频讲解](https://apollo.baidu.com/community/course/outline/613?code=aa883598-a2b9-4037-bdbb-e3b605e57d0d)

## Linux 的基本操作

---

**linux 下的文件系统为树形结构，入口为/ ， 无论哪个版本的linux系统，都有这些目录， 这些目录是标准的。各个Linux发行版本会存在一些小小的差异，但总体来说，还是大体相近的**

例如：

1. /bin存放了大多数的系统命令
2. /boot存放了大多数与开机相关的命令
3. /etc目录保存了系统管理所需的配置和子目录
4. /root该目录为系统管理员，也称作超级权限者的用户主目录

*以下是Linux中常用的命令*  ：

![屏幕截图 2023-10-24 225037](C:\Users\Lenovo\Pictures\Screenshots\屏幕截图 2023-10-24 225037.png)

*关于在Terminal中修改代码的方法* ：

vim文本编译器

1.vim使用方法：vim 文件名

2.vim文本编译器的模式：

​                                         **以键盘上的i进行输入模式的切换**

​                                              **Esc进入底线命令模式**

![屏幕截图 2023-10-25 103957](C:\Users\Lenovo\Pictures\Screenshots\屏幕截图 2023-10-25 103957.png)

3.vim文本编译器的保存与退出:

​              **在进入底线命令模式后输入冒号： 加上下面你想要进行的操作**

![屏幕截图 2023-10-25 104305](C:\Users\Lenovo\Pictures\Screenshots\屏幕截图 2023-10-25 104305.png)

最后可以在Terminal中可以用cat加文件名进行文件的查看