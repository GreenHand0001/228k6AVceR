## 前言

本项目是一个基于Spring Boot的青年公寓服务平台，旨在为广大青年提供便捷、高效的公寓租赁服务。在这里，用户可以轻松浏览到各种类型的公寓，实现线上预约看房、在线支付等功能。此项目适用于Java计算机毕业设计，具有实战意义。以下是项目的详细介绍。

## 内容介绍

本项目采用前后端分离的开发模式，后端采用Java语言和Spring Boot框架，前端采用JS、Vue和CSS3技术。项目功能包括用户注册登录、房源浏览、预约看房、在线支付等。为了提高用户的体验，我们还对页面进行了优化，使得操作更加流畅。

## 技术介绍

- 语言：Java
- 使用框架：Spring Boot
- 前端技术：JS、Vue、CSS3
- 开发工具：IDEA/Eclipse
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven: apache-maven 3.8.1-bin
- 前端环境：Node.Js 12\14\16

## 核心代码

以下是项目中的一段核心代码，展示了如何使用Spring Boot实现用户登录功能：

```java
@RestController
public class UserController {

    @Autowired
    private UserService userService;

    @PostMapping("/login")
    public Result login(@RequestBody User user) {
        String username = user.getUsername();
        String password = user.getPassword();
        return userService.login(username, password);
    }
}
```

## 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

# 项目截图

![封面图片](https://img11.360buyimg.com/ddimg/jfs/t1/317384/28/24535/124856/689de2cfF0f5c5b76/96f6ddd53d9cf10e.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/291078/17/25910/33947/689de2b9F492b0342/8e208e3bbd52439f.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/300982/28/22687/69311/689de2b9F9d357a87/d42399bad1d9009c.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/321199/13/25169/31688/689de2baFe1d3a050/0549fe83f65e6670.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/327971/8/4368/41873/689de2baF6134fbc7/5012f39103c179cf.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/327335/26/4552/54455/689de2bbF5db79b01/50b96b63d89b649c.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/317626/23/24895/50174/689de2bbFf3a2c2b7/b46a004fe2793abc.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/318261/31/24947/31261/689de2bcF1920d960/b2f64f110a7ba7c7.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/310999/8/26088/57270/689de2bcF14438400/94f20e364a74c7fb.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/312780/1/26539/59223/689de2bdF62a2d9bb/af7ac53a6b09987d.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
