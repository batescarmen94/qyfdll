最新前沿技术资讯

一、入门教程｜Getting Started
原标题：TCP 长连接参数优化 TIME_WAIT
简介：缓存过期策略优化防业务故障，合理设置缓存过期策略，规避集中过期，减少缓存失效带来业务抖动。
 | 原文链接：http://wiki.m9zpbz.asia/arts/222821.Doc

原标题：踩坑：重试逻辑未做幂等，重复生成业务数据
简介：大事务拆分回滚日志暴涨解决，拆分大型数据库事务，减少回滚日志生成量，避免磁盘被回滚日志占满。
 | 原文链接：http://wiki.m9zpbz.asia/arts/716985.Doc

原标题：消息队列消费堆积扩容处理
简介：golang 信号捕获程序退出处理，Go 捕获操作系统信号，做资源回收，控制程序退出流程。
 | 原文链接：http://wiki.m9zpbz.asia/arts/559553.Doc

原标题：运维笔记：服务器磁盘内存监控告警配置
简介：golang goroutine 泄露常见场景汇总，channel 阻塞、context 忘记取消，导致协程无法退出发生泄露。
 | 原文链接：http://wiki.m9zpbz.asia/arts/067250.Doc

原标题：日志敏感信息脱敏泄露防护
简介：golang go mod why 查询依赖引入原因，go mod why 查询为什么引入某个包，理清依赖来源。
 | 原文链接：http://wiki.m9zpbz.asia/arts/485466.Doc

原标题：架构笔记：多环境隔离架构开发测试生产隔离
简介：nodejs 日志轮转生产环境配置，配置 Node 日志轮转切割，防止日志文件无限变大，适配生产环境。
 | 原文链接：http://wiki.m9zpbz.asia/arts/422518.Doc

原标题：Issue：容器日志驱动配置错误日志全部丢失
简介：代理 HTTPS 证书访问异常处理，配置代理根证书，解决代理环境 HTTPS 证书校验失败无法访问外网。
 | 原文链接：http://wiki.m9zpbz.asia/arts/042437.Doc

原标题：设计思考：分布式ID系统架构选型对比
简介：golang gorm 软删除实现逻辑，Gorm 开启软删除，删除数据仅标记，数据保留可恢复，满足业务数据留存。
 | 原文链接：http://wiki.m9zpbz.asia/arts/525817.Doc

原标题：手写简易 RPC 服务通信原型
简介：golang 字符编码转换 go 处理，iconv‑go 做编码转换 gbk utf8 互转，处理老旧系统 gbk 编码数据。
 | 原文链接：http://wiki.m9zpbz.asia/arts/140058.Doc

原标题：golang 系统设计缓存过期时间设置原则梳理
简介：业务幂等键设计防重复逻辑，讲解幂等键设计思路，选择合适业务字段作为幂等标识，实现可靠防重复。
 | 原文链接：http://wiki.m9zpbz.asia/arts/782685.Doc

原标题：express 中间件开发业务实践
简介：本地运行正常线上报错排查，对比本地与线上环境差异，从配置、系统版本、文件权限定位线上独有的 bug。
 | 原文链接：http://wiki.m9zpbz.asia/arts/713089.Doc

原标题：Hands‑on：简易网关路由转发组件开发
简介：nodejs 事件循环机制完整讲解，拆解 Node.js 事件循环各个阶段，理解异步回调执行顺序。
 | 原文链接：http://wiki.m9zpbz.asia/arts/415617.Doc

原标题：golang 系统设计压测指标 qps rt 错误率讲解
简介：golang tcp keepalive 参数程序配置，go 程序设置 tcp keepalive，操作系统 tcp 保活参数，清理僵死连接。
 | 原文链接：http://wiki.m9zpbz.asia/arts/498152.Doc

原标题：性能笔记：HTTP连接复用性能优化实践
简介：golang go 容器 heap 堆实现优先队列，实现 heap 接口，构建优先队列，任务优先级调度。
 | 原文链接：http://wiki.m9zpbz.asia/arts/787324.Doc

原标题：记一次内存Swap被大量使用系统响应缓慢
简介：时间同步修复令牌提前过期，服务器时间不同步导致 JWT 令牌提前过期，同步系统时间解决异常。
 | 原文链接：http://wiki.m9zpbz.asia/arts/275095.Doc

原标题：调优方案：静态资源缓存头Cache‑Control优化
简介：golang benchmark 参数‑bench‑mem 统计内存分配，benchmark 开启内存统计，观察内存分配次数大小。
 | 原文链接：http://wiki.m9zpbz.asia/arts/046503.Doc

原标题：DevOps：Docker镜像安全扫描集成CI流程
简介：后端分页查询逻辑代码实现，编写后端分页接口，处理页码、每页条数参数，优化大数据量查询返回结果。
 | 原文链接：http://wiki.m9zpbz.asia/arts/339664.Doc

原标题：新手向：开源项目依赖安装失败排查
简介：golang url 参数编码处理方案，Go URL 参数编码解码，处理特殊字符，避免 URL 参数错乱。
 | 原文链接：http://wiki.m9zpbz.asia/arts/697571.Doc

原标题：优化实践：接口返回字段裁剪减少报文大小
简介：golang go sum 校验失败处理方案，go sum 校验不匹配，排查网络代理，清理缓存解决校验报错。
 | 原文链接：http://wiki.m9zpbz.asia/arts/663326.Doc

原标题：数据库排序规则统一结果一致
简介：批量数据处理脚本编写技巧，编写脚本批量处理大量业务数据，循环处理、分批执行，提升数据处理效率。
 | 原文链接：http://wiki.m9zpbz.asia/arts/962153.Doc

原标题：Debug：长连接未设置心跳，连接僵死不回收
简介：项目构建脚本编译打包解析，解读项目构建脚本，理清编译、压缩、资源复制流程，理解打包后产物如何生成。
 | 原文链接：http://wiki.m9zpbz.asia/arts/025146.Doc

原标题：预编译 SQL 防注入实现
简介：Git 误提交撤销回退实操教程，演示多种撤销提交方式，区分已经推送远程和本地未提交场景，处理误提交代码。
 | 原文链接：http://wiki.m9zpbz.asia/arts/760402.Doc

原标题：WSL 搭建 Windows Linux 开发环境
简介：golang 大文件读取内存优化，Go 流式读取大文件，分块处理，避免大文件一次性加载全部到内存。
 | 原文链接：http://wiki.m9zpbz.asia/arts/405403.Doc

原标题：golang 系统设计唯一索引业务使用场景
简介：golang rate 令牌桶限流器源码理解，拆解令牌桶限流核心逻辑，理解令牌生成消耗，掌握限流底层原理。
 | 原文链接：http://wiki.m9zpbz.asia/arts/217678.Doc

原标题：Hands‑on：简易配置热更新组件开发实践
简介：定时任务周期调度 demo 开发，实现简单定时调度程序，按时间周期执行业务逻辑，理解定时任务运行机制。
 | 原文链接：http://wiki.m9zpbz.asia/arts/641826.Doc

原标题：Hands‑on：编写自定义Git钩子实现代码提交校验
简介：CDN 缓存刷新获取最新静态资源，调用 CDN 刷新接口，清除节点旧缓存，用户访问到更新后的静态文件。
 | 原文链接：http://wiki.m9zpbz.asia/arts/667395.Doc

原标题：golang 系统设计网关限流熔断降级配置思路
简介：Git 子模块更新代码不全修复，正确更新 Git 子模块，拉取子模块完整代码，解决子模块目录为空问题。
 | 原文链接：http://wiki.m9zpbz.asia/arts/951201.Doc

原标题：项目实践：定时任务防重复执行落地实践
简介：golang redis geo 地理位置存储查询，Redis GEO 存储经纬度，查询附近点位，实现附近人业务功能。
 | 原文链接：http://wiki.m9zpbz.asia/arts/489486.Doc

原标题：Issue：连接池参数不合理，大量连接被耗尽
简介：OpenAPI 自动接口文档生成，集成 OpenAPI 工具，自动扫描代码生成接口文档，减少文档维护成本。
 | 原文链接：http://wiki.m9zpbz.asia/arts/579705.Doc

原标题：golang es 分词器选型业务适配
简介：线程调度优化减少上下文切换，优化线程数量，减少线程频繁切换，降低 CPU 上下文切换开销。
 | 原文链接：http://wiki.m9zpbz.asia/arts/245063.Doc

原标题：排错：GitLFS大文件推送失败完整排障
简介：golang bcrypt 密码哈希加密存储，bcrypt 做用户密码哈希，加盐存储密码，保障用户密码安全。
 | 原文链接：http://wiki.m9zpbz.asia/arts/376153.Doc

原标题：SSH 密钥配置 GitHub 免密登录
简介：golang go xml 解析生成 xml 文档，encoding/xml 解析 xml，结构体标签映射 xml 节点属性。
 | 原文链接：http://wiki.m9zpbz.asia/arts/089621.Doc

原标题：图片上传预览格式大小处理
简介：golang 程序崩溃 core dump 生成调试，开启 core dump，程序崩溃生成转储文件，事后分析崩溃原因。
 | 原文链接：http://wiki.m9zpbz.asia/arts/595439.Doc

原标题：golang 系统设计 protobuf oneof 类型业务场景
简介：golang aes cbc gcm 模式加密对比，AES‑CBC AES‑GCM 模式加密解密，理解两种模式差异选型。
 | 原文链接：http://wiki.m9zpbz.asia/arts/372686.Doc

原标题：开发复盘：避免大报文导致服务OOM优化实践
简介：超大数据集分页性能优化方案，对比不同分页方案，针对海量数据集做分页性能优化，解决越翻越慢。
 | 原文链接：http://wiki.m9zpbz.asia/arts/633723.Doc

原标题：避坑：批量操作未分批次，一次性内存打爆
简介：SDK 版本兼容线上崩溃修复，处理 SDK 版本升级之后线上崩溃，定位 API 变更，做版本兼容适配改造。
 | 原文链接：http://wiki.m9zpbz.asia/arts/950167.Doc

原标题：golang 系统设计日志检索排查线上问题实操技巧
简介：golang feishu 飞书机器人消息发送，调用飞书 webhook 机器人，发送文本卡片消息，实现业务告警通知。
 | 原文链接：http://wiki.m9zpbz.asia/arts/975581.Doc

原标题：golang 系统设计消息发送确认机制配置实操
简介：nodejs 项目 pm2 部署运维指南，使用 PM2 管理 Node 服务，进程守护、日志、重启，线上部署运维实操。
 | 原文链接：http://wiki.m9zpbz.asia/arts/440216.Doc

原标题：多操作系统开发兼容处理
简介：读懂开源项目 README 实用技巧，教你快速解析开源项目说明文档，提取安装、运行、配置关键信息，快速上手项目。
 | 原文链接：http://wiki.m9zpbz.asia/arts/274999.Doc

原标题：数据库读写分离性能优化
简介：golang sync.WaitGroup 协程等待控制，WaitGroup 控制一组协程等待全部执行完成，完成批量协程任务调度。
 | 原文链接：http://wiki.m9zpbz.asia/arts/770357.Doc


二、踩坑排错｜Troubleshooting
原标题：方案对比：几种分布式限流算法架构适用性
简介：环境变量不生效问题修复，排查环境变量加载顺序、作用域问题，修复环境变量读取不到的异常。
 | 原文链接：http://wiki.m9zpbz.asia/arts/782435.Doc

原标题：Debug：分页偏移量过大数据库查询性能暴跌
简介：集成测试业务流程编写示例，编写业务流程集成测试，覆盖完整业务链路，验证模块之间协同工作是否正常。
 | 原文链接：http://wiki.m9zpbz.asia/arts/933848.Doc

原标题：设计思考：缓存分层架构设计与失效处理策略
简介：css 变量主题切换方案实现，使用 CSS 变量实现网页主题切换，多套主题样式快速切换无需大量 CSS。
 | 原文链接：http://wiki.m9zpbz.asia/arts/591068.Doc

原标题：Hands‑on：简易请求转发代理中间件实现
简介：golang go 第三方库选型评估要点，评估库活跃度维护情况、性能、依赖数量，选择合适开源库。
 | 原文链接：http://wiki.m9zpbz.asia/arts/055251.Doc

原标题：Hands‑on：手写简易ORM框架理解底层原理
简介：灰度发布策略服务平滑升级，实现灰度发布逻辑，流量逐步切到新版本，出现问题快速回滚旧版本。
 | 原文链接：http://wiki.m9zpbz.asia/arts/608694.Doc

原标题：golang 系统设计 pr 评审合并完整流程
简介：golang gitlab ci go 项目流水线编写，gitlab ci 流水线执行单元测试、静态检查、构建推送镜像。
 | 原文链接：http://wiki.m9zpbz.asia/arts/484449.Doc

原标题：安全复盘：业务数据脱敏防止泄露实践
简介：golang go 测试文件命名规范，_test.go 测试文件，TestXxx 单元测试函数命名规范。
 | 原文链接：http://wiki.m9zpbz.asia/arts/959248.Doc

原标题：golang 系统设计开源项目 issue pr 模板编写
简介：数据库主从延迟业务兼容处理，业务适配主从复制延迟，避免读取从库拿到还未同步完成旧数据。
 | 原文链接：http://wiki.m9zpbz.asia/arts/842397.Doc

原标题：golang 消息死信处理业务逻辑
简介：读懂开源项目 README 实用技巧，教你快速解析开源项目说明文档，提取安装、运行、配置关键信息，快速上手项目。
 | 原文链接：http://wiki.m9zpbz.asia/arts/414701.Doc

原标题：超大数据集分页性能优化方案
简介：多环境配置中心灵活切换方案，简易配置中心实现，支持多套环境配置，动态下发无需重启服务。
 | 原文链接：http://wiki.m9zpbz.asia/arts/493638.Doc

原标题：Troubleshooting：依赖安装失败完整排查清单
简介：线程调度优化减少上下文切换，优化线程数量，减少线程频繁切换，降低 CPU 上下文切换开销。
 | 原文链接：http://wiki.m9zpbz.asia/arts/459810.Doc

原标题：安全笔记：请求头伪造IP漏洞防护
简介：内网测试服务搭建团队调试，配置本地服务内网可访问，团队成员能够访问调试，方便前后端联调与内部演示。
 | 原文链接：http://wiki.m9zpbz.asia/arts/560667.Doc

原标题：golang 系统设计缓存基准测试对比方案
简介：golang interface {} 类型断言类型转换，类型断言 ok 模式，避免断言失败触发 panic。
 | 原文链接：http://wiki.m9zpbz.asia/arts/178847.Doc

原标题：golang 系统设计接口参数防篡改校验
简介：Redis 大 key 拆分集群卡顿解决，拆分 Redis 超大 Key，避免大 key 操作造成 Redis 集群卡顿阻塞。
 | 原文链接：http://wiki.m9zpbz.asia/arts/568292.Doc

原标题：GET POST 接口请求参数处理
简介：文件句柄上限调整上传随机失败，调高系统文件句柄上限，解决高并发上传场景随机打开文件失败。
 | 原文链接：http://wiki.m9zpbz.asia/arts/232090.Doc

原标题：安全实践：敏感信息加密存储传输完整方案
简介：golang go 程序版本号内置编译注入，编译时注入 git commit 版本号，程序运行输出版本便于排查。
 | 原文链接：http://wiki.m9zpbz.asia/arts/788683.Doc

原标题：方案设计：接口版本管理架构向前兼容策略
简介：golang redis 客户端业务使用，Go Redis 客户端对接，实现缓存、计数器，适配各类 Redis 业务场景。
 | 原文链接：http://wiki.m9zpbz.asia/arts/188499.Doc

原标题：新手参与开源社区贡献指南
简介：golang go 泛型约束与类型集合，泛型 type set 约束，限制泛型支持类型，写出安全泛型代码。
 | 原文链接：http://wiki.m9zpbz.asia/arts/424056.Doc

原标题：golang redis 五种数据结构实战
简介：golang multipart 表单文件上传解析，服务端解析 multipart 表单，获取上传文件与表单字段。
 | 原文链接：http://wiki.m9zpbz.asia/arts/347063.Doc

原标题：踩坑：重试逻辑未做幂等，重复生成业务数据
简介：大文件导出内存溢出防护，流式处理大文件导出，边读边写，不把全部数据加载内存，规避 OOM。
 | 原文链接：http://wiki.m9zpbz.asia/arts/354863.Doc

原标题：实践：大文件分片上传后端完整实现思路
简介：图片上传预览格式大小处理，实现图片上传接口，校验文件格式、大小，完成上传后预览处理。
 | 原文链接：http://wiki.m9zpbz.asia/arts/074526.Doc

原标题：golang 系统设计线上问题复现思路简单讲解
简介：读懂开源项目 README 实用技巧，教你快速解析开源项目说明文档，提取安装、运行、配置关键信息，快速上手项目。
 | 原文链接：http://wiki.m9zpbz.asia/arts/773640.Doc

原标题：方案设计：异步解耦业务架构边界识别
简介：golang sync/atomic 原子操作使用注意，理解原子操作内存顺序，规避原子操作错误使用带来 bug。
 | 原文链接：http://wiki.m9zpbz.asia/arts/858379.Doc

原标题：安全实践：敏感信息加密存储传输完整方案
简介：nodejs jwt 登录鉴权完整示例，Node 实现 JWT 登录鉴权，登录签发令牌，接口校验令牌身份。
 | 原文链接：http://wiki.m9zpbz.asia/arts/347620.Doc

原标题：部署复盘：容器OOM问题完整排查流程
简介：golang redis hyperloglog 基数统计，hyperloglog 统计 UV 基数，海量数据去重统计，极低内存开销。
 | 原文链接：http://wiki.m9zpbz.asia/arts/075164.Doc

原标题：开发记录：容器日志标准输出采集实践方案
简介：移动端适配 rem vw 方案对比，对比 rem 与 vw 移动端适配方案，分析优缺点，给出选型建议。
 | 原文链接：http://wiki.m9zpbz.asia/arts/717190.Doc

原标题：实战项目：WSL开发环境完整配置实操
简介：项目语义化版本号规范管理，遵循语义化版本规范管理项目版本，明确主次版本变更含义。
 | 原文链接：http://wiki.m9zpbz.asia/arts/269628.Doc

原标题：Architecture：配置中心架构，动态配置设计思路
简介：golang url 参数编码处理方案，Go URL 参数编码解码，处理特殊字符，避免 URL 参数错乱。
 | 原文链接：http://wiki.m9zpbz.asia/arts/399070.Doc

原标题：golang 系统设计监控体系指标分类方法论梳理
简介：golang grpc 双向流双向通信开发，grpc 双向流，服务端客户端持续互发消息，长连接流式业务场景。
 | 原文链接：http://wiki.m9zpbz.asia/arts/932466.Doc

原标题：golang 系统设计压测环境隔离避免影响生产
简介：gRPC 服务端客户端入门示例，搭建 gRPC 服务端与调用客户端，学习 protobuf 定义，掌握 RPC 基础开发流程。
 | 原文链接：http://wiki.m9zpbz.asia/arts/773298.Doc

原标题：golang redis zset 排行榜业务实现
简介：git rebase 整理提交历史实操，使用 rebase 整理杂乱提交记录，将多条提交合并，保持 git 提交历史干净线性。
 | 原文链接：http://wiki.m9zpbz.asia/arts/634523.Doc

原标题：Hands‑on：简易ID生成雪花算法完整实现
简介：webpack chunk 分包策略详解，讲解 webpack chunk 分包策略，拆分第三方包与业务代码，优化缓存复用。
 | 原文链接：http://wiki.m9zpbz.asia/arts/402983.Doc

原标题：复盘总结：技术选型对比文档模板实践
简介：golang context.WithCancel 手动取消上下文，WithCancel 生成可取消 ctx，手动调用 cancel 触发取消。
 | 原文链接：http://wiki.m9zpbz.asia/arts/158059.Doc

原标题：golang 系统设计用户签到统计方案
简介：golang 定时任务任务持久化存储，定时任务持久化到数据库，服务重启任务不丢失，动态管理任务。
 | 原文链接：http://wiki.m9zpbz.asia/arts/394666.Doc

原标题：实践：数据库回滚点业务调试实践
简介：nodejs 中间件模式原理剖析，拆解 Node 中间件设计模式，理解请求逐层处理流转的底层原理。
 | 原文链接：http://wiki.m9zpbz.asia/arts/192998.Doc

原标题：Security：文件上传漏洞攻击面完整防护方案
简介：golang 优雅处理 http 超时设置，Go HTTP 请求设置各类超时，防止请求无限阻塞，保护协程与连接。
 | 原文链接：http://wiki.m9zpbz.asia/arts/050167.Doc

原标题：线程池拒绝策略任务丢失防护
简介：文件编码统一随机乱码修复，统一项目全部文件读写编码，消除随机中文乱码，保证文本处理稳定。
 | 原文链接：http://wiki.m9zpbz.asia/arts/377698.Doc

原标题：开发记录：接口请求日志记录完整中间件实现
简介：分布式 ID 全局唯一生成方案，讲解分布式 ID 生成思路，实现全局唯一 ID，满足分布式系统主键生成需求。
 | 原文链接：http://wiki.m9zpbz.asia/arts/695516.Doc

原标题：设计思考：大促系统架构压测改造整体思路
简介：限流组件计数器令牌桶模式实现，实现计数器、令牌桶两种限流算法，封装可复用限流组件。
 | 原文链接：http://wiki.m9zpbz.asia/arts/152819.Doc

原标题：golang k8s 滚动更新回滚策略
简介：golang gin 路由分组权限管控，Gin 路由分组，不同分组绑定鉴权中间件，实现接口权限分组管控。
 | 原文链接：http://wiki.m9zpbz.asia/arts/159338.Doc

三、实战开发｜Practice
原标题：golang redis 事务 multi exec 使用
简介：磁盘 inode 耗尽文件创建失败，排查磁盘 inode 占用，清理大量小文件，恢复文件创建能力。
 | 原文链接：http://wiki.m9zpbz.asia/arts/374460.Doc

原标题：golang 系统设计依赖版本升级风险评估
简介：react hooks 常见陷阱避坑指南，梳理 React Hooks 高频踩坑点，依赖数组、闭包陷阱，写出稳定组件。
 | 原文链接：http://wiki.m9zpbz.asia/arts/373084.Doc

原标题：限流窗口绕过漏洞修复方案
简介：golang os 主机名内核版本读取，os 读取主机名，内核信息，操作系统版本，获取运行环境信息。
 | 原文链接：http://wiki.m9zpbz.asia/arts/901709.Doc

原标题：架构复盘：数据库索引架构设计原则与边界
简介：golang wasm 浏览器 js 交互，go wasm 与 js 互相调用，浏览器端 go 程序操作 dom 调用 js 函数。
 | 原文链接：http://wiki.m9zpbz.asia/arts/047138.Doc

原标题：WSL 文件权限访问异常修复
简介：前后端会话登录状态持久化，实现登录状态持久存储，重启服务登录状态不丢失，保障会话稳定性。
 | 原文链接：http://wiki.m9zpbz.asia/arts/569505.Doc

原标题：开发环境变量配置全平台教程
简介：golang 数据库连接耗尽排查思路，监控连接池状态，定位连接未归还，解决连接耗尽报错。
 | 原文链接：http://wiki.m9zpbz.asia/arts/121242.Doc

原标题：架构复盘：网关层、应用层、数据库层层限流架构
简介：golang io.Copy 流式拷贝数据，io.Copy 拷贝 reader 到 writer，不用加载全部数据到内存。
 | 原文链接：http://wiki.m9zpbz.asia/arts/787335.Doc

原标题：DevOps：制品仓库管理二进制产物版本
简介：golang 微服务网关简易实现，http 反向代理、路由匹配、鉴权限流，理解网关核心原理。
 | 原文链接：http://wiki.m9zpbz.asia/arts/469853.Doc

原标题：安全实践：最小权限原则数据库账号管控
简介：golang 分布式事务 seata go 客户端，seata‑go 实现分布式事务，保证跨库业务数据最终一致性。
 | 原文链接：http://wiki.m9zpbz.asia/arts/369409.Doc

原标题：golang 系统设计全局异常处理器实现
简介：golang go‑fuzz 模糊测试开发，go fuzz 模糊测试，自动构造异常输入，发现代码隐藏 bug。
 | 原文链接：http://wiki.m9zpbz.asia/arts/932659.Doc

原标题：golang kafka 消费者组原理讲解
简介：nodejs 流处理大文件不占内存，使用 Node.js 流处理超大文件，边读边写，不需要全部加载进内存。
 | 原文链接：http://wiki.m9zpbz.asia/arts/290650.Doc

原标题：架构复盘：限流系统架构防止恶意流量冲击
简介：golang http 服务性能优化调参，调优 Go HTTP 服务参数，调整连接池，提升服务并发吞吐能力。
 | 原文链接：http://wiki.m9zpbz.asia/arts/034396.Doc

原标题：Practice：实现接口签名、验签完整示例代码
简介：任务执行锁防止并发重复调度，增加任务执行锁，多实例环境，防止同一个定时任务并发多次运行。
 | 原文链接：http://wiki.m9zpbz.asia/arts/613951.Doc

原标题：golang 系统设计分库分表中间件思路
简介：golang 系统调用跟踪 strace 排查 go 程序，strace 跟踪系统调用，定位文件网络 IO 慢的底层原因。
 | 原文链接：http://wiki.m9zpbz.asia/arts/978939.Doc

原标题：golang k8s 本地 minikube 调试应用
简介：golang 进程信号捕获 SIGUSR 自定义信号，捕获用户自定义信号，实现线上不重启触发调试、日志切换。
 | 原文链接：http://wiki.m9zpbz.asia/arts/011555.Doc

原标题：golang 结构体深拷贝几种实现
简介：golang nacos go 客户端配置服务发现，nacos‑go 对接 nacos，配置管理、微服务注册发现。
 | 原文链接：http://wiki.m9zpbz.asia/arts/933335.Doc

原标题：开发记录：分布式锁超时业务安全处理实践
简介：golang mime 类型检测文件，mime 识别文件 mime 类型，设置 http 响应 Content‑Type。
 | 原文链接：http://wiki.m9zpbz.asia/arts/898255.Doc

原标题：Issue：CI脚本超时，构建任务无故终止
简介：golang hystrix 模式简易熔断实现，简易熔断组件，错误率达到阈值触发熔断，快速失败保护下游。
 | 原文链接：http://wiki.m9zpbz.asia/arts/373118.Doc

原标题：架构复盘：多级缓存架构，本地缓存+分布式缓存
简介：golang 读写分离 gorm 实现主从切换，gorm 配置主库写入从库查询，读写分离分担数据库查询压力。
 | 原文链接：http://wiki.m9zpbz.asia/arts/019751.Doc

原标题：express 中间件开发业务实践
简介：百万数据 Excel 导出内存优化，优化大 Excel 导出逻辑，流式输出，避免一次性加载全部数据造成 OOM。
 | 原文链接：http://wiki.m9zpbz.asia/arts/162434.Doc

原标题：新手向：配置项目eslint/prettier代码格式化
简介：不必要字符转义关闭业务异常，关闭多余自动转义逻辑，防止业务数据被错误转义，破坏原始数据。
 | 原文链接：http://wiki.m9zpbz.asia/arts/146486.Doc

原标题：golang 系统设计数据库表设计通用规范模板
简介：依赖安装失败全方位排错，从网络、镜像源、权限、版本多角度，定位依赖安装失败，给出对应修复手段。
 | 原文链接：http://wiki.m9zpbz.asia/arts/922156.Doc

原标题：Debug：分页偏移量过大数据库查询性能暴跌
简介：golang 分库分表 id 路由规则设计，分库分表 id 路由算法，id 映射库表，数据均匀打散避免热点分片。
 | 原文链接：http://wiki.m9zpbz.asia/arts/664175.Doc

原标题：单元测试用例编写入门实操
简介：nodejs 多进程任务分发处理，多进程拆分处理 CPU 密集任务，主进程分发任务，利用多核提升处理速度。
 | 原文链接：http://wiki.m9zpbz.asia/arts/120611.Doc

原标题：Hands‑on：模拟RPC超时重试业务异常场景
简介：golang go proxy 私有代理配置，配置 go proxy 私有代理，加速依赖下载，内网环境构建项目。
 | 原文链接：http://wiki.m9zpbz.asia/arts/552064.Doc

原标题：部署复盘：容器OOM问题完整排查流程
简介：golang go ring 环形容器循环队列，ring 环形链表实现循环队列，环形缓冲区业务场景。
 | 原文链接：http://wiki.m9zpbz.asia/arts/991289.Doc

原标题：前端打包分包加载提速方案
简介：线上接口超时故障排查思路，从网络、数据库、代码逻辑逐层排查接口超时，定位慢请求根因。
 | 原文链接：http://wiki.m9zpbz.asia/arts/776819.Doc

原标题：Cookie 跨环境登录配置调整
简介：代码格式化工具团队统一风格，接入格式化工具，统一全团队代码书写风格，减少格式类 git 冲突。
 | 原文链接：http://wiki.m9zpbz.asia/arts/199278.Doc

原标题：golang 大文件读取内存优化
简介：golang os.Signal 信号监听完整示例，signal.Notify 监听信号，缓冲 channel 防止信号丢失。
 | 原文链接：http://wiki.m9zpbz.asia/arts/963105.Doc

原标题：golang 系统设计消息幂等消费去重实现方案
简介：golang rabbitmq go 客户端生产消费，streadway/amqp 实现 rabbitmq 生产者消费者，队列交换机绑定。
 | 原文链接：http://wiki.m9zpbz.asia/arts/161197.Doc

原标题：golang 系统设计内部 rpc 接口设计原则梳理
简介：前后端交互跨域问题完整处理，讲解跨域产生原理，列举多种解决方案，适配开发、生产不同环境的跨域处理。
 | 原文链接：http://wiki.m9zpbz.asia/arts/109684.Doc

原标题：从零搭建简单Mock接口服务
简介：golang websocket 服务端开发，Go 实现 WebSocket 服务端，处理连接、消息收发，实现长连接服务。
 | 原文链接：http://wiki.m9zpbz.asia/arts/836389.Doc

原标题：架构笔记：高并发系统核心设计思路总结
简介：golang sync.Map 适用场景与性能对比，读多写少，离散 key，对比普通 map 加锁性能差异。
 | 原文链接：http://wiki.m9zpbz.asia/arts/928789.Doc

原标题：Fork 开源项目同步上游代码
简介：Nginx 请求头大小上限调整，修改 Nginx 配置，调大请求头允许最大大小，避免大 Header 请求被拒绝。
 | 原文链接：http://wiki.m9zpbz.asia/arts/306353.Doc

原标题：Hands‑on：编写GitLabCI配置自动测试部署
简介：nodejs 日志轮转生产环境配置，配置 Node 日志轮转切割，防止日志文件无限变大，适配生产环境。
 | 原文链接：http://wiki.m9zpbz.asia/arts/727439.Doc

原标题：入门实践：简易导出导入文件功能实现
简介：布隆过滤器误判问题修正，调整布隆过滤器参数，降低误判概率，保证业务去重逻辑准确。
 | 原文链接：http://wiki.m9zpbz.asia/arts/421507.Doc

原标题：坑点：依赖包内部携带恶意代码供应链风险
简介：Git LFS 大文件推送失败解决，配置 Git LFS，处理仓库大文件，解决大文件推送报错推送失败。
 | 原文链接：http://wiki.m9zpbz.asia/arts/602699.Doc

原标题：服务器 Swap 关闭提升响应速度
简介：git cherry‑pick 规范操作防 bug，规范 cherry‑pick 使用流程，处理冲突，避免错误引入不兼容代码。
 | 原文链接：http://wiki.m9zpbz.asia/arts/972153.Doc

原标题：排错：静态资源CDN缓存未刷新旧资源持续返回
简介：golang go select 多路等待 channel，select 等待多个 channel，default 非阻塞，超时等待 channel。
 | 原文链接：http://wiki.m9zpbz.asia/arts/706516.Doc

原标题：从零搭建简单CLI命令行工具
简介：nodejs 集成测试业务流程编写，编写 Node 集成测试，调用真实接口，验证完整业务链路执行结果。
 | 原文链接：http://wiki.m9zpbz.asia/arts/258805.Doc

四、架构设计｜Architecture
原标题：Security：密码存储哈希加盐最佳实践
简介：golang context.WithValue 传递元数据，WithValue 只传 traceId 鉴权元数据，不要传业务大对象。
 | 原文链接：http://wiki.m9zpbz.asia/arts/936691.Doc

原标题：golang 系统设计技术方案评审关注点清单参考
简介：golang fasthttp 客户端连接池调优，fasthttp 客户端连接池配置，复用连接提升请求性能。
 | 原文链接：http://wiki.m9zpbz.asia/arts/925061.Doc

原标题：Practice：实现多数据源动态切换组件实践
简介：golang 钉钉企业微信告警消息推送，go 调用企业微信钉钉接口，推送告警通知、业务消息。
 | 原文链接：http://wiki.m9zpbz.asia/arts/006888.Doc

原标题：DevOps：GitLabCI完整流水线配置示例
简介：golang 高并发下锁优化减少竞争，减小锁粒度，读写锁替换互斥锁，无锁编程降低锁竞争开销。
 | 原文链接：http://wiki.m9zpbz.asia/arts/621183.Doc

原标题：调优方案：JVM内存参数优化，降低GC频率
简介：数据库索引重建提升查询速度，针对碎片化索引，重建数据库索引，恢复 SQL 查询执行性能。
 | 原文链接：http://wiki.m9zpbz.asia/arts/857028.Doc

原标题：新手教程：本地项目初始化gitignore配置
简介：GET POST 接口请求参数处理，讲解两种请求方式参数传递区别，演示参数接收、解析、校验，适配不同接口调用场景。
 | 原文链接：http://wiki.m9zpbz.asia/arts/198284.Doc

原标题：踩坑：数据库连接未关闭，连接池泄露
简介：golang mysql 长连接检测保活设置，配置 mysql 连接保活检测，剔除失效连接，避免拿到断开无效数据库连接。
 | 原文链接：http://wiki.m9zpbz.asia/arts/109110.Doc

原标题：Issue：本地数据库与线上数据库排序规则差异
简介：golang lru 缓存淘汰算法编写，手写 LRU 缓存淘汰算法，实现本地缓存，淘汰最久未使用数据。
 | 原文链接：http://wiki.m9zpbz.asia/arts/028814.Doc

原标题：环境变量不生效问题修复
简介：golang consul 服务发现简单示例，对接 Consul 实现服务注册发现，微服务实例自动感知。
 | 原文链接：http://wiki.m9zpbz.asia/arts/776581.Doc

原标题：golang 分布式 ID 雪花算法实现
简介：golang os.Exit 退出程序注意 defer 不执行，os.Exit 会直接退出，不会执行 defer，优雅退出不要直接 os.Exit。
 | 原文链接：http://wiki.m9zpbz.asia/arts/314571.Doc

原标题：golang k8s 监控 prometheus 部署
简介：golang 字符串处理常用技巧汇总，字符串拼接、分割、替换、类型转换实操，规避字符串高频错误。
 | 原文链接：http://wiki.m9zpbz.asia/arts/910709.Doc

原标题：Practice：实现异步任务结果查询回调实践
简介：容器资源限制防止宿主机过载，设置容器 CPU 内存资源上限，避免单个容器耗尽宿主机全部硬件资源。
 | 原文链接：http://wiki.m9zpbz.asia/arts/502916.Doc

原标题：Architecture：鉴权授权系统架构设计思路
简介：环境变量不生效问题修复，排查环境变量加载顺序、作用域问题，修复环境变量读取不到的异常。
 | 原文链接：http://wiki.m9zpbz.asia/arts/452505.Doc

原标题：Security：RPC调用身份认证安全加固
简介：无用对象回收抑制内存上涨，优化对象生命周期，及时释放不再使用对象，抑制内存持续不断增长。
 | 原文链接：http://wiki.m9zpbz.asia/arts/572511.Doc

原标题：避坑：预编译SQL失效，出现SQL注入风险
简介：前端工程化 webpack 打包优化，针对 webpack 项目做打包调优，分包、压缩、Tree‑Shaking，缩减包体积。
 | 原文链接：http://wiki.m9zpbz.asia/arts/337397.Doc

原标题：零基础理解模块化与组件化基础思想
简介：容器内存扩容 OOM 被杀死修复，调高容器内存限制，优化程序内存占用，避免程序被 OOM 终止。
 | 原文链接：http://wiki.m9zpbz.asia/arts/590169.Doc

原标题：OpenSource：如何高效阅读大型开源项目源码
简介：golang 分布式锁防死锁实现要点，锁超时、续期、锁持有者校验，避免锁死锁，保障分布式锁可靠性。
 | 原文链接：http://wiki.m9zpbz.asia/arts/417025.Doc

原标题：AI实践：大模型生成测试用例实践与校验
简介：golang http 服务并发连接数限制，自定义 listener 统计连接数量，限制最大并发连接数保护服务。
 | 原文链接：http://wiki.m9zpbz.asia/arts/266568.Doc

?
