# 前言

本项目是一个基于Java语言的Spring Boot框架开发的毕业设计项目，旨在实现对当代中国获奖知名作家信息的管理。该项目不仅涉及前端的展示，还包括后端的数据处理，是一个完整的实战项目。下面将详细介绍本项目的相关内容。

# 内容介绍

本项目主要分为前端展示和后端数据处理两部分。前端部分采用JS、Vue、CSS3等技术实现用户与系统的交互；后端部分则主要负责知名作家信息的存储、查询、修改等功能。通过本项目的实现，用户可以方便地了解到我国获奖的知名作家及其作品信息。

# 技术介绍

- 语言：Java
- 使用框架：Spring Boot
- 前端技术：JS、Vue、CSS3
- 开发工具：IDEA/Eclipse
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven：apache-maven 3.8.1-bin
- 前端环境：Node.Js 12\14\16

# 核心代码

以下是项目中的一个核心代码片段，展示了如何使用Spring Boot与MySQL数据库进行交互：

```java
// 引入Spring Boot相关依赖
import org.springframework.beans.factory.annotation.Autowired;
import org.springframework.web.bind.annotation.GetMapping;
import org.springframework.web.bind.annotation.RestController;

//作家信息实体类
class Writer {
    private int id;
    private String name;
    private String award;
    // getter和setter方法省略
}

//作家信息控制器
@RestController
public class WriterController {

    @Autowired
    private WriterRepository writerRepository;

    @GetMapping("/writers")
    public List<Writer> getAllWriters() {
        return writerRepository.findAll();
    }
}
```

# 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

# 项目截图

![封面图片](https://img14.360buyimg.com/ddimg/jfs/t1/290165/30/25091/166736/689e9eb1F37f0accf/e5832d07283051b5.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/315386/11/25544/118409/689e9e91F4824e993/a28eb2eb55612b87.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/327509/7/4727/26356/689e9e92F71545029/69ddfbe1107c373e.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/318133/7/24848/57966/689e9e99Fd161519c/910b23d964c0999e.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/319499/27/24659/16401/689e9e9bF5cdf72fa/24148f12a5ff3c99.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
