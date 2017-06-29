## Keycloak
此项目主要是用来探究`keycloak`的。从[keycloak的官网](http://www.keycloak.org/)介绍来看，它是一个开源的具有认证、访问控制现代应用服务的框架。
为应用程序添加身份验证最小化，无需处理存储用户或验证用户，是开箱即用的。

## 缘起
看到了这篇[使用 Keyclock 轻松保护 Spring Boot 应用程序](https://www.oschina.net/translate/easily-secure-your-spring-boot-applications-with-k?lang=chs&page=1#)，于是想动手实践体验下。

To start the app from the command line:
```

mvn clean spring-boot:run

```

# Part 1 - Create a Spring Boot app and Keycloak support
This is on [Master branch](https://github.com/elegance/spring-keycloak/tree/master)