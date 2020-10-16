# spring-boot-2.1.7 源码构建
1、 spring-boot 的 github [官网](https://github.com/spring-projects/spring-boot/)下载 tag 为v2.1.7
.RELEASE 的源码压缩包并且解压  
传送门
[spring-boot-2.1.7](https://github.com/spring-projects/spring-boot/tree/v2.1.7.RELEASE)   
2、 spring-boot-2.1.17.RELEASE/ 目录下执行
```
mvn clean install -DskipTests
```
即可编译成功
编译源码注意使用各个插件的版本是否适配  
- idea 2018.1  
- maven 3.5.4
- gradle 4.4.1  

**tips：** 这里可以提前下载好 gradle相关的压缩包放在：
 ```
 ~/.gradle/wrapper/dists/**/**
 ```
 


[gradle下载地址官网](https://services.gradle.org/distributions/)  
[gradle国内下载地址](https://mirrors.cloud.tencent.com/gradle/)

