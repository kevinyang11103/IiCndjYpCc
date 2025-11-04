# 西安旅游系统

## 前言

西安旅游系统是一个基于Java语言和Spring Boot框架的实战项目，用于实现西安地区旅游信息的管理和展示。本项目适用于计算机专业学生的毕业设计，也可供初学者和开发者参考学习。本文将详细介绍该项目的相关内容，包括技术栈、核心代码等。

## 内容介绍

本项目主要包括以下功能模块：

1. 用户模块：实现用户注册、登录、修改资料等功能。
2. 旅游信息模块：展示西安地区的旅游景点、美食、住宿等信息。
3. 景点评论模块：实现用户对景点进行评论、评分等功能。
4. 后台管理模块：实现对用户、景点、评论等信息的增删改查操作。

项目采用前后端分离的架构，前端使用Vue框架，后端使用Spring Boot框架，易于维护和扩展。

## 技术介绍

- 语言：Java
- 使用框架：Spring Boot
- 前端技术：JS、Vue、css3
- 开发工具：IDEA/Eclipse
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven: apache-maven 3.8.1-bin
- 前端环境：Node.Js 12\14\16

## 核心代码

以下是本项目中的一个核心代码片段，展示了如何实现景点信息的查询功能：

```java
// 使用Spring Data JPA实现查询
public interface ScenicRepository extends JpaRepository<Scenic, Integer> {
    // 根据景点名称模糊查询
    List<Scenic> findByNameContaining(String name);
}

// 在Service层调用Repository查询景点信息
public List<Scenic> findScenicByName(String name) {
    return scenicRepository.findByNameContaining(name);
}
```

## 免费源码获取

```
8000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

# 项目截图

![封面图片](https://img13.360buyimg.com/ddimg/jfs/t1/308421/2/26469/244051/689e0ed8F8e7e7ff4/8c27e751ff7dc3f1.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/312517/36/26282/22209/689e0eb6Fd49d79c7/dd726be2f7b4900d.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/316725/21/24735/219453/689e0eb9F03d4ca42/f5695311e820ef60.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/286578/9/23960/60655/689e0ebbF5e06f505/7155aad54c386b75.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/319963/38/24699/18777/689e0ebcF7775aca4/42f38e725eaac747.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/309531/12/20079/63751/689e0ebdF0f9f5f2a/e6385946824f1a35.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/323924/8/4629/22815/689e0ebeF1e6cf658/00d82103c29fc0fd.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/328483/39/4616/26904/689e0ebeFbf8182b9/f7554a8066b9599d.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/312500/15/26192/21211/689e0ebfFb78fbea5/7c69db704074dd6a.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/311589/1/26848/30803/689e0ebfF882b9255/bdc12a95cd3a5230.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
