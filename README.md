# note-network



[comment]: <> (+ [协议层次]&#40;notes/model.md&#41;)

[comment]: <> (+ [应用层]&#40;notes/application.md&#41;)

[comment]: <> (+ [传输层]&#40;notes/transport.md&#41;)

[comment]: <> (+ [网络层]&#40;notes/network.md&#41;)

[comment]: <> (+ [数据链路层]&#40;notes/data_link.md&#41;)

[comment]: <> (+ [物理层]&#40;notes/physical.md&#41;)


- [x] [协议层次](notes/model.md)
- [x] [应用层](notes/application.md)
- [ ] [传输层](notes/transport.md)
- [ ] [网络层](notes/network.md)
- [ ] [数据链路层](notes/data_link.md)
- [ ] [物理层](notes/physical.md)

+ [协议层次](notes/model.md)
    + [模型介绍](notes/model.md#模型介绍)
        + [OSI 七层模型](notes/model.md#osi-七层模型)
        + [TCP/IP 参考模型](notes/model.md#tcpip-参考模型)
        + [TCP/IP 五层参考模型](notes/model.md#tcpip-五层参考模型)
    + [FQA](notes/model.md#fqa)
        + [OSI 模型和 TCP/IP 模型异同比较](notes/model.md#osi-模型和-tcpip-模型异同比较)
        + [OSI 和 TCP/IP 协议之间的对应关系](notes/model.md#osi-和-tcpip-协议之间的对应关系)
        + [为什么 TCP/IP 去除了表示层和会话层](notes/model.md#为什么-tcpip-去除了表示层和会话层)
        + [数据如何在各层之间传输(数据的封装过程)](notes/model.md#数据如何在各层之间传输数据的封装过程)
+ [应用层](notes/application.md)
    + [基本概念](notes/application.md#基本概念)
        + [HTTP 头部](notes/application.md#http-头部)
        + [HTTP 方法](notes/application.md#http-方法)
        + [状态码](notes/application.md#状态码)
        + [HTTP 与 HTTPs 的工作方式(建立连接的过程)](notes/application.md#http-与-https-的工作方式建立连接的过程)
        + [HTTP/3](notes/application.md#http3)
        + [socket 套接字](notes/application.md#socket-套接字)
    + [FQA](notes/application.md#fqa)
        + [Keep-Alive 和非 Keep-Alive 区别，对服务器性能有影响吗](notes/application.md#keep-alive-和非-keep-alive-区别对服务器性能有影响吗)
        + [HTTP 长连接短连接使用场景是什么](notes/application.md#http-长连接短连接使用场景是什么)
        + [怎么知道 HTTP 的报文长度](notes/application.md#怎么知道-http-的报文长度)
        + [GET 和 POST 的区别](notes/application.md#get-和-post-的区别)
        + [GET 的长度限制是多少](notes/application.md#get-的长度限制是多少)
        + [HTTPS 和 HTTP 的区别](notes/application.md#https-和-http-的区别)
        + [HTTPS 的加密方式](notes/application.md#https-的加密方式)
        + [客户端为什么信任第三方证书](notes/application.md#客户端为什么信任第三方证书)
        + [状态码 301 和 302 的区别](notes/application.md#状态码-301-和-302-的区别)
        + [HTTP 是不保存状态的协议,如何保存用户状态](notes/application.md#http-是不保存状态的协议如何保存用户状态)
        + [HTTP/1.1 和 HTTP/1.0 的区别](notes/application.md#http11-和-http10-的区别)
        + [HTTP/1.X 和 HTTP/2.0 的区别](notes/application.md#http1x-和-http20-的区别)
        + [网页解析全过程(用户输入网址到显示对应页面的全过程)](notes/application.md#网页解析全过程用户输入网址到显示对应页面的全过程)