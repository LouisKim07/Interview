### html+css 总结

#### 语义化掌握要到位
#### 页面布局理解深刻
#### css 接触知识扎实
#### 思维灵活且积极上进
#### 代码书写规范


# css 盒模型?
*     1.基本概念: 标准模型+IE模型
*     2. 标准模型盒和IE模型的区别(计算高度和宽度的不同)
*     3.css 如何设置这两种模型
*     4.js 如何设置获取盒模型对应的高和宽
*     5. 示例题(根据盒模型解释边距重叠)
*     6. BFC(块级格式化上下文) 或(IFC)的  边距重叠解决方案
*       1 BFC概念:块级格式化上下文
*       2 BFC的原理(渲染规则): 1.BFC元素的垂直方向边距的重叠
*                             2.BFC元素 区域不会与 浮动元素的box重叠
*                             3.BFC的独立的容器(内外元素互不影响)
*                             4.计算BFC高度浮动元素也会参与计算
*       3.如何创建BFC:
*           1.float:不为 none 即创建了BFC
*           2.position:不为 static(默认值)
*           3.display: inline-box,table-cell,等跟 table 相关的几个
*           4.overflow:不为 visible 
*       4.BFC 使用场景:
*           
* 
*        标准模型的宽和高: content(内容)的宽和高
*        IE模型的宽和高: content+border的宽和高
*        如何设置这两中模型来区分 标准模型和IE模型(css3):
*        box-sizing:content-box;(标准模型)
*        box-sizing:border-box;(IE模型)

*     7.JS 如何设置获取盒模型对应的宽和高(link.外部样式 , head.style ,dom.style)
*       dom.style.width/height(只能获取内联属性(有局限性))
*       dom.currentStyle.width/height (浏览器渲染后可用(仅IE支持此方法))
*       window.getComputedStyle(dom).width/height (兼容Chrome 和 Firefox)
*       window.getBoundingClientRect().width/height(也可以拿到元素的宽和高(即时渲染后))
*              应用的场景:根据视窗(左上角)计算元素的绝对位置(可获取:left,top,width,height)