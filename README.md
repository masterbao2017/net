# net
# 个人毕设作品。。。。。。正在完善。目前初步完成。。。

net是一个基于Reactor 模式的现代化C++11网络库。

自带TCP协议的异步非阻塞式的服务器和客户端库。

实现上深度借鉴[muduo]和[evpp]两个开源网络库。

性能上没太多测试，不过个人感觉性能还不错。。。

没啥第三方库依赖，只要支持c++11就行。。。

需要的linux版本没测试。。。有时间再说。。。


# 特性

现代版的C++11接口

非阻塞异步接口都是C++11的functional形式的回调仿函数

非阻塞纯异步多线程TCP服务器/客户端

单核环境支持

线程安全

线程安全的退出，重启

客户端断线自动重连

服务端可同时监听多个ip/port
