# 云时空 社会化商业ERP系统 Shiro框架 远程命令执行漏洞

## 漏洞描述

云时空 社会化商业ERP为 Shiro框架 ，使用了默认的密钥导致了远程命令执行漏洞

## 漏洞影响

```
云时空 社会化商业ERP系统
```

## FOFA

```
title="云时空社会化商业ERP"
```

## 漏洞复现

登录页面

![image-20220525102459840](https://typora-notes-1308934770.cos.ap-beijing.myqcloud.com/202205251024908.png)

默认密钥为

```
kPH+bIxk5D2deZiIxcaaaA==
```

![image-20220525102542474](https://typora-notes-1308934770.cos.ap-beijing.myqcloud.com/202205251025549.png)

