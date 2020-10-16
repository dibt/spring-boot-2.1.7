# spring-boot-2.1.17
1、 spring-boot 的 github [官网](https://github.com/spring-projects/spring-boot/)下载 tag 为v2.1.17
.RELEASE 的源码压缩包并且解压  
传送门
[spring-boot-2.1.17](https://github.com/spring-projects/spring-boot/tree/v2.1.17.RELEASE)   
2、 注释掉 spring-boot-2.1.17.RELEASE/spring-boot-project/spring-boot-tools/pom.xml 下的
```
<module>spring-boot-gradle-plugin</module>
```
3、 spring-boot-2.1.17.RELEASE/spring-boot-project/ 目录下执行
```
mvn clean install -DskipTests
```
即可编译成功

