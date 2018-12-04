# DOM 事件类
##    1.基本概念:DOM事件的级别
##    2.DOM事件模型(捕获和冒泡)
##    3.DOM事件流()
##    4.描述DOM事件捕获的具体流程:
##    5.Event 对象的常见应用()
##    6.自定义事件

#  DOM 事件类-- 事件级别:
##     DOM0   element.onclick = function(){}

##     DOM2   element.addEventListener('click',fucntion(){},false)

##     DOM3   element.addEventListener('keyup',fucntion(){},false)

#  DOM 事件类 -- 事件模型
##   捕获 <-> 冒泡 

#  DOM 事件类 -- 事件流(完整事件流分 3 阶段:如下,)
##   捕获 -> 目标阶段 -> 冒泡 


##  DOM 事件类:--描述DOM事件捕获的具体流程
*   window -> document -> html -> body -> ...
*   html:->  document.documentElement 

## DOM 事件类: Event对象常见应用

*    event.preventdefault(); -- 阻止默认事件(例如,a标签,可以阻止默认跳转行为)
*    event.stopPropagation() -- 阻止冒泡
*    event.stopImmediatePropagation() --
*    event.currentTarget() --
*    event.target() --