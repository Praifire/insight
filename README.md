
* 安全知识库管理

安全知识库管理：对安全知识、管理制度进行集中存放、线上学习、安全培训、知识传承等。


## 部署指南

[![Python 2.7](https://img.shields.io/badge/python-2.7-green.svg)](https://www.python.org/)
[![MySQL 5.6.27](https://img.shields.io/badge/mysql-5.6.27-orange.svg)](https://www.mysql.com)
[![Flask 0.11.1](https://img.shields.io/badge/flask-0.11.1-yellow.svg)](https://github.com/pallets/flask)
[![Docker 1.13.0](https://img.shields.io/badge/docker-1.13.0-blue.svg)](https://www.docker.com/)

目前只编写了docker部署指南，建议docker部署，详细请见：

[docker部署指南](docs/install.md)

## 使用指南

平台用户分为以下5种角色：
* 匿名用户：公司内部未登录用户
* 普通用户：普通登录用户，指公司研发、业务、产品经理等。
* 安全人员：安全部门进行漏洞测试、提交、跟踪修复的人员等。
* 安全管理员：安全部门对漏洞进行审核的管理人员。
* 超级管理员：最高权限账号，对用户的角色进行分配。

以上5种角色对应的使用文档请见：

[使用指南-匿名用户篇](docs/anonymous_user.md)

[使用指南-普通用户篇](docs/normal_user.md)

[使用指南-安全人员篇](docs/sec_user.md)

[使用指南-安全管理员篇](docs/sec_manager.md)

[使用指南-超级管理员篇](docs/super_user.md)

## 设计理念

应用安全管理从应用资产的风险评估开始，公司资产一旦多了之后，往往会面临资产不清晰、找不到负责人、漏洞持续跟踪成本高昂、安全知识难以沉淀、高频风险没有数据支持、不能有的放矢的解决核心问题，另外风险量化也是难题。

![](docs/pics/安全管理痛点.png)

应用安全管理体系设计中，风险治理一般过程如下

![](docs/pics/安全管理体系.png)

基于上述风险治理的实际需求，洞察应运而生。

## 平台亮点

使用洞察系统后，我们实现了以下目标，请看大图：

### 历史漏洞一目了然

![](docs/pics/历史漏洞一目了然.png)

### 漏洞跟踪有条不紊

![](docs/pics/漏洞跟踪有条不紊.png)

### 学习案例信手拈来

![](docs/pics/学习案例信手拈来.png)

### 威胁风险有理有据

![](docs/pics/威胁风险有理有据.png)

### 安全要求精准管控

![](docs/pics/安全要求精准管控.png)

### 量化数字实时知晓

![](docs/pics/量化数字实时知晓.png)

欢迎安全小伙伴使用、交流、fork、star、转发。

也欢迎安全小伙伴在使用洞察过程中和我们多多交流，扫描下方二维码，关注宜信安全应急响应中心公众号，回复“自己的微信号+洞察”，我们的运营小姐姐九色鹿会拉你进群讨论。

![](docs/pics/CESRC.jpeg)
