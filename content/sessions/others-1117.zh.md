---
title: "云中事件驱动集成技术的最佳实践"
date: "2024-07-26 17:15:00" 
track: "others"
presenters: "武晓慧, Alan Liu"
stype: "中文演讲"
---
在过去十年中，用户对现代应用程序的需求发生了重大变化。用户希望应用程序能够实时地处理和响应他们的需求，并且始终可用。此外，应用程序还面临着从客户机到服务器传输的前所未有的数据量，包括实时数据、云计算事件、来自分布式业务系统的消息以及来自大数据源的海量数据。用户还希望新的应用程序能够快速开发和部署，并结合敏捷方法和DevOps实践。这使得开发人员使用合适的体系结构进行发展和迭代，以实现最终应用程序的快速开发和部署。

在当前Kubernetes容器开发的浪潮中，挑战在于如何有效地实现企业微服务应用程序。这包括引导企业及其最终用户将传统应用程序实践转变为事件驱动的微服务应用程序。我们将用真实的环境用户用例来说明我们的最佳实践，这些用例基于我们在该领域的世界级产品经验。包括如何从一开始就设计，主要利用kubertes平台能力，结合最新的上游项目Camel-K作为集成框架，集成现有的数据和系统，结合云原生无服务器架构、Kafka和消息中间件平台，以及采用capture data Change技术实现基于流的数据驱动架构和应用。这种方法旨在解决客户的痛点，并最终实现业务的稳定性和敏捷性。
 ### Speakers: 
 <img src="https://sessionize.com/image/e988-400o400o1-HeJc6unYc27myQAbSfqTs3.jpg" width="200" /><br>武晓慧: Redhat首席软件维护工程师, 吴晓辉，在红帽担任首席软件维护工程师，为客户提供支持，主要关注云原生开发，消息传递，集成领域。
 <br><br><img src="https://sessionize.com/image/9817-400o400o1-hQ99g9187n5ER31PcjX8u8.jpg" width="200" /><br>Alan Liu: Redhat高级解决方案架构师, 在企业级软件和Web分布式系统方面有超过16年的经验，专注于开源云计算、容器、云原生和Devops自动化，
·过程，负责产品的定义、设计、实施、测试和发布
•拥有Red Hat RHCA、CloudNative-Developer Openshift Microservice、AMQ.等技术认证
·在VMware、SAP、Adobe等多家国外知名公司担任技术团队负责人
·《企业开源实践之旅》、《开发云原生事件驱动应用》作者
 <br><br>