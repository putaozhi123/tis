![tis](docs/tis-logo.png)

## 产品特性

TIS是一款为用户提供一站式搜索引擎服务的企业化产品，它基于Solr，具有方便、快捷、稳定、易维护的特性。

有以下功能特性:

- 具有版本控制的元数据维护
 
   将solr配置文件(schema.xml,solr.xml)从Zookeeper中剥离，持久化由TIS托管，并且提供多版本机制，实现索引修改历史查看，回滚等机制。

- 离线式全量索引构建流程

   企业级数据索引数据规模上亿是非常常见的，加之业务中会以多表Join（构建宽表）的方式实现全量数据。在此背景下Solr自带的数据导入插件会有诸多问题，例如导入时间长，导入过程中会影响线上搜索节点的正常访问等。因此TIS中独创性的提供了离线全量索引构建的解决方案，实现了海量索引数据快速构建，无缝切换等功能。

- 基于流式计算的数据近实时同步方案

 TIS提供了针对Solr搜索引擎的增量近实时解决方案，实现了数据库中的数据变更秒级同步到Solr搜索引擎中，且TIS已经无缝将增量引擎无缝整合到TIS平台，在增量执行过程中的实时状态信息实时同步到TIS控制台中。

- 为行业痛点提供模板式解决方案

- 具有一站式全生命周期控制的控制台界面

- 为行业痛点提供模板化快速解决方案

## 安装说明

## 使用者

## 架构

## 许可协议