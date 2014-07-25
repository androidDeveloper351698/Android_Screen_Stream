Android_Screen_Stream
=====================

在无线自动化测试平台的搭建中，我们可能需要这样一个机器管理的场景：
在一个portal里，能够看到我们机器的一些基本情况，比如它是否在锁屏状态，运行是否正常。
如果能够看到屏幕回传的话......

### 工具优点

采用ddmlib高效截图方式,不在手机内部运行

### 运行环境

需要jython

### 依赖jar包

见代码顶端,自己调整一下

### 运行

```python
jython screenshot.py
```

### 打开demo.html

然后在目录中找到demo.html用chrome或者Firefox打开
你就可以欣赏到屏幕回传了。
不支持IE9以下浏览器......

### 效果展示

![效果](ass.PNG)

![效果](ass2.PNG)
