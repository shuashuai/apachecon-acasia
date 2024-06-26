---
title: "Apache脉冲星星团规模控制与稳定性实践"
date: "2024-07-26 14:00:00" 
track: "messaging"
presenters: "Lin Lin"
stype: "中文演讲"
---
无论是服务云本地化还是AI模型训练，作为基础组件的消息队列的稳定性越来越重要。
上层业务的规模越来越大，对消息队列性能和吞吐量的要求也越来越高。
集群的不断扩张将使集群规模不断扩大。大集群容易出现热点、爆炸半径过大等问题，影响上层业务的稳定性。
集群规模过小，无法承载不断增长的业务流量，自然会出现资源利用率不足等问题。
华为终端云中间件团队多年来总结了一套一线生产环境的集群规模控制实践。集群大小和业务隔离控制在合理范围内，对于高流量业务，消息队列是无服务器的，服务器跨集群调度资源。
在保证集群资源利用率的前提下，不断提高消息队列的稳定性。
 ### Speakers: 
 <img src="https://sessionize.com/image/ec9e-400o400o1-KuHvwPtuLnXMT8uZBbVMQi.jpg" width="200" /><br>Lin Lin: 华为终端云消息队列技术总监, 华为SDE专家，中间件技术总监，曾就职于腾讯、蚂蚁金服
专注于中间件和基础设施，拥有10年以上相关经验，致力于构建高质量的基础设施
Apache脉冲星提交者& PMC成员
“深入理解Apache Dubbo与实战”“深入解析Apache Pulsar”作者
 <br><br>