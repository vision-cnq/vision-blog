# vision-blog


blog-api：定义项目中所有的api接口，暴露对外的restful接口
blog-common：系统公共模块 
blog-config：配置中心
blog-dao：数据中心
blog-gateway：api网关
blog-elk：日志采集，搜索系统等
blog-monitor：监控中心
blog-registry：注册中心
blog-service：业务逻辑
blog-client：存放控制层，负责对外的开放
blog-ui：前端页面


依赖关系：
1.ui调用gateway
2.gateway调用api
3.api调用client
4.client调用service
5.elk


