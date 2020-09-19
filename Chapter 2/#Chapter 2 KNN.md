# Chapter 2 KNN

因为这本书写了很长时间了，我只是对照着这本书在学习一些机器学习的基础知识而已。顺便勘一下误。

#### 错误一：ValueError: invalid literal for int() with base 10: 'largeDoses'

首先这里是文件调用错了，应该调用datingDataSet2.txt

剩下的是一个python版本不同造成的问题：
如：

#### 错误二：iteritems变为items
把iteritems变为items即可

#### 错误三：NameError: name 'raw_input' is not defined
把raw_input替换成input即可。

#### 错误四：NameError: name ‘listdir’ is not defined
import os，然后改成os.listdir
