# micro_arch

# 目标
micro_arch希望可以为初创互联网企业提供一套可行的CI/CD流水线以及微服务框架的方案。

# 解构
micro_arch分为两个部分
* cicd:CI/CD的方案
* mservice:微服务架构的方案

## cicd
以docker容器为演练环境，搭建起可供运维、开发使用的编译、打包、测试、发布、回滚等自动化操作，方便技术团队可适应快速迭代的需求。

cicd的所有操作会以应用树(Yggdrasill)为入口，通达各种运维节点，包括应用所绑定的机器、域名、发布、回滚、申请集群信息等。

## mservice
分成技术组件和业务代码。

### 技术组件
redis、mysql、消息中间件、zk等
