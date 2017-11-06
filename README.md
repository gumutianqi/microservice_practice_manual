# Microservice Practice manual 微服务实践开发手册

微服务开始被广为人知，并且普及起来，应该是在2016年，SpringBoot + SpringCloud 的出现也进一步推动了微服务架构的发展速度；本书为 LarryKoo 在自2016年开始对微服务架构的实践当中积累的经验和日常记录，故名为：《微服务实践开发手册》；

---

更新时间：2017-08-29

本书所有内容皆围绕 SpringBoot 、SpringCloud 展开微服务实践；

当前 SpringBoot 最新版本为：`1.5.8`版本，Maven 依赖如下：

```
<parent>
    <groupId>org.springframework.boot</groupId>
    <artifactId>spring-boot-starter-parent</artifactId>
    <version>1.5.8.RELEASE</version>
</parent>
<dependencies>
    <dependency>
        <groupId>org.springframework.boot</groupId>
        <artifactId>spring-boot-starter-web</artifactId>
    </dependency>
</dependencies>
```

当前 SpringCloud 最新版本为：Dalston.SR2，适配 SpringBoot 1.5.2 版本，Maven 依赖如下：

```
<parent>
    <groupId>org.springframework.boot</groupId>
    <artifactId>spring-boot-starter-parent</artifactId>
    <version>1.5.2.RELEASE</version>
</parent>
<dependencyManagement>
    <dependencies>
        <dependency>
            <groupId>org.springframework.cloud</groupId>
            <artifactId>spring-cloud-dependencies</artifactId>
            <version>Dalston.SR2</version>
            <type>pom</type>
            <scope>import</scope>
        </dependency>
    </dependencies>
</dependencyManagement>
<dependencies>
    <dependency>
        <groupId></groupId>
        <artifactId>spring-cloud-starter-config</artifactId>
    </dependency>
    <dependency>
        <groupId></groupId>
        <artifactId>spring-cloud-starter-eureka</artifactId>
    </dependency>
</dependencies>
```



