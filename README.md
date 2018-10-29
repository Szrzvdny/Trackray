
# 简介
做这个初衷只是为了实现自己在朋友圈立下的Flag，供自己在渗透测试过程中提升工作效率，方便于记录与分析。该框架使用Java语言编写，数据库使用MySQL。项目为接口式服务，可以通过调用WEB接口或Websocket等方式完成模块调用，此为最初版本。

该项目分为三个模块base、rest、module。rest与module继承自base。

# 功能
## 基本检测
* 扫描端口
* 扫描同服网站
* 扫描子域名
* 扫描C段
* 网页爬虫

## 指纹识别
* 识别WAF
* 识别CDN
* 识别CMS&框架&系统
* 识别语言

## 暴力破解(不支持初版)
* 暴力破解(21,22等)根据端口识别结果
* 扫描敏感文件(根据WEB端口&子域)

## 信息收集
* EMAIL & 手机号
* WHOIS信息
* 域名历史解析IP
* 域名在FOFA、zoomeye等平台上的结果
* 域名注册者邮箱
* 域名注册者注册的其他域名

## 攻击检测
* SQL注入检测（基于爬虫）
* XSS检测（基于爬虫）

