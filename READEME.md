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

