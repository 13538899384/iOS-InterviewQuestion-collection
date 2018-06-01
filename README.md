
<p align='center'>
<img src='https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1526457040696&di=0c64726aa0fbf502bbb2af5142b8a1c2&imgtype=0&src=http%3A%2F%2Fimg2.jiemian.com%2F101%2Foriginal%2F20170408%2F149163479116565200.jpg'>
</p>

<p align='center'>
<img src="https://img.shields.io/badge/platform-iOS-ff69b4.svg">
<img src="https://img.shields.io/badge/language-Objective--C-orange.svg">
<img src="https://img.shields.io/badge/language-Swift-abcdef.svg">
<img src="https://img.shields.io/badge/PR-welcome%20!-brightgreen.svg?colorA=a0cd34">
</p>


## iOS-InterviewQuestion-collection（未完待续...）



> 最近在准备面试，所以自己边复习边整理，列出了一些自己复习的知识点。
> 
> 后面的一些知识模块之所以没有延展开，是因为有的地方自己理解的还不到位，我还需要时间仔细整理。
> 
> 这个仓库根据我的设想，我认为还远远没有完成，后续会不断更新，起初并不想写答案，但考虑到有的人需要，其次我自己写一个很简单的思路，起一个提示的作用，如果有想错的地方，也欢迎大家指正。
> 
> 再次说明：所有的答案只写思路，不会长篇大论的验证，只起到提示作用。
> 
> 欢迎大家提PR！



### 推荐书目
* 1.《Effective Objective-C 2.0》
* 2.《Objective-C 高级编程》
* 3.《程序员的自我修养》
* 4.《图解HTTP》
* 5.《高性能iOS应用开发》
* 6.《算法图解》
* 7.《剑指Offer》

## 0.数据结构及算法


### ①.数据结构
- 1.数组
- 2.字符串
- 3.链表
- 4.树
- 5.栈
- 6.队列
- 7.哈希表
- 8.字典

### ②.算法



###### 1.常见的摘要算法：
- HEX编码
- Base64
- MD5
- SHA1
- SHA256
- MAC算法

###### 2.常见对称加密算法
- AES
- DES
- 3DES
- Blowfish

###### 3.常见的排序算法
- 快速排序
- 堆排序
- 冒泡排序 - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/0.算法集合/冒泡排序.md)
- 选择排序
- 希尔排序
- 快速排序

###### 4.常见的字符编码方法
- 1.ASCII
- 2.ISO-8859-1
- 3.GB2312
- 4.GBK
- 5.UTF-8
- 6.UTF-16 
- 7.Unicode

> 推荐一个很好的算法总结 - [链接](https://github.com/CyC2018/Interview-Notebook)

###### 5.常考算法题
- 1.字符串反转 - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/0.算法集合/1.第一题.md)
- 2.链表反转
- 3.有序数组合并
- 4.Hash 算法
- 5.查找两个子视图的共同父视图
- 6.无序数组中的中位数
- 7.两数之和为特定值 - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/0.算法集合/7.第七题.md)
- 8.求出数组中连续数字的和值 - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/0.算法集合/8.第八题.md)
- 9.白鼠与毒酒的算法问题 - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/0.算法集合/9.第九题.md)
- 10.在一个数组中找出前四个最大的数字。- [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/0.算法集合/10.第十题.md)
- 11.假如有 10亿 条数据，每条数据的大小在 10k-100k 之间，我们有一台内存为 4G 的电脑，如何算出播放次数最多的一条微博？
- 12.如何打印一个矩阵？
- 13.如何验证一个 `IP` 地址的有效性？
- 栈中储存着一组无序的数字，不用便利的方式，如何找出最小值？

## 1.iOS 内存管理
- 1.讲一下 `iOS` 内存管理的理解？(三种方案的结合) - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/1.内存管理/1.第一题.md)
- 2.使用自动引用计（`ARC`）数应该遵循的原则? - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/1.内存管理/2.第二题.md)
- 3.`ARC` 自动内存管理的原则？ - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/1.内存管理/3.第三题.md)
- 4.访问 `__weak` 修饰的变量，是否已经被注册在了 `@autoreleasePool` 中？为什么？ - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/1.内存管理/4.第四题.md)
- 5.`ARC` 的 `retainCount` 怎么存储的？ - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/1.内存管理/5.第五题.md)
- 6.简要说一下 `@autoreleasePool` 的数据结构？ - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/1.内存管理/6.第六题.md)
- 7.`__weak` 和 `_Unsafe_Unretain` 的区别？ - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/1.内存管理/7.第七题.md)
- 8.为什么已经有了 `ARC` ,但还是需要 `@AutoreleasePool` 的存在？ - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/1.内存管理/8.第八题.md)
- 9.`__weak` 属性修饰的变量，如何实现在变量没有强引用后自动置为 `nil`？ - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/1.内存管理/9.第九题.md)
- 10.说一下对 `retain`,`copy`,`assign`,`weak`,`_Unsafe_Unretain` 关键字的理解。 - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/1.内存管理/10.第十题.md)
- 11.`ARC` 在编译时做了哪些工作？ - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/1.内存管理/11.第十一题.md)
- 12.`ARC` 在运行时做了哪些工作？ - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/1.内存管理/12.第十二题.md)
- 13.函数返回一个对象时，会对对象 `autorelease` 么？为什么？ - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/1.内存管理/13.第十三题.md)
- 14.说一下什么是 `悬垂指针`？什么是 `野指针`? - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/1.内存管理/14.第十四题.md)
- 15.内存管理默认的关键字是什么？ - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/1.内存管理/15.第十五题.md)
- 16.内存中的5大区分别是什么？ - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/1.内存管理/16.第十六题.md)
- 17.是否了解 `深拷贝` 和 `浅拷贝` 的概念，集合类深拷贝如何实现？ - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/1.内存管理/17.第十七题.md)
- 18.`BAD_ACCESS` 在什么情况下出现? - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/1.内存管理/18.第十八题.md)
- 19.讲一下 `@dynamic` 关键字？- [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/1.内存管理/19.第十九题.md)
- 20.`@autoreleasrPool` 的释放时机？- [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/1.内存管理/20.第二十题.md)
- 21.`retain`、`release` 的实现机制？- [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/1.内存管理/21.第二十一题.md)
- 22.能不能简述一下 `Dealloc` 的实现机制？- [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/1.内存管理/22.第二十二题.md)
- 23.在 `MRC` 下如何重写属性的 `Setter` 和 `Getter`? - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/1.内存管理/23.第二十三题.md)


## 2.Runtime
- 1.实例对象的数据结构？- [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/2.Runtime/1.第一题.md)
- 2.类对象的数据结构？- [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/2.Runtime/2.第二题.md)
- 3.元类对象的数据结构? - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/2.Runtime/3.第三题.md)
- 4.`Category` 的实现原理？ - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/2.Runtime/4.第四题.md)
- 5.如何给 `Category` 添加属性？关联对象以什么形式进行存储？ - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/2.Runtime/5.第五题.md)
- 6.`Category` 有哪些用途？ - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/2.Runtime/6.第六题.md)
- 7.`Category` 和 `Extension` 有什么区别？- [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/2.Runtime/7.第七题.md)
- 8.说一下 `Method Swizzling`? 说一下在实际开发中你在什么场景下使用过? - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/2.Runtime/8.第八题.md)
- 9.如何实现动态添加方法和属性？ - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/2.Runtime/9.第九题.md)
- 10.说一下对 `isa` 指针的理解， 对象的`isa` 指针指向哪里？`isa` 指针有哪两种类型？（注意区分不同对象） - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/2.Runtime/10.第十题.md)
- 11.`Obj-C` 中的类信息存放在哪里？ - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/2.Runtime/11.第十一题.md)
- 12.一个 `NSObject` 对象占用多少内存空间？- [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/2.Runtime/12.第十二题.md)
- 13.说一下对 `class_rw_t` 的理解？- [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/2.Runtime/13.第十三题.md)
- 14.说一下对 `class_ro_t` 的理解？- [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/2.Runtime/14.第十四题.md)
- 15.说一下 `Runtime` 消息解析。- [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/2.Runtime/15.第十五题.md)
- 16.说一下 `Runtime` 消息转发。- [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/2.Runtime/15.第十五题.md)
- 17.如何运用 `Runtime` 字典转模型？- [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/2.Runtime/17.第十七题.md)
- 18.如何运用 `Runtime` 进行模型的归解档？- [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/2.Runtime/18.第十八题.md)
- 19.在 `Obj-C` 中为什么叫发消息而不叫函数调用？- [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/2.Runtime/19.第十九题.md)
- 20.说一下对 `runtime` 的理解。（主要讲一下消息机制，是对上述的总结）
- 21.说一下 `Runtime` 的方法缓存？存储的形式、数据结构以及查找的过程？- [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/2.Runtime/21.第二十一题.md)
- 22.是否了解 `Type Encoding`? - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/2.Runtime/22.第二十二题.md)
- 23.`Objective-C` 如何实现多重继承？ - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/2.Runtime/23.第二十三题.md)


## 3.Runloop
- 1.`Runloop` 和线程的关系？ - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/3.Runloop/1.第一题.md)
- 2.讲一下 `Runloop` 的 `Mode`?(越详细越好)  - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/3.Runloop/2.第二题.md)
- 3.讲一下 `Observer` ？（Mode中的重点） - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/3.Runloop/3.第三题.md)
- 4.讲一下 `Runloop` 的内部实现逻辑？（运行过程） - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/3.Runloop/4.第四题.md)
- 5.你所知的哪些三方框架使用了 `Runloop`?（AFNetworking、Texture 等）
- 6.`autoreleasePool` 在何时被释放？ - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/3.Runloop/6.第六题.md)
- 7.解释一下 `事件响应` 的过程？ - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/3.Runloop/7.第七题.md)
- 8.解释一下 `手势识别` 的过程？ - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/3.Runloop/8.第八题.md)
- 9.解释一下 `GCD` 在 `Runloop` 中的使用？ - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/3.Runloop/9.第九题.md)
- 10.解释一下 `NSTimer`，以及 `NSTimer` 的循环引用。 - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/3.Runloop/10.第十题.md)
- 11.`AFNetworking` 中如何运用 `Runloop`? - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/3.Runloop/11.第十一题.md)
- 12.`PerformSelector` 的实现原理？- [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/3.Runloop/12.第十二题.md)
- 13.利用 `runloop` 解释一下页面的渲染的过程？- [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/3.Runloop/13.第十三题.md)
- 14.如何使用 `Runloop` 实现一个常驻线程？这种线程一般有什么作用？- [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/3.Runloop/14.第十四题.md)
- 15.为什么 `NSTimer` 有时候不好使？（不同类型的Mode）- [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/3.Runloop/15.第十五题.md)
- 16.`PerformSelector:afterDelay:`这个方法在子线程中是否起作用？为什么？怎么解决？- [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/3.Runloop/16.第十六题.md)
- 17.什么是异步绘制？- [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/3.Runloop/17.第十七题.md)


## 4.网络
- 1.`NSUrlConnect`相关知识。
- 2.`NSUrlSession`相关知识。
- 3.`Http` 和 `Https` 的区别？为什么更加安全？- [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/4.网络/3.第三题.md)
- 4.`Http`的请求方式有哪些？`Http` 有什么特性？- [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/4.网络/4.第四题.md)
- 5.解释一下 `三次握手` 和 `四次挥手`？解释一下为什么是`三次握手` 又为什么是 `四次挥手`？- [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/4.网络/5.第五题.md)
- 6.`GET` 和 `POST` 请求的区别？- [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/4.网络/6.第六题.md)
- 7.`HTTP` 请求报文 和 响应报文的结构？- [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/4.网络/7.第七题.md)
- 8.什么是 `Mimetype` ? - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/4.网络/8.第八题.md)
- 9.数据传输的加密过程？ - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/4.网络/9.第九题.md)
- 10.说一下 `TCP/IP` 五层模型的协议? - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/4.网络/10.第十题.md)
- 11.说一下 `OSI` 七层模型的协议? - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/4.网络/11.第十一题.md)
- 12.`大文件下载` 的功能有什么注意点？ - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/4.网络/12.第十二题.md)
- 13.`断点续传` 功能该怎么实现？ - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/4.网络/13.第十三题.md)
- 14.封装一个网络框架有哪些注意点？
- 15.`Wireshark`、`Charles`、`Paw` 等工具会使用吗？
- 16.`NSUrlProtocol`用过吗？用在什么地方了？ - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/4.网络/16.第十六题.md)
- 17.如何在测试过程中 `MOCK` 各种网络环境？ - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/4.网络/17.第十七题.md)
- 18.`DNS` 的解析过程？网络的 `DNS` 优化。 - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/4.网络/18.第十八题.md)
- 19.`Post`请求体有哪些格式？ - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/4.网络/19.第十九题.md)
- 20.网络请求的状态码都大致代表什么意思？- [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/4.网络/20.第二十题.md)
- 21.抓包软件 `Charles` 的原理是什么？说一下中间人攻击的过程。- [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/4.网络/21.第二十一题.md)
- 22.如何判断一个请求是否结束？- [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/4.网络/22.第二十二题.md)
- 23.`SSL` 传输协议？说一下 `SSL` 验证过程？- [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/4.网络/23.第二十三题.md)
- 24.解释一下 `Http` 的持久连接？- [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/4.网络/24.第二十四题.md)
- 25.说一下传输控制协议 - `TCP` ?- [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/4.网络/25.第二十五题.md)
- 26.说一下用户数据报协议 - `UDP` ? - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/4.网络/26.第二十六题.md)
- 27.谈一谈网络中的 `session` 和 `cookie`? - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/4.网络/27.第二十七题.md)

## 5.多线程
- 1.`NSThread`相关知识？ - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/5.多线程/1.第一题.md)
- 2.`GCD` 相关知识？ - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/5.多线程/2.第二题.md)
- 3.`NSOperation` 和 `NSOperationQueue`相关知识？ - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/5.多线程/3.第三题.md)
- 4.如何实现线性编程？ - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/5.多线程/4.第四题.md)
- 5.说一下 `GCD` 并发队列实现机制？
- 6.`NSLock` - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/5.多线程/6.第六题.md)
- 7.`NSContion` - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/5.多线程/7.第七题.md)
- 8.条件锁 - `NSContionLock`  - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/5.多线程/8.第八题.md)
- 9.递归锁 - `NSRecursiveLock` - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/5.多线程/9.第九题.md)
- 10.同步锁 - `Synchronized(self) {// code}`  - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/5.多线程/10.第十题.md)
- 11.信号量 - `dispatch_semaphore`。 - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/5.多线程/11.第十一题.md)
- 12.自旋锁 - `OSSpinLock` 。 - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/5.多线程/12.第十二题.md)
- 13.多功能🔐 - `pthread_mutex` - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/5.多线程/13.第十三题.md)
- 14.分步锁 - `NSDistributedLock`。- [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/5.多线程/14.第十四题.md)
- 15.如何确保线程安全？ - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/5.多线程/15.第十五题.md)
- 16.`NSMutableArray`、和 `NSMutableDictionary`是线程安全的吗？`NSCache`呢？ - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/5.多线程/16.第十六题.md)
- 17.多线程的 `并行` 和 `并发` 有什么区别？ - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/5.多线程/17.第十七题.md)
- 18.多线程有哪些优缺点？ - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/5.多线程/18.第十八题.md)
- 19.如何自定义 `NSOperation` ? - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/5.多线程/19.第十九题.md)
- 20.`GCD` 与 `NSOperationQueue` 有哪些异同？

## 6.项目架构
- 1.什么是 `MVC`?
- 2.什么是 `MVVM`?
- 3.什么是 `MVP`?
- 4.什么是 `CDD`?
- 5.项目的组件化？
    - 1.说一下你了解的项目组件化方案？
    - 2.什么样的团队及项目适合采用组件化的形式进行开发？
    - 3.组件之间的通信方式。
    - 4.各组件之间的解耦。
- 6.还了解哪些项目架构？你之前所在公司的架构是什么样的，简单说一下？

## 7.消息传递的方式

- 1.说一下 `NSNotification` 的实现机制？发消息是同步还是异步？ - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/7.消息传递的方式/1.第一题.md)
- 2.说一下 `NSNotification` 的特点。 - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/7.消息传递的方式/2.第二题.md)
- 3.简述 `KVO` 的实现机制。 - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/7.消息传递的方式/3.第三题.md)
- 4.`KVO` 在使用过程中有哪些注意点？有没有使用过其他优秀的 `KVO` 三方替代框架？ - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/7.消息传递的方式/4.第四题.md)
- 5.简述 `KVO` 的注册依赖键是什么？
- 6.如何做到 `KVO` 手动通知？ - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/7.消息传递的方式/6.第六题.md)
- 7.在什么情况下会触发 `KVO`?  - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/7.消息传递的方式/7.第七题.md)
- 8.给实例变量赋值时，是否会触发 `KVO`?  - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/7.消息传递的方式/8.第八题.md)
- 9.`Delegate`通常用什么关键字修饰？为什么？ - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/7.消息传递的方式/9.第九题.md)
- 10.`通知` 和 `代理` 有什么区别？各自适应的场景？ - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/7.消息传递的方式/10.第十题.md)
- 11.`__block` 的解释以及在 `ARC` 和 `MRC` 下有什么不同？- [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/7.消息传递的方式/11.第十一题.md)
- 12.`Block` 的内存管理。
- 13.`Block` 自动截取变量。
- 14.`Block` 处理循环引用。
- 15.`Block` 有几种类型？分别是什么？

## 8.数据存储
- Sqlite3 常用的语句
- Sqlite3 在不同版本的APP，数据库结构变化了，如何处理? 
- FMDB (`Sqlite3` 的封装)
- Realm
- NSKeyArchieve
- Preperfence
- Plist
- CoreDate
- Keychain
- UIPasteBoard(感谢 lilingyu0620 同学提醒)
- FoundationDB
- LRU(最少最近使用)缓存

## 9.iOS设计模式

> 这个模块需要大量代码，我就不贴了

- 1.编程中的六大设计原则？ - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/9.设计模式/1.第一题.md)
- 2.如何设计一个图片缓存框架？ - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/9.设计模式/2.第二题.md)
- 3.如何设计一个时长统计框架？ - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/9.设计模式/3.第三题.md)
- 4.如何实现 `App` 换肤（夜间模式）？ - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/9.设计模式/4.第四题.md)
- 5.外观模式
- 6.中介者模式
- 7.访问者模式
- 8.装饰模式 
- 9.观察者模式
- 10.责任链模式
- 11.命令模式
- 12.适配器模式
- 13.桥接模式
- 14.代理委托模式
- 15.单例模式
- 16.类工厂模式


## 10.音频处理

## 11.视频处理

## 12.图像处理
- 1.图像的压缩、解压。


## 13.iOS 动画
- 1.简要说一下常用的动画库。

## 14.蓝牙

## 15.ARKit

## 16.Core ML

## 17.代码管理、持续集成、项目托管
- 1.Git
    - 1.`git pull` 和 `git fetch` 的区别？
    - 2.`git merge` 和 `git rebase` 的区别？ 
    - 3.如何在本地新建一个分支，并 `push` 到远程服务器上？
    - 4.如果 `fork` 了一个别人的仓库，怎样与源仓库保持同步？
- 2.Svn
- 3.CocoaPods
    - 1.说一下 `CocoaPods` 的原理？
    - 2.如何让自己写的框架支持 `CocoaPods`？
    - 3.`pod update` 和 `pod install` 有什么区别？
    - 4.`Podfile.lock` 文件起什么作用？
    - 5.如何集成本地私有库？
    - 6.如何集成远程私有库 ？
- 4.Carthage
- 5.Fastlane
- 6.Jenkins
- 7.fir.im
- 8.蒲公英
- 9.TestFlight

## 18.数据安全及加密
- 1.RSA非对称加密 - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/18.数据安全及加密/1.第一题.md)
- 2.AES对称加密
- 3.DES加密
- 4.Base64加密
- 5.MD5加密
- 6.简述 `SSL` 加密的过程用了哪些加密方法，为何这么做？ - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/18.数据安全及加密/6.第六题.md)
- 7.是否了解 `iOS` 的签名机制？
- 8.如何对 `APP` 进行重签名？

## 19.源代码阅读
- 1.YYKit
- 2.SDWebImage
    - 缓存机制
    - 移除策略 
- 3.AFNetworking
- 4.SVProgressHub 
- 5.Texture（ASDK）

## 20.iOS逆向及安全

## 21.性能优化
- 1.如何提升 `tableview` 的流畅度？- [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/21.性能优化/1.第一题.md)
- 2.如何使用 `Instruments` 进行性能调优？(Time Profiler、Zombies、Allocations、Leaks)
- 3.如何优化 `APP` 的启动时间？（感谢 @静待海棠花开 的提醒）
- 4.如何对 `APP` 进行内存、电量、网络流量的优化？（感谢 @静待海棠花开 的提醒）
- 5.如何有效降低 `APP` 包的大小？
- 6.日常如何检查内存泄露？
- 7.能不能说一下物理屏幕显示的原理？
- 8.解释一下什么是屏幕卡顿、掉帧？该如何避免？
- 9.什么是 `离屏渲染`？什么情况下会触发？该如何应对？- [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/21.性能优化/9.第九题.md)

## 22.调试技巧 & 软件使用
- 1.`LLDB` 调试。
- 2.断点调试。
- 3.`NSAssert` 的使用。
- 4.`Charles` 的使用。
- 5.`Reveal` 的使用。
- 6.`iOS` 常见的崩溃类型有哪些？- [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/22.调试技巧/6.第六题.md)

## 23.扩展问题
- 1.无痕埋点
- 2.APM（应用程序性能监测）
- 3.Hot Patch（热修补）
- 4.崩溃的处理

## 24.其他问题
- 1.`UIView` 和 `CALayer` 是什么关系？- [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/24.其他问题/1.第一题.md)
- 2.`Bounds` 和 `Frame` 的区别? - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/24.其他问题/2.第二题.md)
- 3.`nil`、`NIL`、`NSNULL` 有什么区别？- [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/24.其他问题/3.第三题.md)
- 4.如何实现一个线程安全的 `NSMutableArray`? - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/24.其他问题/4.第四题.md)
- 5.如何定义一台 `iOS` 设备的唯一性? - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/24.其他问题/5.第五题.md)
- 6.如何高性能的画一个圆角？ - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/24.其他问题/6.第六题.md)
- 7.`load` 和 `Initialize` 的区别? - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/24.其他问题/7.第七题.md)
- 8.`Designated Initializer`的规则？ - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/24.其他问题/8.第八题.md)
- 9.`App` 编译过程有了解吗？ - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/24.其他问题/9.第九题.md)
- 10.`JS` 和 `Native` 交互。- [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/24.其他问题/10.第十题.md)
- 11.`atomic` 修饰的属性是绝对安全的吗？为什么？- [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/24.其他问题/11.第十一题.md)
- 12.`LoadView`方法了解吗？- [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/24.其他问题/12.第十二题.md)
- 13.说一下对 `APNS` 的认识？- [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/24.其他问题/12.第十二题.md)
- 14.实现 `isEqual` 和 `hash` 方法时要注意什么？
- 15.`UIButton` 的父类是什么？`UILabel` 的父类又是什么？- [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/24.其他问题/15.第十五题.md)
- 16.实现一个控件，可以浮在任意界面的上层并支持拖动？- [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/24.其他问题/16.第十六题.md)
- 17.`id` 和 `instanceType` 有什么区别？- [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/24.其他问题/17.第十七题.md)
- 18.说一下控制器 `View` 的生命周期，一旦收到内存警告会如何处理？- [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/24.其他问题/18.第十八题.md)
- 19.简述事件传递、事件响应机制。- [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/24.其他问题/19.第十九题.md)
- 20.说一下对 `Super` 关键字的理解。- [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/24.其他问题/20.第二十题.md)
- 21.了解 `逆变` 和 `协变` 吗？- [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/24.其他问题/21.第二十一题.md)
- 22.`@synthesize` 和 `@dynamic` 分别有什么作用？- [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/24.其他问题/22.第二十二题.md)
- 23.`Obj-C` 中的反射机制了解吗？- [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/24.其他问题/23.第二十三题.md)
- 24.如何暂停一个 `UIView` 中正在播放的动画？暂停后如何恢复？- [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/24.其他问题/24.第二十四题.md)
- 25.`App` 上有一数据列表，客户端和服务端均没有任何缓存，当服务端有数据更新时，该列表在 `wifi` 下能获取到数据，在 4G 下刷新不到，但是在 4g 环境下其他 `App` 都可以正常打开，分析其产生的原因？
-26.能不能详细的讲一下 `CALayer`?



## 25.逻辑计算题
- 1.**输出如下的计算结果** （14）

```objc
int a=5,b;
b=(++a)+(++a);
```

- 2.**不使用第三个变量，交换两个变量的值。**- [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/25.计算题/2.第二题.md)

```objc
int a = 5;
int b = 10;
```
- 3.**给出 `i`值得取值范围？** （大于或等于10000）

```objc
    __block int i = 0;

    while (i<10000) {

    dispatch_async(dispatch_get_global_queue(0, 0), ^{
        i++;
    });
}
    NSLog(@"i=%d",i);
}
```

- 4.**编码求，给定一个整数，按照十进制的编码计算包含多少个 `0`?**  - [链接](https://github.com/liberalisman/iOS-InterviewQuestion-collection/blob/master/25.计算题/4.第四题.md)

## 26.开放性问题

- 1.你最近在业余时间研究那些技术点？可不可以分享一下你的心得？
- 2.你对自己未来的职业发展有什么想法？有没有对自己做过职业规划？
- 3.和同事产生矛盾（包括意见分歧），你一般怎么解决？
- 4.能不能说一下你的业余精力都花在什么方面，或者介绍一下你的爱好？
- 5.学习技术知识通常通过哪些途径？
- 6.遇到疑难问题一般怎么解决？能不能说一个你印象颇深的技术难点，后来怎么解决的？


