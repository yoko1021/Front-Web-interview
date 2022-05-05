# 其他

## 前端异常监控
[前端性能和错误监控](https://github.com/woai3c/Front-end-articles/blob/master/monitor.md)

## Ascii、GBK、UTF、Unicode
* Ascii（1个字节1个字符）
* GBK是国内的编码标准（汉字2个字节）
* Unicode是国际编码标准（统一2个字节表示一个字符）
* UTF是Unicode实现的另一个标准
> unicode同样也不完美，这里就有两个的问题，一个是，如何才能区别unicode和ascii？<br>
由于”半角”英文符号只需要用到低8位，所以其高8位永远是0，因此这种大气的方案在保存英文文本时会多浪费一倍的空间<br>
unicode在很长一段时间内无法推广，直到互联网的出现，为解决unicode如何在网络上传输的问题，于是面向传输的众多 UTF（UCS Transfer Format）标准出现了，顾名思义，UTF-8就是每次8个位传输数据，而UTF-16就是每次16个位。UTF-8就是在互联网上使用最广的一种unicode的实现方式，这是为传输而设计的编码，并使编码无国界，这样就可以显示全世界上所有文化的字符了。UTF-8最大的一个特点，就是它是一种变长的编码方式。它可以使用1~4个字节表示一个符号，根据不同的符号而变化字节长度，当字符在ASCII码的范围时，就用一个字节表示，保留了ASCII字符一个字节的编码做为它的一部分，注意的是unicode一个中文字符占2个字节，而UTF-8一个中文字符占3个字节）。从unicode到utf-8并不是直接的对应，而是要过一些算法和规则来转换。

https://www.zhihu.com/question/23374078/answer/69732605

## 前端性能优化
[前端性能优化 24 条建议（2020）](https://github.com/woai3c/Front-end-articles/blob/master/performance.md)


## rpc远程过程调用
[谁能用通俗的语言解释一下什么是 RPC 框架？](https://www.zhihu.com/question/25536695)

## 浏览器工作原理
* [浏览器的工作原理：新式网络浏览器幕后揭秘](https://www.html5rocks.com/zh/tutorials/internals/howbrowserswork/)
* [图解浏览器的基本工作原理](https://zhuanlan.zhihu.com/p/47407398)

## 单点登录
[单点登录（SSO）看这一篇就够了](https://developer.aliyun.com/article/636281)
