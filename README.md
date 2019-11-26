# JavaScript综合练习

##  要求

- 用原生JS

## 开始

### 练习1

新建一个页面，页面上有一个**多行**输入框，一个提交按钮。输入框中用来输入用户的爱好，用逗号，顿号或者空额分隔，数量最多为10个，不能为空。点击提交后，若用户有错误的输入，在按钮上方显示一段红色的错误提示文字，并且不执行后面的行为。输入正确时，提示文字消失。

按照分隔符分开后把输入的内容保存到数组中，过滤掉空的和重复的内容，在按钮显示处理后的爱好。

![image](https://github.com/caiduncheng/peixun3/blob/master/img/image-20191126002106375.png?raw=true)

![image](https://github.com/caiduncheng/peixun3/blob/master/img/image-20191126002153992.png?raw=true)



### 练习2

实现一个倒计时功能。

- 界面有个输入框，按照格式`yyyy-mm-dd`输入年月日

- 输入框旁边有按钮，点击按钮后，计算当前距离输入的日期的00:00:00有多少时间误差

- 在页面中显示，距离在输入框中输入的年月日还有多少天多少小时多少秒

- 每一秒更新倒计时

- 如果时差为0，停止倒计时

  ![image](https://github.com/caiduncheng/peixun3/blob/master/img/image-20191126092331485.png?raw=true)

### 练习3

做一个轮播图，要求：

- 可以更改轮播的配置，顺序（正序、逆序）、间隔、是否循环

- 图片切换要流畅

- 轮播图下方自动生成对应图片的小点，点击小点，轮播图切换到对应的图片

  ![image](https://github.com/caiduncheng/peixun3/blob/master/img/image-20191126091530819.png?raw=true)

### 练习4

做一个类似百度的输入提示框，在文本框输入关键字后，会出现输入提示。不要求和后端交互，伪造几个数据。比如:

```javascript
var data = ['bill', 'john', 'jeff']
```

要求：

- 可以使用鼠标点击提示框某个选项
- 可以使用键盘的上下键来选择某个选项，回车选中
- 选中后，输入框的内容变成选中的内容，输入框隐藏

