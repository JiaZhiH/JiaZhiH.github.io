# 2017-12-20 - 热云 TrackingIO
<!-----
layout: post
title: "热云 TrackingIO"
date: 2017.12.20
tag: iOS 总结 
--- -->

[TOC]

<!-- more -->
## 项目中证书到期，如何更新？
- [ios证书，描述文件创建以及证书过期的处理](http://www.jianshu.com/p/22fe4a78a67d)

## 接入第三方 TrackingIO 热云的问题
- 使用文档中的方法，然后和后台对接

```
// 初始化热云 SDK
[TrackingIO initWithappKey:@"450a7b4f11f4b97bed0fe81273b6cd06" withChannelId:@"_default_"];
    
// 统计用户注册数据
[TrackingIO setRegisterWithAccountID:@"sys_id"];
    
// 统计用户登陆数据
[TrackingIO setLoginWithAccountID:@"sys_id"];
    
// 测试
[TrackingIO setPrintLog:NO];
```

## iOS 微信支付拉起跳转
- [iOS版微信开发小结（微信支付，APP跳转微信公众号）](https://www.cnblogs.com/littleBit/p/5977572.html)

- [iOS微信支付步骤以及出现的问题总结（一）](https://www.jianshu.com/p/22a1ceee4d36) 

- [iOS微信支付步骤以及出现的问题总结（二）](http://www.jianshu.com/p/379c9fc64fe1)

- [iOS微信支付步骤以及出现的问题总结（三）](https://www.jianshu.com/p/1aade8e6495b)

## iOS WKWebview 使用集锦
- [iOS WKWebview 使用集锦](http://www.jianshu.com/p/3725782865a2)

- iOS WKWebView 禁止滑动方法

```
// 自适应宽度
_webView.autoresizingMask = UIViewAutoresizingFlexibleWidth;

// 自适应高度
_webView.autoresizingMask = UIViewAutoresizingFlexibleHeight;

// 禁止滚动
UIScrollView *tempView = (UIScrollView *)[self.webView.subviews objectAtIndex:0];
tempView.scrollEnabled = NO;
```

## iOS 如何往当前工程再添加一个工程
- [iOS如何往当前工程再添加一个工程](http://blog.csdn.net/kurrygo/article/details/54380517)


