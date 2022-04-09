# 浏览器工作原理与实践目录：

## 1.宏观视角上的浏览器

- [Chrome 架构：仅仅打开 1 个页面，为什么有 4 个进程](./1.宏观视角上的浏览器/1.1.Chrome架构：仅仅打开1个页面，为什么有4个进程/index.md)
- [TCP 协议：如何保证页面文件能被完整送达浏览器](./1.宏观视角上的浏览器/1.2.TCP协议：如何保证页面文件能被完整送达浏览器/index.md)
- [HTTP 请求流程：为什么很多站点第二次打开速度会很快](./1.宏观视角上的浏览器/1.3.HTTP请求流程：为什么很多站点第二次打开速度会很快/index.md)
- [导航流程：从输入 URL 到页面展示这中间发生了什么](./1.宏观视角上的浏览器/1.4.导航流程：从输入URL到页面展示这中间发生了什么/index.md)
- [渲染流程（上）：HTML、CSS 和 JavaScript 是如何变成页面的](./1.宏观视角上的浏览器/1.5.渲染流程（上）：HTML、CSS和JavaScript是如何变成页面的/index.md)
- [渲染流程（下）：HTML、CSS 和 JavaScript 是如何变成页面的](./1.宏观视角上的浏览器/1.6.渲染流程（下）：HTML、CSS和JavaScript是如何变成页面的/index.md)

## 2.浏览器中的 JavaScript 执行机制

- [变量提升：JavaScript 代码是按顺序执行的吗](./2.浏览器中的JavaScript执行机制/2.1.变量提升：JavaScript代码是按顺序执行的吗/index.md)
- [调用栈：为什么 JavaScript 代码会出现栈溢出](./2.浏览器中的JavaScript执行机制/2.2.调用栈：为什么JavaScript代码会出现栈溢出/index.md)
- [块级作用域：var 缺陷以及为什么要引入 let 和 const](./2.浏览器中的JavaScript执行机制/2.3.块级作用域：var缺陷以及为什么要引入let和const/index.md)
- [作用域链和闭包：代码中出现相同的变量，JavaScript 引擎如何选择](./2.浏览器中的JavaScript执行机制/2.4.作用域链和闭包：代码中出现相同的变量，JavaScript引擎如何选择/index.md)
- [this：从 JavaScript 执行上下文视角讲 this](./2.浏览器中的JavaScript执行机制/2.5.this：从JavaScript执行上下文视角讲this/index.md)

## 3.V8 工作原理

- [栈空间和堆空间：数据是如何存储的](./3.V8工作原理/3.1.栈空间和堆空间：数据是如何存储的/index.md)
- [垃圾回收：垃圾数据如何自动回收](./3.V8工作原理/3.2.垃圾回收：垃圾数据如何自动回收/index.md)
- [编译器和解析器：V8 如何执行一段 JavaScript 代码的](./3.V8工作原理/3.3.编译器和解析器：V8如何执行一段JavaScript代码的/index.md)

## 4.浏览器中的页面循环系统

- [消息队列和事件循环：页面是怎么活起来的](./4.浏览器中的页面循环系统/4.1.消息队列和事件循环：页面是怎么活起来的/index.md)
- [Webapi：setTimeout 是怎么实现的](./4.浏览器中的页面循环系统/4.2.Webapi：setTimeout是怎么实现的/index.md)
- [Webapi：XMLHttpRequest 是怎么实现的](./4.浏览器中的页面循环系统/4.3.Webapi：XMLHttpRequest是怎么实现的/index.md)
- [宏任务和微任务：不是所有的任务都是一个待遇](./4.浏览器中的页面循环系统/4.4.宏任务和微任务：不是所有的任务都是一个待遇/index.md)
- [使用 Promise 告别回调函数](./4.浏览器中的页面循环系统/4.5.使用Promise告别回调函数/index.md)
- [async-await 使用同步方式写异步代码](./4.浏览器中的页面循环系统/4.6.async-await使用同步方式写异步代码/index.md)

## 5.浏览器中的页面

- [页面性能分析：利用 chrome 做 web 性能分析](./5.浏览器中的页面/5.1.页面性能分析：利用chrome做web性能分析/index.md)
- [DOM 树：JavaScript 是如何影响 DOM 树构建的](./5.浏览器中的页面/5.2.DOM树：JavaScript是如何影响DOM树构建的/index.md)
- [渲染流水线：CSS 如何影响首次加载时的白屏时间](./5.浏览器中的页面/5.3.渲染流水线：CSS如何影响首次加载时的白屏时间/index.md)
- [分层和合成机制：为什么 CSS 动画比 JavaScript 高效](./5.浏览器中的页面/5.4.分层和合成机制：为什么CSS动画比JavaScript高效/index.md)
- [页面性能：如何系统优化页面](./5.浏览器中的页面/5.5.页面性能：如何系统优化页面/index.md)
- [虚拟 DOM：虚拟 DOM 和实际 DOM 有何不同](./5.浏览器中的页面/5.6.虚拟DOM：虚拟DOM和实际DOM有何不同/index.md)
- [PWA：解决了 web 应用哪些问题](./5.浏览器中的页面/5.7.PWA：解决了web应用哪些问题/index.md)
- [webComponent：像搭积木一样构建 web 应用](./5.浏览器中的页面/5.8.webComponent：像搭积木一样构建web应用/index.md)

## 6.浏览器中的网络

- [HTTP1：HTTP 性能优化](./6.浏览器中的网络/6.1.HTTP1：HTTP性能优化/index.md)
- [HTTP2：如何提升网络速度](./6.浏览器中的网络/6.2.HTTP2：如何提升网络速度/index.md)
- [HTTP3：甩掉 TCP、TCL 包袱，构建高效网络](./6.浏览器中的网络/6.3.HTTP3：甩掉TCP、TCL包袱，构建高效网络/index.md)
- [同源策略：为什么 XMLHttpRequest 不能跨域请求资源](./6.浏览器中的网络/6.4.同源策略：为什么XMLHttpRequest不能跨域请求资源/index.md)
- [跨站脚本攻击 XSS：为什么 cookie 中有 httpOnly 属性](./6.浏览器中的网络/6.5.跨站脚本攻击XSS：为什么cookie中有httpOnly属性/index.md)
- [CSRF 攻击：陌生链接不要随便点](./6.浏览器中的网络/6.6.CSRF攻击：陌生链接不要随便点/index.md)
- [沙盒：页面和系统之间的隔离墙](./6.浏览器中的网络/6.7.沙盒：页面和系统之间的隔离墙/index.md)
- [HTTPS：让数据传输更安全](./6.浏览器中的网络/6.8.HTTPS：让数据传输更安全/index.md)
