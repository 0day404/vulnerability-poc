# 绿盟 BAS日志数据安全性分析系统 accountmanage 未授权访问漏洞

## 漏洞描述

绿盟 BAS日志数据安全性分析系统存在未授权访问漏洞，通过漏洞可以添加任意账户登录平台获取敏感信息

## 漏洞影响

```
绿盟 BAS日志数据安全性分析系统
```

## FOFA

```
body="WebApi/encrypt/js-sha1/build/sha1.min.js"
```

## 漏洞复现

登录页面

![image-20220525145937586](https://typora-notes-1308934770.cos.ap-beijing.myqcloud.com/202205251459725.png)

未授权页面

```
/accountmanage/index
```

![](https://typora-notes-1308934770.cos.ap-beijing.myqcloud.com/202205251500626.png)

添加用户并登录

![](https://typora-notes-1308934770.cos.ap-beijing.myqcloud.com/202205251500966.png)

使用账户登录后台

![](https://typora-notes-1308934770.cos.ap-beijing.myqcloud.com/202205251500218.png)