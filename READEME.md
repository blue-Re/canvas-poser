# canvas的基本使用

## 一、画直线

常用的方法和属性

- 方法
  1. beginPath() 开始一条路径
  2. closePath() 结束一条路径
  3. moveTo(x, y) 定义线条开始的坐标
  4. lineTo(x, y) 定义线条结束的坐标
     - 可以进行直线的连用，调用完lineTo后继续调用
  5. stroke() 绘制一条路径，着色
     - 要在该方法之前对线条进行上色以及设置线宽
- 属性
  1. strokeStyle 属性设置或返回用于线条的颜色、渐变或者模式
  2. lineWidth 设置线宽

## 二、画矩形

1. 绘制矩形**需要着色描边，可以通过fill方法来填充颜色**

   rect(x, y, width, height)

   如果需要描边和填充，需要先进行填充，再进行描边，否则就会出现边框像素变小的问题。

2. 绘制实心矩形

   fillRect(x, y, width, height)

3. 绘制空心矩形

   strokeRect(x, y, width, height)

## 三、清除画布

clearRect(x, y, width, height) 清除画布

