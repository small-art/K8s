Kubernetes  k8s组件

```
Infrastructure as a Service 基础设施服务
platform as a service   平台
Software as a Service   软件



容器的集群化

ip加端口进行集群 管理

滚动更新回滚

borg 

轻量级：消耗的资源小
开源
弹性伸缩
负载均衡 ：ipvs

基础 什么是pod 控制器类型 k8s 网络通讯模式
k8s 构建 
k8s 集群


资源清单
	编写 Pod 掌握Pod生命周期
Pod 控制器类型 掌握各种控制器的特点以及使用定义方式


go语言

访问入口
负载均衡的方案

设置服务发现：让Pod控制器去访问

服务发现
	Service 掌握 syc 原理及构建方式
    
服务分类
	有状态服务：DBMS
	无状态服务: Lvs APACHE
	
存储：掌握多种存储类型的特点 并且能够在不同环境中选择合适的存储方案(有自己的见解);

调度器： 掌握调度器原理  能够根据要求把Pod 定义到想要的节点上运行

configMap
value

集群安全机制
安全：集群的认证 鉴权 访问控制 原理及其流程
	
HELM：Linux yum  掌握原理  模板定义 部署一些常用的插件

运维
k8s源码修改 1年更新一次
k8s高可用构建

达到证书可用的10年
 

etcd 可信赖的分布式键值存储服务，能够为整个分布式集群存储一些关键数据，协助分布式集群正常运转

kube let
kube proxy


k8s架构
	api server
	
APISERVER:所有 服务访问统一入口
CrontrollerManager ： 维持副本期望数目
Scheduler ： 负责介绍任务，选择合适的节点进行分配任务
ETCD ： 键值对数据库 存储k8s 集群所有重要信息(持久化)
	doker 容器中运行
Kubelet : 直接跟容器引擎交互实现容器的生命周期管理
Kube-proxy: 负责写入规则至 IPTABLES 、IPVS实现服务映射访问的
DASHBOARD：给k8s 集群提供 一个 B/S 结构访问体系
INGRESS CONTROLLER ： 官方只能实现四层代理，ingress 可以实现七层代理
FEDERATION : 提供一个可以跨集群中心多K8S统一管理功能
PROMETHEUS: 提供k8s集群的监控能力
ELK：提供k8s集群日志统一分析介入平台




firewall

internet

coreDNS ：可以为集群中的SVC创建一个域名IP的对应关系解析
	访问Pod 时



Pod 概念
	自主式 Pod
	控制器管理的 Pod
	

网络通讯方式



service 通过标签找到对应的pod 进行统一管理
ip 加上端口
r2




```

Apache：Messos 分布式资源管理框架

Docker：swarm 