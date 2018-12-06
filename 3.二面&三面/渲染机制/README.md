##  渲染机制

        什么式DOCTYPE及作用?

            DTD(document type definition,文档类型定义) 是一系列的语法规则,用来定义XML 或(X)HTML的文件类型.浏览器会使用它来判断文档类型,决定使用何种协议来解析,以及切换浏览器模式

            DOCTYPE 是用来声明文档类型 和DTD 规范的, 一个主要的用途便是文件的合法性验证,如果文件代码不合法,那么浏览器解析是便会出现错误

            H5:
            <!DOCTYPE html>


            HTML4.01 transitional:(传统模式)

             <DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" " http://www.w3.org/TR/html4/loose.dtd">


            HTML4.01 strict:(严格模式)

            DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01//EN" "http://www.w3.org/TR/html4/strict.dtd"


        浏览器渲染过程

        重排 Reflow

        重绘 Repaint

        布局 Layout