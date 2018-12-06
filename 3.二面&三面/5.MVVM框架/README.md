#   MVVM框架类:
        1.了解MVVM框架吗?(vue,react,anguler)
        2.谈谈你对MVVM的认识?
        3.双向绑定是什么原理,可以写出来吗?
        4.使用了什么设计模式?
        5.生命周期是什么?
        6.有看过源码吗?

##  1.了解MVVM框架吗?

        vue.js,react.js,anguler.js

*       注意事项:

            1.一定要想好说 哪个

            2.收住有点,攒着下面说,开启引导模式

            3.话别说的太满,低调谨慎

##  2.对MVVM的认识?

    1.先聊MVC  Model - View - Controll 

    2.聊聊MVVM的定义:
        Model  <-> ViewModel  <->  View

    注意事项:
        1.聊聊MVC,彰显只是面涉猎较多

        2.把MVVM的定义说清楚,表达概念理解到位

        4.对比MVVM和MVC

##  2.双向绑定是什么原理

                反向▶
*       View  ------- Data
                ◀正向




            input 事件
            ------→
                反向▶
        View  ------- Data
                ◀正向
            ←-----
            ES6中的API:Object.defineProperty


        1.object.defineProperty 的用法要熟记于心

        2.object.defineProperty 与 reflect.defineProperty的区别
        reflect.defineProperty:es6中的语法,返回一个 布尔值
        object.defineProperty:es5 返回一个 新的对象

        3.object.defineProperty 要会手写

## 使用了什么设计模式?

*       观察者模式
        如图:设计模式.png

        1.观察者设计模式的原理了如指掌

        2.最好能写出设计模式的伪代码

        3.如果没有问到设计模式,也要找时机表现出来


##  生命周期是什么?

        1.熟悉对应的几个节点

        2.书记每个节点出发的时机

        3.做好演练一下

## 源码解析:

    