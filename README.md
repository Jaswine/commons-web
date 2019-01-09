# commons-web
> JavaWeb项目常用工具类
在开发`Web`项目过程中，有很多类是可以抽取出来做工具类；还有很多自定义的类是常常被不同项目使用到的。所以创建一个专门为`Web`项目依赖的包很有必要。


## 使用方法
- **使用Maven私服**

在`pom.xml`文件中加入私服地址

```xml
<repository>
    <id>jaswine-maven-repo</id>
    <url>https://raw.githubusercontent.com/jaswine/Maven-Repo/master/repo</url>
</repository>
```

导入`commons-web`依赖包

```xml
<dependency>
    <groupId>com.jaswine</groupId>
    <artifactId>commons-web</artifactId>
    <version>${web.version}</version>
</dependency>
```

## 更新日志
- 2018年3月28日
