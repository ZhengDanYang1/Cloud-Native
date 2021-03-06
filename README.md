# 中国云原生技术生态

## 云应用定义与开发流程

### 数据库

|     项目名称     |                           项目LOGO                           |                           项目概述                           | 是否开源 | 主导公司 |              Github地址              |
| :--------------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :------: | :------: | :----------------------------------: |
|  Tanzu  GemFire  | ![NATS](https://github.com/ZhengDanYang1/Cloud-Native/raw/master/pic/Tanzu.png) | VMware  Tanzu  GemFire是一个分布式的，在内存中的键值存储，执行读写操作在惊人的速度。它提供了高可用性的并行消息队列、持续可用性和事件驱动的架构，可以动态伸缩，而不需要停机。随着用户对数据大小的需求增加，以支持高性能实时应用程序，轻松地线性扩展。 |          |  VMware  |                                      |
| Tanzu  Greenplum | ![NATS](https://github.com/ZhengDanYang1/Cloud-Native/raw/master/pic/Tanzu.png) | Greenplum被设计用于在任何场所、公共和私有云以及现代的容器化环境(如kubernet)中运行，以便更容易安装、操作和升级。Greenplum是基于PostgreSQL和Greenplum数据库项目开发的。它提供了可选的用例特定扩展，如用于地理空间分析的PostGIS，以及用于文档提取、搜索和自然语言处理的GPText(基于Apache  Tika和Apache Solr)。这些都是预先集成的。用户可以从充满活力的开发人员社区的贡献中获益，而不是依赖昂贵的专有数据库。 |    是    |  VMware  | https://github.com/greenplum-db/gpdb |

### 消息和Streaming

| 项目名称 |                           项目LOGO                           |                           项目概述                           | 是否开源 | 主导公司 |         Github地址         |
| :------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :------: | :------: | :------------------------: |
|   NATS   | ![NATS](https://github.com/ZhengDanYang1/Cloud-Native/raw/master/pic/NATS.png) | NATS是一种简单、安全、高性能的通信系统，用于数字系统、服务和设备。NATS有超过30种客户端语言实现，它的服务端可以运行在内部，云，边缘，甚至树莓派。NATS可以保证和简化现代分布式系统的设计和操作。 |    是    | Synadia  | https://github.com/nats-io |

### 应用定义与镜像制作

|         项目名称          |                           项目LOGO                           |                           项目概述                           | 是否开源 | 主导公司 |            Github地址            |
| :-----------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :------: | :------: | :------------------------------: |
|   Tanzu  Build Service    | ![NATS](https://github.com/ZhengDanYang1/Cloud-Native/raw/master/pic/Tanzu.png) | Tanzu  Build Service使用开源Cloud Native  Buildpacks项目将应用程序源代码转换为容器映像。生成服务执行与现代容器标准一致的可复制生成，并且使图像保持最新状态。它通过将kubernetes基础架构与kpack结合使用来管理映像生命周期。 |          |  VMware  |                                  |
| Tanzu Application Catalog | ![NATS](https://github.com/ZhengDanYang1/Cloud-Native/raw/master/pic/Tanzu.png) | VMware  Tanzu Application Catalog是一项结合了内容和工具的服务，允许IT组织在多个平台上使用根据其特定要求定制的开源和商业应用程序。 |          |  VMware  |                                  |
|          Octant           | ![NATS](https://github.com/ZhengDanYang1/Cloud-Native/raw/master/pic/Octant.png) | Octant是一个让开发人员了解应用程序如何在Kubernetes集群上运行的工具。它的目标是成为开发人员工具包的一部分，用于了解Kubernetes中的复杂性。Octant提供了内省工具、集群导航和对象管理的组合，以及一个插件系统来进一步扩展它的功能。 |    是    |  VMware  | https://github.com/vmware/octant |

### CI/CD

|     项目名称     |                           项目LOGO                           |                           项目概述                           | 是否开源 | 主导公司 | Github地址 |
| :--------------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :------: | :------: | :--------: |
| Tanzu  Concourse | ![NATS](https://github.com/ZhengDanYang1/Cloud-Native/raw/master/pic/Tanzu_Concourse.png) | Concourse是一个持续集成工具，可以使企业的IT人员构建，扩展和监控持续集成/持续部署的管道。通过使用Concourse，可以设置生产级的CI/CD管道从而实时部署和管理平台和应用程序。 |    是    |  VMware  |            |







---







## 云应用编排与管理

### 应用编排与调度

|          项目名称          |                           项目LOGO                           |                           项目概述                           | 是否开源 | 主导公司 |                   Github地址                   |
| :------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :------: | :------: | :--------------------------------------------: |
|        Spring  Boot        | ![NATS](https://github.com/ZhengDanYang1/Cloud-Native/raw/master/pic/spring_boot.png) | Spring  Boot的设计目的是让用户尽可能快地启动和运行，同时配置最少。Spring  Boot为生产就绪的应用提供opinionated的简易直观的最佳实践，通过简单而一致的开发体验，构建带有REST、WebSocket、消息传递、响应、数据、集成和批处理功能的微服务。 |          | Pivotal  | https://github.com/spring-projects/spring-boot |
| Tanzu  Application Service | ![NATS](https://github.com/ZhengDanYang1/Cloud-Native/raw/master/pic/Tanzu.png) | Tanzu  Application Service  (TAS)经过专门设计，适用于Java、.NET和Node应用的现代运行时产品，可让开发人员加快功能速度，让运维团队实现一流的正常运行时间。 |          |  VMware  |                                                |

### 远程调用

| 项目名称 | 项目LOGO | 项目概述 | 是否开源 | 主导公司 | Github地址 |
| :------: | :------: | :------: | :------: | :------: | :--------: |
|          |          |          |          |          |            |

### API网关

| 项目名称 | 项目LOGO | 项目概述 | 是否开源 | 主导公司 | Github地址 |
| :------: | :------: | :------: | :------: | :------: | :--------: |
|          |          |          |          |          |            |

### 服务网格

|      项目名称       |                           项目LOGO                           |                           项目概述                           | 是否开源 | 主导公司 | Github地址 |
| :-----------------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :------: | :------: | :--------: |
| Tanzu  Service Mesh | ![NATS](https://github.com/ZhengDanYang1/Cloud-Native/raw/master/pic/Tanzu.png) | Tanzu  Service Mesh建立在VMware  NSX®之上，在任何平台或云上提供端到端应用程序事务(终端用户到服务到数据)的一致操作和安全性。更重要的是，可以简化企业中所有服务网格的生命周期管理。 |          |  VMware  |            |







---









## 云原生工具集

### 流程自动化与配置管理

|        项目名称        |                           项目LOGO                           |                           项目概述                           | 是否开源 | 主导公司 | Github地址 |
| :--------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :------: | :------: | :--------: |
| Tanzu  Mission Control | ![NATS](https://github.com/ZhengDanYang1/Cloud-Native/raw/master/pic/Tanzu.png) | VMware  Tanzu Mission  Control是一个集中式管理平台，可跨多个团队和云一致地运行和保护Kubernetes基础架构和现代应用程序。它为运营商提供了一个控制点，为开发人员提供了推动业务发展所需的独立性，同时实现了跨环境的一致管理和操作，从而提高了安全性和治理。 |          |  VMware  |            |
|    vRealize  Suite     |                                                              | VMware  vRealize Suite 是一种多云环境的云计算管理解决方案，为 IT 组织提供了一个基于 DevOps 和 ML  原则的基础架构自动化、一致运维和监管的现代平台。 |          |  VMware  |            |
|  Tanzu  Observability  | ![NATS](https://github.com/ZhengDanYang1/Cloud-Native/raw/master/pic/Tanzu.png) | VMware®的Wavefront®是一个托管的性能指标分析平台，可提供所有Tanzu组件和云应用程序的即时可见性，从而帮助工程团队监视，排除故障并计划整个堆栈。  Wavefront为Tanzu管理员和开发人员提供了可共享的自助服务指标，以更快地将代码发布到生产环境中。 |          |  VMware  |            |

### 容器镜像仓库

| 项目名称 |                           项目LOGO                           |                           项目概述                           | 是否开源 | 主导公司 |             Github地址             |
| :------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :------: | :------: | :--------------------------------: |
|  Harbor  | ![NATS](https://github.com/ZhengDanYang1/Cloud-Native/raw/master/pic/Harbor.png) | Harbor可帮助用户迅速搭建企业级的镜像仓库  服务。Harbor不仅可以存储容器镜像，还可以存储与OCI标准兼容任何工件如Helm chart，云原生应用程序包（CNAB），开放策略代理包（OPA  bundle）等。它提供了管理图形界面, 基于角色的访问控制(Role Based Access  Control)，镜像远程复制（同步），镜像漏洞扫描，镜像公证，AD/LDAP集成、以及审计日志等企业用户需求的功能，同时还原生支持中文，深受中国用户的喜爱。该项目推出4年多以来，在GitHub  获得了超过12000多个点赞星星和3200多个  forks。Harbor目前是云原生基金会（CNCF）的孵化级别的开源项目。（即将于美国时间2020/6/23宣布成为毕业项目） |    是    |  VMware  | https://github.com/goharbor/harbor |

### 云原生安全技术

| 项目名称 | 项目LOGO | 项目概述 | 是否开源 | 主导公司 | Github地址 |
| :------: | :------: | :------: | :------: | :------: | :--------: |
|          |          |          |          |          |            |

### 云端密码管理

| 项目名称 | 项目LOGO | 项目概述 | 是否开源 | 主导公司 | Github地址 |
| :------: | :------: | :------: | :------: | :------: | :--------: |
|          |          |          |          |          |            |







---







## 云原生底层技术

### 容器技术

|            项目名称            |                           项目LOGO                           |                           项目概述                           | 是否开源 | 主导公司 |              Github地址              |
| :----------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :------: | :------: | :----------------------------------: |
|    VMware Cloud Foundation     |                                                              | VMware  Cloud Foundation是基于全栈超融合基础架构（HCI）技术构建的混合云平台，用于管理虚拟机和编排容器。凭借易于部署的单一体系架构，VMware  Cloud Foundation  可在私有云和公有云之间实现一致、安全的基础架构和运维。通过可以提供这一切的混合云，提高企业的敏捷性和灵活性。通过集成的容器编排（由 vSphere 7  with Kubernetes 提供支持）优化 Kubernetes 集群的性能、恢复能力和可用性。 |          |  VMware  |                                      |
| vSphere  Integrated Containers |                                                              | vSphere  Integrated Containers (VIC)  是基于虚拟机技术实现的容器运行平台的开源项目，每个容器对于一个虚机，创建一个容器就相当于增加一个虚机，删除容器就是删除它所对应的虚机。VIC 提供了兼容  Docker 的命令，开发人员只需使用 Docker 容器命令就可以创建容器和使用容器。 |    是    |  VMware  | http://github.com/vmware/vic-product |
|     Tanzu  Kubernetes Grid     | ![NATS](https://github.com/ZhengDanYang1/Cloud-Native/raw/master/pic/Tanzu.png) | VMware  Tanzu Kubernetes  Grid（非正式名称为TKG）是一个面向多云的Kubernetes发行版，可以在vSphere和公共云中本地运行。除了受VMware测试，签名和支持的Kubernetes二进制文件外，Tanzu  Kubernetes Grid还包括签名和受支持的开源应用程序版本，以提供生产Kubernetes环境所需的联网，身份验证，入口控制和日志记录服务。 |          |  VMware  |                                      |

### 存储技术

|   项目名称   | 项目LOGO |                           项目概述                           | 是否开源 | 主导公司 | Github地址 |
| :----------: | :------: | :----------------------------------------------------------: | :------: | :------: | :--------: |
| VMware  vSAN |          | vSAN  是企业级存储虚拟化软件，与 vSphere 结合使用时，可让您通过单个平台管理计算和存储。借助  vSAN，您可以降低传统存储高昂的成本和较高的复杂性，通过最简单的方法实现超融合基础架构和混合云。采用基于 vSAN 的集成式超融合基础架构 (HCI)  解决方案，可以在加快运维速度并降低成本的同时提高业务敏捷性。 |          |  VMware  |            |

### 网络技术

|              项目名称              |                           项目LOGO                           |                           项目概述                           | 是否开源 | 主导公司 |               Github地址                |
| :--------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :------: | :------: | :-------------------------------------: |
|      VMware  NSX Data Center       |                                                              | 使虚拟云网络能够跨数据中心、多云环境、裸机和容器基础架构连接并保护应用。VMware  NSX Data Center 提供完整的 L2-L7 网络和安全虚拟化平台，支持像从单一窗口管理单个条目一样轻松管理整个网络。 |          |  VMware  |                                         |
|         VMware  NSX Cloud          |                                                              | VMware  NSX  Cloud，可为在公有云中原生运行的应用提供一致的网络和安全服务。不再有基础架构孤立小环境增加复杂性和运维成本，而是享受跨虚拟网络、区域和云环境的全局原生安全策略和精确控制。 |          |  VMware  |                                         |
| VMware  NSX Advanced Load Balancer |                                                              | VMware  NSX Advanced Load Balancer (Avi Networks) 可跨本地数据中心和任何云环境提供多云负载平衡、Web  应用防火墙和应用分析。该软件定义的平台跨裸机服务器、虚拟机和容器一致地提供应用，以确保提供快速、可扩展和安全的应用体验。 |          |  VMware  |                                         |
|        SD-WAN  by VeloCloud        |                                                              | VMware  SD-WAN by VeloCloud 可提供对云计算服务、专有数据中心和基于 SaaS 的企业级应用的可靠的高性能分支访问。 |          |  VMware  |                                         |
|               Antrea               | ![NATS](https://github.com/ZhengDanYang1/Cloud-Native/raw/master/pic/Tanzu.png) | Antrea是一个Kubernetes网络解决方案，旨在与Kubernetes原生集成。它在网络的Layer3/4层运行，为Kubernetes集群提供网络和安全服务，Antrea利用Open  vSwitch作为网络数据平面，实现Pod网络和安全特性。例如，Open vSwitch使Antrea能够非常有效地实现Kubernetes网络策略。 |    是    |          | https://github.com/vmware-tanzu/antrea/ |
|    NSX  Advanced Load Balancer     |                                                              | VMware  NSX Advanced Load Balancer (Avi Networks) 可跨本地数据中心和任何云环境提供多云负载平衡、Web  应用防火墙和应用分析。该软件定义的平台跨裸机服务器、虚拟机和容器一致地提供应用，以确保提供快速、可扩展和安全的应用体验。 |          |  VMware  |                                         |

