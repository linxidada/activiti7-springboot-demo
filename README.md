# 注意事项：

## 1.版本问题
### 7.0.0GA
```text
All these Spring Boot Starters are based on Spring Boot 2.1.2 and 
Spring Cloud Greenwich RELEASE and all the artifacts are compiled to work with JDK11.
仅支持jdk11
```
### 7.0.0SR1
```text
修正了上一版本对jdk8的支持，可以使用
```

## 2.数据库生成
```java
activiti.cfg.xml (resources中)
Initialize.java (test目录中)
```
## 3.SpringSecurity
```java
DemoApplicationConfiguration.java
SecurityUtil.java
//这两个类从Activiti官方的example中复制即可，专门为了security准备的
```