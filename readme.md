# 基础库
- [fmt](https://github.com/fmtlib/fmt)。fmt是一个C++的格式化库，它能打印出漂亮的、易读的、易于理解的格式化输出。

- [poco]()。Poco是一个C++的跨平台开发框架，它提供了各种开发人员所需的各种功能，如网络、数据库、XML、加密、文件系统、线程、计时器。

# 模型部署
- [FastDeploy](https://github.com/PaddlePaddle/FastDeploy/tree/develop)。百度飞浆的模型部署工具。

- [nndeploy](https://github.com/nndeploy/nndeploy)。nndeploy是一款模型端到端部署框架。以多端推理以及基于有向无环图模型部署为基础，致力为用户提供跨平台、简单易用、高性能的模型部署体验。

# 网络通信
- [nanomsg](https://github.com/nanomsg/nanomsg)。nanomsg 库是一个简单且高性能的实现，它实现了几种“可扩展性协议”。这些可扩展性协议是轻量级的消息传递协议，可以用来解决一系列非常常见的消息模式，例如请求/响应、发布/订阅、调查者/应答者等。这些协议可以在多种传输层之上运行，例如 TCP、UNIX 套接字，甚至是 WebSocket。

- [nng](https://github.com/nanomsg/nng)。NNG（就像它的前身 nanomsg 以及某种程度上的 ZeroMQ 一样）是一个轻量级、无代理的库，它提供了一个简单的 API 来解决常见的反复出现的消息传递问题，例如发布/订阅、RPC 风格的请求/响应，或是服务发现。该 API 使程序员不必担心诸如连接管理、重试以及其他常见考虑等细节，从而让他们能够专注于应用程序本身而不是底层基础设施。
NNG 是用 C 语言实现的，仅需 C99 和 CMake 即可构建。它可以构建为共享库或静态库，并且易于嵌入到其他项目中。此外，NNG 的设计使得将其移植到新的平台变得容易，即使你的平台尚未得到支持。

- [ZeroMQ](https://github.com/zeromq/libzmq)。ZeroMQ是一个开源的、跨平台的、可靠的、可伸缩的、面向消息的、异步的消息传递库。

# 事件循环
- [uvw](https://github.com/skypjack/uvw)。这是一个现代C++中的无头文件（header-only）、基于事件的小型且易于使用的libuv封装库 —— 现在也可作为共享库或静态库提供！