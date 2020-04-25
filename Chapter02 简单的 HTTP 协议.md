# 简单的 HTTP 协议

## 2.2 通过请求和响应的交换达成通信

![](https://s1.ax1x.com/2020/04/25/JyS1Z6.png)

```
GET /index.html HTTP/1.1
Host: hackr.jp
```

起始行开头的 GET表示请求访问服务器的类型，称为方法（method）。随后的字符串 /index.htm 指明了请求访问的资源对象，也叫做请求 URI。最后的 HTTP/1.1，即 HTTP 的版本号，用来提示客户端使用的 HTTP 协议功能。

请求报文是由请求方法、请求 URI、协议版本、可选的请求首部自读那和内容实体构成的。

![](https://s1.ax1x.com/2020/04/25/JySXO1.png)