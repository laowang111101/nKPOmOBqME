# 前言

欢迎来到本项目的 Gitee 仓库！这是一个基于 Java 和 Spring Boot 框架的宿舍管理系统，适用于毕业设计和实战项目。在这里，您将找到完整的源码、文档报告以及代码讲解，助您更好地了解和掌握该项目。

# 内容介绍

本项目是一个宿舍管理系统，主要实现了学生宿舍的分配、管理、查询等功能。系统采用前后端分离的设计，前端负责展示和交互，后端处理业务逻辑和数据库操作。通过本项目，您可以学习到 Java 开发、Spring Boot 框架、前端技术以及数据库管理等知识。

# 技术介绍

## 语言：Java
## 使用框架：Spring Boot
## 前端技术：JS、Vue、css3
## 开发工具：IDEA/Eclipse
## 数据库：MySQL 5.7/8.0
## 数据库管理工具：phpstudy/Navicat
## JDK版本：jdk1.8
## Maven: apache-maven 3.8.1-bin
## 前端环境：Node.Js 12\14\16

# 核心代码

以下是一段关于宿舍管理的核心代码：

```java
@RestController
@RequestMapping("/dormitory")
public class DormitoryController {

    @Autowired
    private DormitoryService dormitoryService;

    @GetMapping("/list")
    public ResponseEntity<List<Dormitory>> list() {
        List<Dormitory> dormitoryList = dormitoryService.list();
        return ResponseEntity.ok(dormitoryList);
    }

    @PostMapping("/add")
    public ResponseEntity<Void> add(@RequestBody Dormitory dormitory) {
        dormitoryService.save(dormitory);
        return ResponseEntity.ok().build();
    }

    @PutMapping("/update")
    public ResponseEntity<Void> update(@RequestBody Dormitory dormitory) {
        dormitoryService.update(dormitory);
        return ResponseEntity.ok().build();
    }

    @DeleteMapping("/delete/{id}")
    public ResponseEntity<Void> delete(@PathVariable("id") Long id) {
        dormitoryService.delete(id);
        return ResponseEntity.ok().build();
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

![封面图片](https://img10.360buyimg.com/ddimg/jfs/t1/311564/33/26743/145981/689ec09fF16d20373/441d7e03024ba4d8.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/314217/8/26728/17420/689ec080Fc50aea8e/35af7db74b64725f.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/292361/28/25644/96202/689ec082F9f5f48e3/7dd151b59cab65a5.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/317409/40/24674/75015/689ec083Fc96249ce/d212205adc2b9d72.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/313803/28/26470/23545/689ec083Fa52b6337/5ddbaafbc5476c32.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/326356/37/4794/24251/689ec084Fef548349/32b40d4ac6779ac9.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/320319/17/25143/26076/689ec084Ff934a43f/57f9d57e7d67d4e2.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/307054/29/26519/26147/689ec085Fb7166458/e21d023974ed777b.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/312013/16/26636/65114/689ec085F64f94659/edac401167c608b0.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/326019/5/4864/23155/689ec085F581f39bc/408af10d587b2051.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
