#  页面性能类:

## 题目: 提升页面性能的方法有哪些?

*       1. 资源压缩合并,减少 HTTP 请求

        2.非核心代码异步加载: -> 异步加载的方式 -> 异步加载的区别

        3.利用浏览器缓存: -> 缓存的分类 -> 缓存的原理

        4.使用CDN

        5.预解析 DNS
            
            //https 协议默认关闭 dns 预解析
            //强制打开 dns预解析
            <meta http-equiv ="x-dns-prefetch-control" content="on">

            <link rel="dns-prefetch" href="//host_name_to_prefetch.com">

### 异步加载:

        1.异步加载的方式:

            1) ↓动态脚本的加载  2)defer   3)async
              (动态创建脚本(document.creatEle....))

        2.异步加载的区别
            1)  defer 是在HTML 解析完之后才会执行,如果是多个,按照加载的顺序依次执行
            
            2)  async 是在加载完成之后立即执行,如果是多个,执行顺序和加载顺序无关

### 浏览器缓存:

        1.缓存分类:
            
            1)  强缓存:

                Expires:    Expires:Thu,21 Jan 2017 23:39:02 GMT
                Cache-Control:  Cache-Control:max-age=3600

            2)  协商缓存:

                Last-Modified  If-Modified-Since    Last-Modified:Wed,26 Jan 2017 00:35:11 GMT
                Etag    If-None-Match