# Node.js 源码

> 为了什么而看源码？

- 深入理解它或一些底层的原理；
- 从中学到一些优秀的设计思想和实践。

Node.js -> libuv、V8、第三方库。

- JS 层：了解 Node.js 实现的一些上层逻辑，能够更深入的去了解；
- C++ 层：更多的是在了解怎么去使用 V8，可以当作兴趣使然，了解 js 实现的底层原理，又或者想了解一个编译器/解释器是如何实现的，他里面有一个编译器/解释器的通用逻辑，词法解析，语法解析，代码生成，代码优化等等；
- C 层：libuv，Node.js 是作为服务器的，libuv 可中可以学到相关的技术，文件系统、TCP、文件事件系统、线程池。
- 稀缺能力（情况极少）：当遇到一些难题，难以解决业界也没有好的方案，这个时候阅读源码的价值就能体现出来了。

## 看 Node.js 源码前的准备

> 看源码也是重要的学习过程，少不了调试，所以搭建环境是第一步。
