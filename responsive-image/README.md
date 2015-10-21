# 图片宽度自适应

demo来自[div.io](http://div.io)专栏[浅谈图片宽度自适应解决方案](http://div.io/topic/1396)

## 解决方案

嵌套标签来控制img宽度，width:100%相对于父级元素。此时存在三种解决方案：

1. 多嵌套一层div.row（demo4）
2. 清除浮动，影响之后元素（demo5）
3. 使用inline-block和br（demo6）

## 存在问题

1. demo4为什么需要overflow
2. 深刻理解demo6的inline-block