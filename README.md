# Dockin - 生产级云原生容器平台

## 项目介绍
Dockin 是微众银行开源的生产级容器平台，提供了一整套私有云容器化的落地方案。涵盖Kubernetes集群管理、应用管理、网络、运维工具、开放 API 等组件，用户可以自由搭配使用，定制自己的容器平台。
开源版本从我们生产环境中剥离出来，经过了金融级生产环境的严格验证，是私有化部署的较好方案。

## 开源组件

一款支持固定IP的网络插件（Dockin-CNI）
基于 kubernetes 的 CNI 网络插件，支持固定IP，支持多网卡

https://github.com/WeBankFinTech/Dockin-CNI

https://gitee.com/WeBank/Dockin-CNI

一套安全的运维编排服务（Dockin-Ops）
Dockin 运维管理系统是安全的运维管理服务，优化 exec 执行性能，支持命令权限管理。

https://github.com/WeBankFinTech/Dockin-Ops

https://gitee.com/WeBank/Dockin-Ops

一套离线Kubernetes集群安装器（Dockin-Installer）
Dockin 平台安装器，快速部署Docker、高可用 kubernetes 集群、ETCD 集群，生产级参数调优。全离线安装，不需要连外网，支持十年的证书续订、ETCD备份恢复

https://github.com/WeBankFinTech/Dockin-Installer

https://gitee.com/WeBank/Dockin-Installer

一款应用资源管理系统（Dockin-RM）
Dockin 容器项目资源管理器，是应用定义和容器实例管理的核心模块，提供容器分配、回收、查询等功能。

https://github.com/WeBankFinTech/Dockin-RM

https://gitee.com/WeBank/Dockin-RM


## Dockin待开源组件
* 静态应用管理方案
* 镜像管理系统
* 平台管理台
* 高可用监控服务
* 统一API网关
* 智能调度系统
* 通用Operator套件

## RoadMap

https://github.com/WeBankFinTech/Dockin/blob/main/RoadMap.md

## 社区通讯


## 社区活动

###  Dockin 社区有奖征文

为了 Dockin 开源项目更好的运转，同时回馈开源社区，社区推出有奖征文活动！欢迎大家投递实践经验，给社区用户，更广泛的开发者提供借鉴。经验输出也可以帮助到你系统沉淀自有项目，梳理工作思路，也能够帮助你的技术博客做宣传。优秀的实践案例将有机会邀请参与项目社区技术会议分享，赶快来参与吧。

详情请戳：https://mp.weixin.qq.com/s/-D0Z9ICw_FuciKVZ7P81Ow

