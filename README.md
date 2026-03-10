## 前言

欢迎来到我们的基于微信小程序的校医务室健康服务系统项目。本项目旨在为在校师生提供一个便捷的健康咨询和服务平台，实现线上挂号、咨询、就诊记录查询等功能。以下是项目的详细介绍。

## 内容介绍

本项目分为前后端两部分，前端采用微信小程序，后端采用Spring Boot技术栈。通过微信小程序，用户可以轻松实现线上挂号、预约就诊、查看就诊记录等功能。后端处理业务逻辑，与数据库进行交互，为前端提供数据支持。

## 技术介绍

- **语言：Java**
- **使用框架：Spring Boot、Spring、Spring MVC、MyBatis**
- **前端技术：JavaScript、Vue.js、CSS3、Uniapp**
- **开发工具：IDEA/Eclipse，Uniapp**
- **数据库：MySQL 5.7/8.0**
- **数据库管理工具：phpstudy/Navicat**
- **JDK版本：jdk1.8**
- **Maven: apache-maven 3.8.1-bin**
- **前端环境：Node.js 12\14\16**

## 核心代码

以下是项目中的部分核心代码，以MyBatis配置为例：

```java
@Mapper
public interface UserMapper {
    @Select("SELECT * FROM user WHERE id = #{id}")
    User selectUserById(@Param("id") int id);

    @Insert("INSERT INTO user(name, password) VALUES(#{name}, #{password})")
    int insertUser(@Param("name") String name, @Param("password") String password);
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

## 项目截图
![封面图片](https://img13.360buyimg.com/ddimg/jfs/t1/324047/22/19988/76935/68c64a98F582e1039/d1478360b317e526.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/346321/6/3319/9310/68c64a70F1fc4edfc/4cfa6d988c57e7c0.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/329431/34/13095/8353/68c64a70F1802e056/242af8de7ed0df4a.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/294083/37/24706/26748/68c64a71F9416a2cb/b98d5e7e183d97f1.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/338081/23/10498/24192/68c64a71Ffae95353/4088873247e3b691.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/338089/21/10437/12679/68c64a72Fcf93fd91/d2ca27abf6efc2f3.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/348135/20/3062/26773/68c64a72F0cd4e8a9/7b68b1218807041c.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/334827/23/13239/26901/68c64a72Fbd41df52/ff061582a0f9c1d7.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/342212/3/3126/27693/68c64a73Ff38315d9/55bdba0ce6518bbf.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/340756/26/10605/26931/68c64a73Fdf7a57b8/403f76844ce6da19.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
