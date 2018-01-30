## 新手上路

- 安装 Python

> 首先你应该确保你能访问[Python官方站点](https://www.python.org/)

Python官方站点曾经被屏蔽过，在写下这篇文章(2018/1/30)的时候它还是可以在中国大陆地区正常访问的。当然不排除以后某个时间段没办法访问的可能性。
> 尽管如此，中国大陆连接到Python官网的速度也很慢，但作为思想成熟的人类，你可以使用其他工具辅助一下。
我们以[Python3.6.4](https://www.python.org/downloads/release/python-364/)为例，当然你可以选择其他版本。准确来说，当很久以后Python发布了更新的版本，你应该选择更新的版本。
为什么不选择Python2.7版本？因为它实在太陈旧了，并且Python官方将停止对它的维护。注意，Python2与Python3并不兼容。
另外，在这个时候，Python3.7还处于开发阶段。以后可能会作出一些修订。
[其他版本的Python下载](https://www.python.org/downloads/)

在Windows系统下，安装是一件非常简单的事情，只需要按照安装程序的指示就可以安装完成Python.
在Mac下，如果你的系统版本高于10.8，那么系统自带Python2.7
在Linux系统下...使用 Linux 的一般不会是计算机入门选手，因此不作过多介绍。
 > 在windows下安装完成以后记得添加环境变量。Python安装完成后会附带一些已安装的库。

安装完可以在命令行工具中输入Python查看相关信息和进入界面。
```Python 3.6.4 (default, Jun 22 2015, 17:58:13) 
[GCC 4.8.2] on linux2
Type "help", "copyright", "credits" or "license" for more informat
ion.
>>> 

-从最简单的入手 Hello world

我们来打印一个hello world:
```>>> print ('Hello World!')
Hello World!

Python被官方形容为Quick & Easy to Learn, 其官网上给出的另一个实例是:
```>>>name = input('What is your name\n')
What is your name
hexu
>>>print('Hi,%s.' % name)
Hi,hexu.
 