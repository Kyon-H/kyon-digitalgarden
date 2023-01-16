---
{"dg-publish":true,"permalink":"/acunetix-api/readme/"}
---

# Acunetix11-API-Documentation

* Acunetix11伪API,非官方API文档。官方API需要 Enterprise edition licenses才能获取到。
* 先更一部分，有时间慢慢更。有问题提issue或者pr。

## 获取API-KEY
Administrator--Profile--API Key

## 环境设置:

### Header设置:

```
X-Auth: API-KEY
Content-type: application/json; charset=utf8
```

### 接口设置
1. 传参内容均为Json格式
2. 接口均为https

## 文档目录(Contents)

* 1 . [Dashboard接口](Dashboard.md)
* 2 . [Targets接口](Acunetix-API/Document/Targets/main.md)
    
    * a). [General设置](scan.md)
    * b). [Crawl设置](scan.md)
    * c). [HTTP设置](scan.md)
    * d). [Advanced设置](scan.md)
* 3 . [Scans接口](Acunetix-API/Document/Scans/main.md)
* 4 . [Vulnerabilities接口](Acunetix-API/Document/Vulnerabilities/main.md)
* 5 . [Reports接口](Acunetix-API/Document/Reports/main.md)
     

