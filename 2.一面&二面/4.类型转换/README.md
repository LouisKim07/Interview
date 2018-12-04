# 类型转换
##  数据类型
##  显示类型转换
##  隐式类型转换
*   最新的ECMAScript 标准定义了 7 个数据类型
*   原始类型:
*           Boolean Null Undefined Number String Symbol
*   对象:
*           Object
### 显示类型转换:
*       Number函数
*       String函数
*       Boolean函数
*     显示类型转化->  Number 函数
*     原始类型转换:
*           数值: 转换后还是原来的值.
*           字符串: 如果可以被解析为数值,则转换为相应的数值,否则得到NaN.空字符串为 0
*           布尔值: true转成1,false转成0.
*           *undefined*: 转成*NaN* .
*           null: 转成 0
*    对象类型转换(Number对对象类型的转换):
*           先调用对象自身的 *valueOf* 方法,如果返回类型的值(数值,字符串和布尔类值),则直接对该值使用
*        *Number*方法,不再进行后续步骤.
*           
*           如果*valueOf* 方法返回复合类型的值,再调用对象自身的 * toString * 方法

*           如果 toString 方法返回的是复合类型的值.则报错.