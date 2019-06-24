# What Is MicroServices ?
```md
微服务不单单是一种技术架构，也涉及到了管理、组织架构。
在微服务的架构下，一个服务应该是由一个团队全权负责的。
```
## 特征
```md
1. 通过服务实现组件化
2. 按业务能力来划分服务和开发团队
3. 去中心化
4. 基础设施自动化(DevOPs、自动化部署)
```

## Compare
* 微服务与SOA
```md
	微服务是SOA的一种实现
	微服务是去ESB的SOA
	背后实际上是两种思想的分歧：服务的治理分布还是集中
```
* vs. SOA vs. Distributed
```md
微服务是架构设计方式，分布式是系统部署方式。

分布式的思想就是把一个系统的不同模块，部署在不同的服务器上，以应对高并发的问题。

SOA是一种分布式架构，把业务系统分成多个子系统，提供不同的服务，再通过服务组合、编排实现业务流程；
通常在SOA架构中，ESB企业服务总线扮演了重要的角色。

微服务是SOA的升华，如果非要说点儿不同的，那么微服务更加强调服务的细分和专业，
去ESB总线、去中心化，部署粒度更细，服务扩展更灵活。
```