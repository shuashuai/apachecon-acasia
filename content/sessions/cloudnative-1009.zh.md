---
title: "Seata的云原生演进:从部署到未来可能性的路线图"
date: "2024-07-28 15:00:00" 
track: "cloudnative"
presenters: "尹祥琨"
stype: "中文演讲"
---
从单片架构到微服务，从独立数据库到分布式数据库系统的演变，已经成为现代服务交付中无可争议的现实。应用程序现在被分解为多个可独立部署的服务，需要服务之间的远程协作来完成事务。这种转变给分布式事务管理带来了复杂性，需要的解决方案不仅要高效，而且要适应不断变化的云原生环境。

讨论将包括Seata如何通过适应云原生趋势进入Seata 2.0。特别是，Raft共识机制的引入允许分布式事务处理，而不依赖于传统的数据库和消息队列，而是使用文件存储和集群间一致性。此外，使用Seata的K8s Operator作为管理和自动化Seata服务部署的一种手段，强调了Seata 2.0的云原生适应性。

展望未来，该演讲将探讨Seata在云原生领域的进一步工作，包括通过控制台管理集群配置，以及通过扩展Seata -ctl增强集群操作。这是迈向全面的云原生分布式事务管理解决方案的关键一步。本次演讲不仅将展示Seata目前的成就，还将为其发展提供清晰的路线图，说明它如何适应并引领微服务架构的未来趋势。
 ### Speakers: 
 <img src="https://sessionize.com/image/91bb-400o400o1-nKKKZUWXVJ5XYnXihK1tQW.jpg" width="200" /><br>尹祥琨: 清华大学, 我叫尹祥琨，目前是清华大学软件工程专业的一名硕士研究生。由于对开源项目非常感兴趣，我积极地为几个社区做出了贡献，并且最近被授予Apache Seata(孵化)中的Committer角色。在Seata，我做出了一些重大贡献，领导了几个关键项目，如Seata操作器、前端设计、Seata -go Saga实现。
 <br><br>