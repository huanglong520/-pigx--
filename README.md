---商业版:
PIGX采用 J2EE 技术体系，基于Spring Cloud微服务框架进行封装，平台设计灵活可扩展、可移植、可应对高并发需求。同时兼顾本地化、私有云、公有云部署，支持SaaS模式应用。开发框架：平台底层应用的基础服务，是一个微服务系统运行所必要的组件服务。平台提供较好的兼容性，可根据需要选择不同的基础组件，如注册中心、配置中心、分布式事务等，并能很好的适配阿里云EDAS等公有云平台。

辅助开发包
主要针对开发人员进行技术开发支持，提供一系列通用的开发工具包，定义了基础工具类，如配置、缓存、路由、发号器等工具，减少开发人员重复造轮子，帮助提高代码编写效率。

通用服务：
主要指平台中已包含的开发业务系统所需要的基础服务，如分布式调度、消息、权限、文档、支付管理等，能快速适配各产品线、各业务系统的通用基础功能需求，帮助提高开发效率。

基本功能：
PIG商业版 平台提供的通用业务功能，目前主要包括权限管理、协同办公、支付收单、公众号管理等一系列一个业务系统所必须的基础功能。

├── PIGX-ui -- 前端工程[8080]

├── PIGX-auth -- 授权服务提供[3000]

├── PIGX-common -- 系统公共模块

├ ├── PIGX-common-bom -- 公共依赖版本

├ ├── PIGX-common-core -- 公共工具类核心包

├ ├── PIGX-common-data -- 数据相关

├ ├── PIGX-common-datasource -- 动态数据源相关

├ ├── PIGX-common-feign -- feign 通用封装

├ ├── PIGX-common-gateway -- 动态路由定义

├ ├── PIGX-common-gray -- 灰度路由控制封装

├ ├── PIGX-common-job -- 定时任务

├ ├── PIGX-common-log -- 日志服务

├ ├── PIGX-common-oss -- 通用文件系统

├ ├── PIGX-common-security -- 安全工具类

├ ├── PIGX-common-sentinel -- sentinel分装

├ ├── PIGX-common-sequence -- 全局发号器

├ ├── PIGX-common-swagger -- Swagger Api文档生成

├ ├── PIGX-common-test -- oauth 2.0 单元测试方案

├ ├── PIGX-common-xss -- xss 安全过滤组件

├ └── PIGX-common-transaction -- 分布式事务工具包

├── PIGX-register -- 注册中心、配置中心[8848]

├── PIGX-gateway -- Spring Cloud Gateway网关[9999]

├── PIGX-upms -- 通用用户权限管理模块

├ └── PIGX-upms-api -- 通用用户权限管理系统公共api模块

├ └── PIGX-upms-biz -- 通用用户权限管理系统业务处理模块[4000]

└── PIGX-visual -- 图形化模块

├ ├── PIGX-monitor -- Spring Boot Admin监控 [5001]

├ ├── PIGX-daemon-elastic-job -- 分布式调度中心[elastic-job 版本]

├ ├── PIGX-daemon-quartz -- 分布式调度中心[quartz]

├ ├── PIGX-code-gen -- 图形化代码生成[5003]

├ ├── PIGX-sso-client-demo -- sso 客户端接入示例

├ ├── PIGX-tx-manager -- PIGX分布式事务解决方案[5004]

├ ├── PIGX-bi-platform -- 报表在线设计模块[5006]

├ ├── PIGX-oa-platform -- 工作流模块[5005]

├ ├── PIGX-pay-platform -- 微信支付宝收单模块[5010]

├ ├── PIGX-mp-platform -- 微信管理模块[6000]

├ └── PIGX-sentinel-dashboard -- sentinel 控制台[5005]

点我获取资料 https://mfk.hllfy.top
