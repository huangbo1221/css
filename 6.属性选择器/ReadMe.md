# 属性选择器
## 初始代码如下：

![img.png](img.png)

效果如下：

![img_1.png](img_1.png)

## 属性选择举例
### 选择存在id属性的元素
代码如下：

![img_2.png](img_2.png)

效果如下：

![img_3.png](img_3.png)

### 选择id为first的元素
代码如下：

![img_4.png](img_4.png)

效果如下：

![img_5.png](img_5.png)

可见，后面的选择会覆盖前面的选择！！！

### 选择包含某个元素
代码如下：

![img_6.png](img_6.png)

效果如下：

![img_7.png](img_7.png)

a[class*="links"]中表示class中包含links的属性！！！

### 以某个字符串开头的属性
代码如下：

![img_8.png](img_8.png)

效果如下：

![img_9.png](img_9.png)

a[href^="http"]中表示href属性中以http开头的属性！！！

### 以某个字符串结尾的属性
代码如下：

![img_10.png](img_10.png)

效果如下：

![img_11.png](img_11.png)

a[href$="doc"]中表示href属性中以doc结尾的属性！！！