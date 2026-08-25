最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计 issue 模板 bug 反馈模板
简介：golang go panic 合理使用边界，panic 只用于不可恢复程序错误，业务逻辑禁止直接 panic。
 | 原文链接：http://zhishi.c9hyko.asia/blog/6480947.sHtML

原标题：golang 系统设计灰度发布流量切分实现
简介：golang runtime.Gosched 主动让出调度，长计算循环主动 Gosched，让出调度权，防止其他协程饥饿。
 | 原文链接：http://zhishi.c9hyko.asia/blog/5054506.sHtML

原标题：优化实践：业务定时任务错开高峰避免资源争抢
简介：Nginx 请求头大小上限调整，修改 Nginx 配置，调大请求头允许最大大小，避免大 Header 请求被拒绝。
 | 原文链接：http://zhishi.c9hyko.asia/blog/1973497.sHtML

原标题：golang 系统设计定时任务失败重试告警实现
简介：golang loki 日志收集 go 服务集成，日志输出适配 loki，标签携带 traceId，日志集中检索排查问题。
 | 原文链接：http://zhishi.c9hyko.asia/blog/3053651.sHtML

原标题：多环境配置中心灵活切换方案
简介：前端组件库按需加载性能优化，配置组件库按需引入，避免引入全部组件，减少打包产物体积。
 | 原文链接：http://zhishi.c9hyko.asia/blog/3476234.sHtML

原标题：golang 链路 traceId 透传中间件
简介：golang kitex 超时重试熔断配置，kitex 配置调用超时、重试、熔断策略，保障微服务调用稳定性。
 | 原文链接：http://zhishi.c9hyko.asia/blog/7591492.sHtML

原标题：安全实践：容器最小化镜像减少攻击面
简介：golang go 程序版本号内置编译注入，编译时注入 git commit 版本号，程序运行输出版本便于排查。
 | 原文链接：http://zhishi.c9hyko.asia/blog/3753611.sHtML

原标题：Hands‑on：手写简易ORM框架理解底层原理
简介：golang websocket 服务端开发，Go 实现 WebSocket 服务端，处理连接、消息收发，实现长连接服务。
 | 原文链接：http://zhishi.c9hyko.asia/blog/8329804.sHtML

原标题：Architecture：静态资源分发CDN整体架构思路
简介：vue pinia 状态管理实战教程，Pinia 完整实战示例，实现状态定义修改，模块拆分替代 Vuex。
 | 原文链接：http://zhishi.c9hyko.asia/blog/7645610.sHtML

原标题：golang 系统设计最小权限原则落地实践
简介：golang 容器时区设置镜像构建处理，镜像内部设置正确时区，解决容器时间与宿主机不一致。
 | 原文链接：http://zhishi.c9hyko.asia/blog/3101974.sHtML

原标题：golang 系统设计基准测试 benchmark 编写
简介：golang go‑zero 框架项目快速搭建，go‑zero 脚手架生成微服务项目，api rpc 服务快速开发。
 | 原文链接：http://zhishi.c9hyko.asia/blog/4156982.sHtML

原标题：实战：单元测试+集成测试完整项目落地实践
简介：读懂开源项目 README 实用技巧，教你快速解析开源项目说明文档，提取安装、运行、配置关键信息，快速上手项目。
 | 原文链接：http://zhishi.c9hyko.asia/blog/5242533.sHtML

原标题：实践：前后端时间格式统一规范落地实践
简介：golang go mod exclude 排除依赖版本，exclude 排除有问题依赖版本，规避有 bug 的第三方包。
 | 原文链接：http://zhishi.c9hyko.asia/blog/7524684.sHtML

原标题：业务错误码体系设计方案
简介：golang atomic 原子操作整数，atomic 加减比较交换，无锁更新整型变量，简单计数器场景。
 | 原文链接：http://zhishi.c9hyko.asia/blog/5942658.sHtML

原标题：CI 构建缓存加速编译速度
简介：golang 容器内读取 k8s 配置 configmap，程序读取 k8s configmap 配置，配置与镜像分离便于运维。
 | 原文链接：http://zhishi.c9hyko.asia/blog/1667214.sHtML

原标题：golang 系统设计集成测试环境准备清理实操
简介：golang go 排序 sort 包自定义排序，sort 包实现自定义排序逻辑，对切片按业务规则排序。
 | 原文链接：http://zhishi.c9hyko.asia/blog/0416584.sHtML

原标题：复盘总结：技术选型对比文档模板实践
简介：golang redis hyperloglog 基数统计，hyperloglog 统计 UV 基数，海量数据去重统计，极低内存开销。
 | 原文链接：http://zhishi.c9hyko.asia/blog/9129545.sHtML

原标题：性能笔记：避免频繁创建销毁对象GC优化
简介：nestjs 全局返回格式统一处理，Nest 全局拦截器统一包装接口返回数据，对外输出标准化响应格式。
 | 原文链接：http://zhishi.c9hyko.asia/blog/4145769.sHtML

原标题：跨平台 uniapp 多端开发实操
简介：golang go‑zero 分布式锁组件使用，go‑zero 内置 redis 分布式锁，业务直接调用实现并发控制。
 | 原文链接：http://zhishi.c9hyko.asia/blog/3288120.sHtML

原标题：Hands‑on：编写shell健康检查自动重启脚本
简介：golang 日志脱敏敏感字段过滤，日志打印自动脱敏敏感字段，避免日志输出手机号身份证泄露隐私。
 | 原文链接：http://zhishi.c9hyko.asia/blog/9785467.sHtML

原标题：新手向：项目目录结构规范与含义解析
简介：Redis 分布式锁高并发安全实现，基于 Redis 实现分布式锁，处理锁过期、续期，保障集群并发安全。
 | 原文链接：http://zhishi.c9hyko.asia/blog/5258537.sHtML

原标题：golang 系统设计敏感数据加密存储方案
简介：golang time duration 解析时间字符串，time.ParseDuration 解析 1h30m 时间间隔字符串。
 | 原文链接：http://zhishi.c9hyko.asia/blog/9116161.sHtML

原标题：调优方案：前端静态资源打包性能体积优化
简介：golang go‑pg postgres 客户端实操，go‑pg 操作 PostgreSQL 数据库，CRUD 关联查询业务开发。
 | 原文链接：http://zhishi.c9hyko.asia/blog/6708399.sHtML

原标题：Issue：WSL2内存持续暴涨不自动释放
简介：GET POST 接口请求参数处理，讲解两种请求方式参数传递区别，演示参数接收、解析、校验，适配不同接口调用场景。
 | 原文链接：http://zhishi.c9hyko.asia/blog/0095996.sHtML

原标题：golang 系统设计告警渠道钉钉邮件企业微信集成
简介：golang bcrypt 密码哈希加密存储，bcrypt 做用户密码哈希，加盐存储密码，保障用户密码安全。
 | 原文链接：http://zhishi.c9hyko.asia/blog/4999197.sHtML

原标题：Practice：实现请求body重复读取中间件实践
简介：golang go mod graph 可视化依赖图，可视化 go 依赖关系，直观看到包之间依赖，定位冲突。
 | 原文链接：http://zhishi.c9hyko.asia/blog/6359393.sHtML

原标题：golang 系统设计 span 埋点业务代码最小侵入思路
简介：golang 制品镜像版本号规范管理，镜像版本号结合 git commit，明确每个镜像对应代码版本便于追溯。
 | 原文链接：http://zhishi.c9hyko.asia/blog/7047168.sHtML

原标题：Git 仓库瘦身加快克隆下载速度
简介：golang 大文件 HTTP 流式上传接收，服务端流式接收上传文件，不全部加载内存，防止大文件 OOM 崩溃。
 | 原文链接：http://zhishi.c9hyko.asia/blog/3136651.sHtML

原标题：实践：接口参数自动校验业务落地实践
简介：golang 滑动窗口限流算法 go 实现，滑动窗口限流，解决固定窗口临界流量突增漏洞，限流更精准。
 | 原文链接：http://zhishi.c9hyko.asia/blog/4428979.sHtML

原标题：零基础理解版本控制核心概念与工作流
简介：golang go 模板缓存预编译模板，预编译 html 模板，程序启动加载，避免每次请求解析模板损耗性能。
 | 原文链接：http://zhishi.c9hyko.asia/blog/8558278.sHtML

原标题：golang 系统设计读写分离延迟业务兼容
简介：golang 错误处理最佳实践汇总，Go 错误处理规范，包装错误，堆栈携带，拒绝简单忽略错误。
 | 原文链接：http://zhishi.c9hyko.asia/blog/6505279.sHtML

原标题：Security：RPC调用身份认证安全加固
简介：开源源码阅读拆解学习思路，分享阅读大型开源项目方法，从入口文件逐层拆解模块，降低源码学习门槛。
 | 原文链接：http://zhishi.c9hyko.asia/blog/6066137.sHtML

原标题：踩坑记录：时间戳精度不一致引发判断错误
简介：对象存储上传下载权限实操，演示对象存储文件上传、下载、访问权限设置，适配业务文件存储场景。
 | 原文链接：http://zhishi.c9hyko.asia/blog/5702333.sHtML

原标题：golang 数据库连接泄露排查
简介：golang grpc 重试机制客户端配置，grpc 客户端配置重试策略，临时故障自动重试，提升调用稳定性。
 | 原文链接：http://zhishi.c9hyko.asia/blog/2002562.sHtML

原标题：设计思考：防雪崩，系统过载保护架构设计
简介：golang bufio 缓冲读写性能优化，bufio 带缓冲读写，减少系统调用，提升文件网络 IO 性能。
 | 原文链接：http://zhishi.c9hyko.asia/blog/4927966.sHtML

原标题：golang 系统设计告警规则阈值设置方法论
简介：golang GC 频繁 STW 停顿优化，减少小对象分配，调整 GOGC，降低 GC 停顿对接口延迟影响。
 | 原文链接：http://zhishi.c9hyko.asia/blog/6497300.sHtML

原标题：golang 系统设计开源版本发布 changelog 维护
简介：对象存储上传下载权限实操，演示对象存储文件上传、下载、访问权限设置，适配业务文件存储场景。
 | 原文链接：http://zhishi.c9hyko.asia/blog/1902296.sHtML

原标题：golang mysql limit 大分页优化
简介：YAML 配置文件语法快速上手，讲解 YAML 基础语法、缩进规则，编写项目配置文件，规避语法错误引发程序异常。
 | 原文链接：http://zhishi.c9hyko.asia/blog/8380403.sHtML

原标题：golang k8s 命名空间资源隔离方案
简介：ORM 框架数据库增删改查实操，使用 ORM 框架完成数据库基础操作，减少手写 SQL，简化业务层数据库交互代码。
 | 原文链接：http://zhishi.c9hyko.asia/blog/7895878.sHtML

原标题：Debug：网关超时时间小于后端接口超时设置
简介：多环境配置中心灵活切换方案，简易配置中心实现，支持多套环境配置，动态下发无需重启服务。
 | 原文链接：http://zhishi.c9hyko.asia/blog/1909919.sHtML


二、踩坑排错｜Troubleshooting
原标题：前端大文件分片上传完整方案
简介：golang http 文件下载断点续传服务，服务端实现断点续传，支持大文件分段下载，提升大文件下载稳定性。
 | 原文链接：http://zhishi.c9hyko.asia/blog/7864839.sHtML

原标题：DevOps：Docker镜像优化，减小镜像体积实践
简介：分布式 ID 全局唯一生成方案，讲解分布式 ID 生成思路，实现全局唯一 ID，满足分布式系统主键生成需求。
 | 原文链接：http://zhishi.c9hyko.asia/blog/4856887.sHtML

原标题：性能复盘：接口响应从800ms优化到50ms全过程
简介：golang go‑zero 配置中心热更新，go‑zero 对接 etcd 配置中心，配置热更新无需重启服务。
 | 原文链接：http://zhishi.c9hyko.asia/blog/4553928.sHtML

原标题：设计实践：如何设计可扩展业务数据库表结构
简介：golang aes 对称加密解密示例，AES 对称加密解密实现，业务敏感数据加密存储传输。
 | 原文链接：http://zhishi.c9hyko.asia/blog/1408111.sHtML

原标题：Security：文件路径穿越漏洞完整防护
简介：golang 异步任务队列 worker 池开发，任务入数据库或 redis，worker 池消费执行，异步处理耗时业务。
 | 原文链接：http://zhishi.c9hyko.asia/blog/2135784.sHtML

原标题：性能笔记：锁优化减少竞争提升并发吞吐
简介：配置与镜像分离防止信息泄露，业务配置不打包进镜像，外部挂载配置，避免密钥配置随镜像泄露。
 | 原文链接：http://zhishi.c9hyko.asia/blog/9602352.sHtML

原标题：调优方案：JVM内存参数优化，降低GC频率
简介：golang jwt jwk 公钥验证令牌，使用 jwk 公钥校验 jwt，非对称方式签发校验令牌，提升安全性。
 | 原文链接：http://zhishi.c9hyko.asia/blog/0802860.sHtML

原标题：排错：静态资源CDN缓存未刷新旧资源持续返回
简介：golang go 基准测试 benchmark 编写，Benchmark 性能基准测试，测量函数执行耗时内存分配情况。
 | 原文链接：http://zhishi.c9hyko.asia/blog/9960986.sHtML

原标题：golang 系统设计防爬虫简单策略
简介：开源源码阅读拆解学习思路，分享阅读大型开源项目方法，从入口文件逐层拆解模块，降低源码学习门槛。
 | 原文链接：http://zhishi.c9hyko.asia/blog/0808828.sHtML

原标题：golang 系统设计联合索引设计避坑要点
简介：golang 大文件 HTTP 流式上传接收，服务端流式接收上传文件，不全部加载内存，防止大文件 OOM 崩溃。
 | 原文链接：http://zhishi.c9hyko.asia/blog/5734084.sHtML

原标题：Practice：实现限流之后友好业务返回处理
简介：golang grpc 拦截器开发鉴权日志，开发 grpc 服务端拦截器，统一做鉴权、日志打印、异常捕获处理。
 | 原文链接：http://zhishi.c9hyko.asia/blog/4145494.sHtML

原标题：golang 重试退避机制代码实现
简介：golang kitex 字节微服务框架入门，kitex 开发 rpc 微服务，代码生成，服务注册发现完整流程。
 | 原文链接：http://zhishi.c9hyko.asia/blog/5654646.sHtML

原标题：安全笔记：请求头伪造IP漏洞防护
简介：golang 项目 go mod 依赖管理，Go Mod 管理项目依赖，下载、升级、清理依赖，解决依赖版本管理。
 | 原文链接：http://zhishi.c9hyko.asia/blog/9428459.sHtML

原标题：golang 系统设计代码安全审计简单思路
简介：golang 数据库分表策略按时间分片，按时间维度分表，历史数据拆分，单表数据量控制保证查询性能。
 | 原文链接：http://zhishi.c9hyko.asia/blog/0959262.sHtML

原标题：OpenSource：开源项目许可证License选型指南
简介：golang mime 类型检测文件，mime 识别文件 mime 类型，设置 http 响应 Content‑Type。
 | 原文链接：http://zhishi.c9hyko.asia/blog/0878037.sHtML

原标题：架构笔记：WebSocket大规模连接服务架构
简介：golang sync.WaitGroup 协程等待控制，WaitGroup 控制一组协程等待全部执行完成，完成批量协程任务调度。
 | 原文链接：http://zhishi.c9hyko.asia/blog/8907242.sHtML

原标题：git rebase 整理提交历史实操
简介：golang context 上下文传参讲解，讲解 Context 使用场景，传递元数据、控制协程超时取消，规范协程控制。
 | 原文链接：http://zhishi.c9hyko.asia/blog/5248756.sHtML

原标题：nestjs 框架模块化项目搭建
简介：golang http MaxHeaderBytes 限制请求头，设置 http 最大请求头大小，防止超大 header 攻击。
 | 原文链接：http://zhishi.c9hyko.asia/blog/9340983.sHtML

原标题：golang 系统设计短链接服务实现思路
简介：golang gorm 原生 SQL 执行处理，复杂场景执行原生 SQL，处理返回结果集，兼顾性能与灵活性。
 | 原文链接：http://zhishi.c9hyko.asia/blog/6347327.sHtML

原标题：golang 系统设计集成测试数据库回滚重置方案
简介：golang 结构体 json 序列化坑点，梳理 Go 结构体 JSON 序列化高频坑点，字段大小写、零值处理问题。
 | 原文链接：http://zhishi.c9hyko.asia/blog/3051754.sHtML

原标题：golang 系统设计故障止损降级回滚执行原则
简介：golang golangci‑lint 静态代码检查配置，golangci‑lint 静态检查，代码规范检测，提前发现代码隐患。
 | 原文链接：http://zhishi.c9hyko.asia/blog/7884935.sHtML

原标题：设计思考：分布式锁选型、风险、业务约束
简介：golang go 代码覆盖率线上统计，单元测试覆盖率统计，找出未测试代码分支，提升测试质量。
 | 原文链接：http://zhishi.c9hyko.asia/blog/8250758.sHtML

原标题：golang jwt 过期刷新 token 实现
简介：浏览器内存泄漏排查前端页面，梳理前端页面内存泄漏场景，讲解排查手段，修复页面内存持续上涨。
 | 原文链接：http://zhishi.c9hyko.asia/blog/0107056.sHtML

原标题：踩坑记录：UTC时间与本地时间混用逻辑错乱
简介：跨域偶现失败配置修复，解决跨域问题时而复现时而正常，定位配置漏配、请求头异常等隐性问题。
 | 原文链接：http://zhishi.c9hyko.asia/blog/3533573.sHtML

原标题：文件句柄上限调整上传随机失败
简介：golang mime 类型检测文件，mime 识别文件 mime 类型，设置 http 响应 Content‑Type。
 | 原文链接：http://zhishi.c9hyko.asia/blog/7578039.sHtML

原标题：Practice：实现IP黑名单拦截中间件实践
简介：后端大文件分片上传接口开发，开发后端分片上传接口，接收分片，合并分片完成大文件存储。
 | 原文链接：http://zhishi.c9hyko.asia/blog/5400949.sHtML

原标题：实践：静态站点自动化部署到GitHubPages
简介：前端 pdf 预览渲染方案对比，对比前端 PDF 预览库，分析性能、兼容性，给出业务选型参考。
 | 原文链接：http://zhishi.c9hyko.asia/blog/3492468.sHtML

原标题：golang 系统设计 rest api 接口设计最佳实践
简介：golang 优雅处理数据库事务，Go 数据库事务封装，正确处理事务提交回滚，保证业务数据一致性。
 | 原文链接：http://zhishi.c9hyko.asia/blog/3099139.sHtML

原标题：入门实践：项目配置文件多环境管理方案
简介：包管理器依赖冲突解决方案，分析依赖冲突产生根源，提供版本调整、锁定依赖等手段，解决项目依赖报错问题。
 | 原文链接：http://zhishi.c9hyko.asia/blog/7120396.sHtML

原标题：golang url 参数编码处理方案
简介：golang 响应 body 流式返回大数据，http 流式输出数据，边生成边返回，无需在内存组装完整返回结果。
 | 原文链接：http://zhishi.c9hyko.asia/blog/7941722.sHtML

原标题：Security：SSRF服务端请求伪造漏洞防御
简介：磁盘 inode 耗尽文件创建失败，排查磁盘 inode 占用，清理大量小文件，恢复文件创建能力。
 | 原文链接：http://zhishi.c9hyko.asia/blog/0809242.sHtML

原标题：踩坑记录：UTC时间与本地时间混用逻辑错乱
简介：布隆过滤器误判问题修正，调整布隆过滤器参数，降低误判概率，保证业务去重逻辑准确。
 | 原文链接：http://zhishi.c9hyko.asia/blog/4490435.sHtML

原标题：Troubleshoot：MySQL字符集utf8非utf8mb4emoji报错
简介：Nginx 请求头大小上限调整，修改 Nginx 配置，调大请求头允许最大大小，避免大 Header 请求被拒绝。
 | 原文链接：http://zhishi.c9hyko.asia/blog/2081465.sHtML

原标题：service‑worker 离线缓存实践
简介：golang mime 类型检测文件，mime 识别文件 mime 类型，设置 http 响应 Content‑Type。
 | 原文链接：http://zhishi.c9hyko.asia/blog/3114918.sHtML

原标题：golang 系统设计配置回滚版本历史记录实现
简介：nodejs 跨域中间件配置细节，Express 跨域中间件配置细节，处理预检请求，修复偶现跨域失效。
 | 原文链接：http://zhishi.c9hyko.asia/blog/8646198.sHtML

原标题：开发记录：长连接连接管理自动清理僵死连接
简介：前端下载导出文件功能实现，前端实现文件流下载导出，处理异常，适配浏览器不同下载行为。
 | 原文链接：http://zhishi.c9hyko.asia/blog/0008621.sHtML

原标题：快速上手简单的限流逻辑模拟实现
简介：golang gorm ORM 数据库操作，GORM 实操数据库 CRUD，模型定义，关联查询，简化 Go 数据库开发。
 | 原文链接：http://zhishi.c9hyko.asia/blog/3203109.sHtML

原标题：Debug：分页偏移量过大数据库查询性能暴跌
简介：Shell 脚本自动化命令编写，讲解 Shell 基础语法，编写自动化脚本，完成批量执行、文件处理，解放重复手工操作。
 | 原文链接：http://zhishi.c9hyko.asia/blog/0757891.sHtML

原标题：代理 HTTPS 证书访问异常处理
简介：无用对象回收抑制内存上涨，优化对象生命周期，及时释放不再使用对象，抑制内存持续不断增长。
 | 原文链接：http://zhishi.c9hyko.asia/blog/4800510.sHtML

原标题：开发记录：分布式锁超时业务安全处理实践
简介：golang 云存储 s3 协议对象存储，go s3 客户端，兼容 minio 阿里云 oss，实现文件上传下载签名访问。
 | 原文链接：http://zhishi.c9hyko.asia/blog/1977732.sHtML

三、实战开发｜Practice
原标题：从零搭建本地开发环境完整教程
简介：golang lru 缓存淘汰算法编写，手写 LRU 缓存淘汰算法，实现本地缓存，淘汰最久未使用数据。
 | 原文链接：http://zhishi.c9hyko.asia/blog/0146898.sHtML

原标题：坑点：环境配置被打包进镜像引发安全泄露
简介：golang go‑zero api 接口开发与路由，go‑zero 编写 api 定义文件，生成代码开发 http 接口。
 | 原文链接：http://zhishi.c9hyko.asia/blog/1933244.sHtML

原标题：golang 优雅处理系统信号 SIGINT
简介：前端大文件分片上传完整方案，前端分片切割大文件，配合后端分片接口，实现稳定大文件上传。
 | 原文链接：http://zhishi.c9hyko.asia/blog/1808169.sHtML

原标题：DevOps：CI构建产物缓存复用加速编译
简介：golang go 模块迁移从 GOPATH 到 GoMod，老项目从 GOPATH 迁移 go mod，解决依赖管理混乱问题。
 | 原文链接：http://zhishi.c9hyko.asia/blog/3447771.sHtML

原标题：golang 系统设计代码评审关注点 checklist 清单
简介：golang 单元测试 mock http 请求，mock HTTP 外部接口，单元测试不依赖外部网络，保证用例稳定运行。
 | 原文链接：http://zhishi.c9hyko.asia/blog/7394531.sHtML

原标题：性能笔记：RPC超时参数优化防止级联阻塞
简介：分布式事务最终一致性实现，基于可靠消息实现最终一致性，解决跨数据库跨服务业务数据一致性。
 | 原文链接：http://zhishi.c9hyko.asia/blog/5052166.sHtML

原标题：golang 系统设计回调重试幂等完整处理
简介：Nginx 透传真实客户端 IP 配置，配置 Nginx 把真实客户端 IP 传递后端服务，后端拿到访问者真实 IP。
 | 原文链接：http://zhishi.c9hyko.asia/blog/1211410.sHtML

原标题：golang 系统设计开源项目 release 发布流程
简介：ServiceWorker 缓存页面更新清理，处理 ServiceWorker 缓存，实现页面新版本更新，用户可以加载最新页面。
 | 原文链接：http://zhishi.c9hyko.asia/blog/3436914.sHtML

原标题：实战项目：编写Dockerfile多阶段构建减小镜像体积
简介：golang redis 过期时间处理技巧，设置 key 过期，监控过期事件，基于过期特性实现业务缓存逻辑。
 | 原文链接：http://zhishi.c9hyko.asia/blog/7772161.sHtML

原标题：安全复盘：定时任务权限过大风险管控
简介：golang bytes.Buffer 字节缓冲区使用，bytes.Buffer 字节内存缓冲区，拼接字节，避免频繁内存分配。
 | 原文链接：http://zhishi.c9hyko.asia/blog/2235608.sHtML

原标题：golang 接口返回统一封装工具
简介：golang 内存碎片问题识别与规避，大量小对象频繁分配产生内存碎片，通过对象池减少碎片。
 | 原文链接：http://zhishi.c9hyko.asia/blog/6196401.sHtML

原标题：SDK 版本兼容线上崩溃修复
简介：Git 子模块更新代码不全修复，正确更新 Git 子模块，拉取子模块完整代码，解决子模块目录为空问题。
 | 原文链接：http://zhishi.c9hyko.asia/blog/4527542.sHtML

原标题：golang 系统设计 io 瓶颈磁盘网络优化实践
简介：灰度发布策略服务平滑升级，实现灰度发布逻辑，流量逐步切到新版本，出现问题快速回滚旧版本。
 | 原文链接：http://zhishi.c9hyko.asia/blog/5321995.sHtML

原标题：运维笔记：系统内核参数调优生产服务器
简介：消息队列重复消费业务处理，实现消息消费幂等，处理重复投递消息，保证多次消费业务结果一致。
 | 原文链接：http://zhishi.c9hyko.asia/blog/6106281.sHtML

原标题：GitHub 项目提交推送完整流程讲解
简介：数据库主从延迟业务兼容处理，业务适配主从复制延迟，避免读取从库拿到还未同步完成旧数据。
 | 原文链接：http://zhishi.c9hyko.asia/blog/8359100.sHtML

原标题：golang 系统设计 commit 提交规范约定
简介：golang go regexp 正则预编译，regexp.MustCompile 预编译正则，不要循环内部编译正则，节省 CPU。
 | 原文链接：http://zhishi.c9hyko.asia/blog/7541996.sHtML

原标题：golang 系统设计大文件上传架构
简介：golang net/url 路径拼接处理，url.ParseRequestURI 处理请求 url，正确拼接 url 路径避免拼接错误。
 | 原文链接：http://zhishi.c9hyko.asia/blog/2875528.sHtML

原标题：从零搭建本地开发环境完整教程
简介：golang 链路追踪简易实现方案，简易链路追踪实现，传递 traceId，记录调用链路，方便排查慢调用。
 | 原文链接：http://zhishi.c9hyko.asia/blog/5889640.sHtML

原标题：缓存过期打散防止缓存雪崩
简介：golang grpc metadata 元数据透传，metadata 传递 traceId、鉴权信息，全链路透传上下文信息。
 | 原文链接：http://zhishi.c9hyko.asia/blog/7244649.sHtML

原标题：实战：基于DockerCompose搭建本地开发栈
简介：golang go 服务压测前后性能对比，压测记录 QPS 延迟，优化前后对比，验证优化效果。
 | 原文链接：http://zhishi.c9hyko.asia/blog/7545161.sHtML

原标题：golang 系统设计内存高占用排查思路
简介：接口请求重试容错机制实现，封装请求重试逻辑，遇到临时网络故障自动重试，提升第三方调用稳定性。
 | 原文链接：http://zhishi.c9hyko.asia/blog/8159519.sHtML

原标题：Git 分支管理多人协作实战教程
简介：golang 大文件读取内存优化，Go 流式读取大文件，分块处理，避免大文件一次性加载全部到内存。
 | 原文链接：http://zhishi.c9hyko.asia/blog/3074159.sHtML

原标题：效率笔记：GitWorkflow团队协作规范模板
简介：Git 误删提交代码恢复找回，使用 Git reflog 工具找回被误删除提交记录，恢复误删除代码。
 | 原文链接：http://zhishi.c9hyko.asia/blog/9952220.sHtML

原标题：项目实践：实现数据脱敏组件支持多种脱敏规则
简介：慢查询分析索引调优数据库实战，抓取慢查询，分析执行计划，优化索引，解决数据库慢查询拖慢业务。
 | 原文链接：http://zhishi.c9hyko.asia/blog/9235991.sHtML

原标题：手写简易 MQ 理解消息存储消费
简介：git cherry‑pick 规范操作防 bug，规范 cherry‑pick 使用流程，处理冲突，避免错误引入不兼容代码。
 | 原文链接：http://zhishi.c9hyko.asia/blog/2365168.sHtML

原标题：golang 系统设计 api 网关核心能力梳理
简介：golang 雪花算法 workId 自动获取，自动获取机器 workId，不用手动配置，简化分布式 id 部署。
 | 原文链接：http://zhishi.c9hyko.asia/blog/7414115.sHtML

原标题：golang k8s 日志收集 efk 简单架构
简介：后端分页查询逻辑代码实现，编写后端分页接口，处理页码、每页条数参数，优化大数据量查询返回结果。
 | 原文链接：http://zhishi.c9hyko.asia/blog/4648769.sHtML

原标题：golang docker 运行 etcd 本地测试
简介：golang 滑动窗口限流算法 go 实现，滑动窗口限流，解决固定窗口临界流量突增漏洞，限流更精准。
 | 原文链接：http://zhishi.c9hyko.asia/blog/7769781.sHtML

原标题：GC 垃圾回收优化降低 CPU 占用
简介：数据库排序规则统一结果一致，统一数据库表排序规则，解决不同环境查询排序结果不一致问题。
 | 原文链接：http://zhishi.c9hyko.asia/blog/7839542.sHtML

原标题：开发记录：实现完整用户登录鉴权业务模块
简介：跨平台 uniapp 多端开发实操，uniapp 开发一套代码，编译多端，梳理多端差异处理与适配技巧。
 | 原文链接：http://zhishi.c9hyko.asia/blog/1818677.sHtML

原标题：快速上手简单信号处理脚本编写
简介：游标分页大数据查询性能提升，使用游标分页替代偏移分页，解决大数据 offset 分页性能越来越差问题。
 | 原文链接：http://zhishi.c9hyko.asia/blog/2570952.sHtML

原标题：新手教程：本地项目初始化gitignore配置
简介：golang 优雅处理 http 重定向逻辑，自定义控制 http 重定向跳转次数，防止无限重定向死循环。
 | 原文链接：http://zhishi.c9hyko.asia/blog/9291698.sHtML

原标题：全局时间标准统一逻辑错乱修复
简介：golang 高并发下锁优化减少竞争，减小锁粒度，读写锁替换互斥锁，无锁编程降低锁竞争开销。
 | 原文链接：http://zhishi.c9hyko.asia/blog/2749733.sHtML

原标题：Practice：实现接口mock动态返回不同响应
简介：golang go 爬虫代理池轮换使用，http 代理池轮换，请求自动切换代理 IP，突破访问限制。
 | 原文链接：http://zhishi.c9hyko.asia/blog/6509720.sHtML

原标题：开发记录：搭建CI/CD流水线自动构建部署项目
简介：数据库死锁成因规避方案，讲解数据库死锁产生条件，给出业务层面规避手段，减少死锁事件发生。
 | 原文链接：http://zhishi.c9hyko.asia/blog/8943652.sHtML

原标题：golang 系统设计配置本地缓存降级策略方案
简介：nodejs 项目 pm2 部署运维指南，使用 PM2 管理 Node 服务，进程守护、日志、重启，线上部署运维实操。
 | 原文链接：http://zhishi.c9hyko.asia/blog/9725085.sHtML

原标题：golang 系统设计配置灰度下发简单实现思路
简介：业务错误码完整落地实践，落地完整业务错误码，枚举全部业务异常，统一返回，配套文档说明。
 | 原文链接：http://zhishi.c9hyko.asia/blog/1121592.sHtML

原标题：排错：反向代理后获取真实IP全部变成内网IP
简介：golang defer 执行顺序与坑点，defer 后进先出，循环内部 defer 陷阱，资源释放正确写法。
 | 原文链接：http://zhishi.c9hyko.asia/blog/6798222.sHtML

原标题：Issue：容器日志驱动配置错误日志全部丢失
简介：golang trace 工具采集 go 程序执行轨迹，go trace 采集程序完整调度轨迹，分析协程调度阻塞问题。
 | 原文链接：http://zhishi.c9hyko.asia/blog/0038831.sHtML

原标题：全局异常处理器接口返回统一
简介：golang context.WithValue 传递元数据，WithValue 只传 traceId 鉴权元数据，不要传业务大对象。
 | 原文链接：http://zhishi.c9hyko.asia/blog/9569246.sHtML

四、架构设计｜Architecture
原标题：GraphQL 接口查询优化实操
简介：移动端适配 rem vw 方案对比，对比 rem 与 vw 移动端适配方案，分析优缺点，给出选型建议。
 | 原文链接：http://zhishi.c9hyko.asia/blog/5428537.sHtML

原标题：golang 系统设计接口向前兼容改造实操
简介：分布式任务调度集群原型开发，开发简易分布式调度原型，集群多节点运行，保证任务只执行一次。
 | 原文链接：http://zhishi.c9hyko.asia/blog/3050658.sHtML

原标题：WebSocket 双向通信 demo 开发
简介：golang go 变量逃逸场景汇总，切片、指针、返回局部变量引发逃逸，变量分配到堆影响 GC。
 | 原文链接：http://zhishi.c9hyko.asia/blog/3340562.sHtML

原标题：Issue：CI脚本超时，构建任务无故终止
简介：golang os 文件权限 mode，os.FileMode 文件权限，读写执行权限位，跨平台权限注意事项。
 | 原文链接：http://zhishi.c9hyko.asia/blog/1558200.sHtML

原标题：MySQL 慢查询索引优化实战
简介：golang go 输入数据校验防御，所有外部入参严格校验长度格式，防止恶意输入造成业务异常。
 | 原文链接：http://zhishi.c9hyko.asia/blog/2183381.sHtML

原标题：golang 系统设计依赖版本升级风险评估
简介：Docker 容器入门镜像实操教程，介绍 Docker 基础概念，演示镜像拉取、容器启停，帮助新手建立容器化开发认知。
 | 原文链接：http://zhishi.c9hyko.asia/blog/8690741.sHtML

原标题：Practice：模拟第三方接口超时服务降级验证
简介：golang makefile 多平台编译脚本，makefile 一键交叉编译多平台二进制，打包镜像，执行测试。
 | 原文链接：http://zhishi.c9hyko.asia/blog/4911423.sHtML

原标题：实战：容器内执行调试排错完整实操流程
简介：golang gin 路由分组权限管控，Gin 路由分组，不同分组绑定鉴权中间件，实现接口权限分组管控。
 | 原文链接：http://zhishi.c9hyko.asia/blog/7220588.sHtML

原标题：golang excel 简单读写操作示例
简介：golang grpc metadata 元数据透传，metadata 传递 traceId、鉴权信息，全链路透传上下文信息。
 | 原文链接：http://zhishi.c9hyko.asia/blog/0411860.sHtML

原标题：Hands‑on：简易布隆过滤器实现与测试验证
简介：文件监控服务自动重启开发，监控项目文件变更，代码修改自动重启服务，提升本地开发调试效率。
 | 原文链接：http://zhishi.c9hyko.asia/blog/4813798.sHtML

原标题：安全笔记：CORS跨域配置错误安全风险
简介：golang 配置文件多环境加载，Go 多环境配置加载实现，读取配置文件环境变量，适配多套运行环境。
 | 原文链接：http://zhishi.c9hyko.asia/blog/8362710.sHtML

原标题：golang 系统设计缓存优化落地实操指南
简介：golang mongodb 索引优化慢查询处理，mongodb 创建索引，分析慢查询，优化聚合查询执行性能。
 | 原文链接：http://zhishi.c9hyko.asia/blog/9664552.sHtML

原标题：从零搭建简单CLI命令行工具
简介：CPU 亲和性配置负载均衡调度，配置进程 CPU 亲和，均衡利用多核 CPU，优化程序调度性能。
 | 原文链接：http://zhishi.c9hyko.asia/blog/4842230.sHtML

原标题：golang docker 容器资源限制设置
简介：golang 内存持续上涨定位思路，区分内存泄漏、缓存占用、GC 参数不合理，分步定位内存持续走高。
 | 原文链接：http://zhishi.c9hyko.asia/blog/6397940.sHtML

原标题：golang 系统设计压测指标确定与分析
简介：golang go 服务蓝绿发布实践思路，蓝绿两套实例，流量一键切换，回滚快速降低发布风险。
 | 原文链接：http://zhishi.c9hyko.asia/blog/9217127.sHtML

原标题：实战项目：GitHubAction自动测试构建实践
简介：Shell 脚本自动化命令编写，讲解 Shell 基础语法，编写自动化脚本，完成批量执行、文件处理，解放重复手工操作。
 | 原文链接：http://zhishi.c9hyko.asia/blog/2091758.sHtML

原标题：复盘总结：接口重构兼容旧版本改造复盘
简介：数值 key 浮点匹配异常规避，避免浮点数作为 Redis 等存储的 key，防止精度问题引发 key 匹配失败。
 | 原文链接：http://zhishi.c9hyko.asia/blog/5408960.sHtML

原标题：踩坑：大报文传输，RPC消息超过大小限制
简介：golang go 输入数据校验防御，所有外部入参严格校验长度格式，防止恶意输入造成业务异常。
 | 原文链接：http://zhishi.c9hyko.asia/blog/4966136.sHtML

?
