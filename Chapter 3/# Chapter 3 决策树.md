# Chapter 3 决策树
#### 错误1：TypeError: 'dict_keys' object is not subscriptable
这是因为在python3中keys不允许切片，先转List再切片就好了
只要将以下几行代码：
#### line14 line24 line46：firstStr = myTree.keys()[0]
改为：
#### firstStr = list(myTree.keys())[0] 即可。