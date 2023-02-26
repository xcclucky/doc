# doc
文档

环境
IntelliJ IDEA 2022.1.2 (Ultimate Edition)
org.springframework.boot' version '2.5.0'
gradle-7.6.1
java 17
MySQL 8.0.25


注意点
Spring Boot 3.0 最低只支持java17,（版本管理器默认也换成了 Gradle，Gradle 支持 7.3网上）


问题：
无效的源发行版 17
gradle编译使用了java8，修改为java17就好![image](https://user-images.githubusercontent.com/126364300/221388399-07f91e2d-80e2-4c5c-8ebe-7118c3e38f6b.png)


查询MySQL版本号 
SELECT @@version;
