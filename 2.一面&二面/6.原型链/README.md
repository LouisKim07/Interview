# 原型链

## 创建对象有几种方法 -> 原型.构造函数.实例.原型链  ->  instanceof 的原理   ->  new 运算符

### 创建 (对象) 有几种方法?
*       1.字面量对象
            var 01 = {name: '01'};
            var o11 = new Object ({name: 'o11'});
        
        2.显示构造函数创建
        var M = function(){ this.name ='o2'}
        var o2 = new M();

        3.
        var P = {name:'o3'};
        var o3 = Object.create(p)