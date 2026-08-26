最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计指标埋点代码低侵入实现
简介：nodejs 数据库连接池配置调优，调优 Node 数据库连接池参数，平衡性能与资源占用，避免连接耗尽。
 | 原文链接：http://wiki.0a865u.asia/arts/899470.Doc

原标题：golang 跨域处理中间件编写
简介：golang redis pipeline 与 txpipeline 区别，区分普通管道与事务管道，根据业务场景选择合适批量执行方案。
 | 原文链接：http://wiki.0a865u.asia/arts/370471.Doc

原标题：golang es 映射 mapping 设计避坑
简介：前端错误监控上报系统搭建，搭建前端错误监控，捕获页面 JS 错误，上报后端，快速发现线上页面 bug。
 | 原文链接：http://wiki.0a865u.asia/arts/019141.Doc

原标题：踩坑记录：UTC时间与本地时间混用逻辑错乱
简介：golang go 程序守护进程实现思路，go 程序不做 daemon 化，依靠 systemd pm2 k8s 实现进程守护。
 | 原文链接：http://wiki.0a865u.asia/arts/352458.Doc

原标题：架构复盘：系统扩容缩容架构无状态优先原则
简介：golang html 模板防 xss 自动转义，理解 go html/template 自动转义，防止 XSS 攻击，处理不需要转义场景。
 | 原文链接：http://wiki.0a865u.asia/arts/815043.Doc

原标题：配置外部化线上部署防错误
简介：golang hystrix 模式简易熔断实现，简易熔断组件，错误率达到阈值触发熔断，快速失败保护下游。
 | 原文链接：http://wiki.0a865u.asia/arts/446854.Doc

原标题：线上异常：缓存雪崩带来数据库压力瞬间飙升
简介：ICMP 放通网络丢包问题修复，放开 ICMP 协议，解决 MTU 问题导致网络丢包，修复网络不稳定现象。
 | 原文链接：http://wiki.0a865u.asia/arts/751648.Doc

原标题：设计思考：大促系统架构压测改造整体思路
简介：nodejs 多进程任务分发处理，多进程拆分处理 CPU 密集任务，主进程分发任务，利用多核提升处理速度。
 | 原文链接：http://wiki.0a865u.asia/arts/730055.Doc

原标题：排错：打包后资源路径，开发生产行为不一致
简介：golang 容器内读取 k8s 配置 configmap，程序读取 k8s configmap 配置，配置与镜像分离便于运维。
 | 原文链接：http://wiki.0a865u.asia/arts/072127.Doc

原标题：Performance：数据库分表解决单表过大性能衰减
简介：布隆过滤器误判问题修正，调整布隆过滤器参数，降低误判概率，保证业务去重逻辑准确。
 | 原文链接：http://wiki.0a865u.asia/arts/401106.Doc

原标题：ORM 隐式慢查询问题规避
简介：nodejs 跨域中间件配置细节，Express 跨域中间件配置细节，处理预检请求，修复偶现跨域失效。
 | 原文链接：http://wiki.0a865u.asia/arts/895070.Doc

原标题：K8s 镜像拉取网络故障修复
简介：golang go race 竞态检测工具，‑race 检测数据竞争，编译运行检测并发读写数据竞争 bug。
 | 原文链接：http://wiki.0a865u.asia/arts/487481.Doc

原标题：golang ci 流水线单元测试集成测试
简介：golang go sum 校验失败处理方案，go sum 校验不匹配，排查网络代理，清理缓存解决校验报错。
 | 原文链接：http://wiki.0a865u.asia/arts/073600.Doc

原标题：复盘总结：线上故障完整复盘报告模板示例
简介：golang loki 日志收集 go 服务集成，日志输出适配 loki，标签携带 traceId，日志集中检索排查问题。
 | 原文链接：http://wiki.0a865u.asia/arts/761830.Doc

原标题：业务幂等键设计防重复逻辑
简介：golang 静态文件服务搭建教程，Go 搭建静态文件服务，托管静态资源，实现文件直接对外访问。
 | 原文链接：http://wiki.0a865u.asia/arts/674441.Doc

原标题：Debug：预加载逻辑错误服务启动时间成倍拉长
简介：Docker Compose 一键搭建本地栈，使用 Compose 编排多个容器，一键拉起全套开发依赖服务。
 | 原文链接：http://wiki.0a865u.asia/arts/203069.Doc

原标题：Hands‑on：简易的事件订阅发布组件开发实践
简介：服务启动依赖顺序配置正确，配置服务启动依赖关系，保证依赖服务就绪之后再启动当前业务服务。
 | 原文链接：http://wiki.0a865u.asia/arts/482419.Doc

原标题：golang 系统设计缓存一致性方案对比
简介：前端虚拟列表大数据渲染优化，实现虚拟滚动列表，只渲染可视区域 DOM，上万条数据页面流畅渲染。
 | 原文链接：http://wiki.0a865u.asia/arts/153218.Doc

原标题：git stash 代码暂存切换分支
简介：golang yaml 解析配置加载实操，Go 解析 YAML 配置文件，读取配置参数，驱动业务运行。
 | 原文链接：http://wiki.0a865u.asia/arts/595863.Doc

原标题：项目构建脚本编译打包解析
简介：golang net/http 超时全套配置，完整配置 Go HTTP 服务读写空闲超时，全方位防止请求挂住。
 | 原文链接：http://wiki.0a865u.asia/arts/704465.Doc

原标题：排错：前端打包chunk过大浏览器加载缓慢
简介：golang 换行符统一处理，文本文件读写统一换行符，规避不同系统换行符带来解析异常。
 | 原文链接：http://wiki.0a865u.asia/arts/696664.Doc

原标题：实践：数据库备份脚本自动化编写实践
简介：golang fuzz corpus 语料库使用，fuzz 语料存储历史输入，回归测试，持续复现曾经触发 bug 输入。
 | 原文链接：http://wiki.0a865u.asia/arts/935077.Doc

原标题：项目实践：灰度发布简易方案落地实践
简介：golang go 泛型使用避坑注意点，泛型与 interface 区别，泛型性能，什么时候适合使用泛型。
 | 原文链接：http://wiki.0a865u.asia/arts/555856.Doc

原标题：实战项目：前端资源打包体积优化完整实操
简介：golang redis hyperloglog 基数统计，hyperloglog 统计 UV 基数，海量数据去重统计，极低内存开销。
 | 原文链接：http://wiki.0a865u.asia/arts/899610.Doc

原标题：golang 系统设计大表加索引线上执行方案
简介：nodejs 信号处理优雅关闭服务，监听系统信号，执行资源清理，实现 Node 服务优雅停机，拒绝粗暴杀死进程。
 | 原文链接：http://wiki.0a865u.asia/arts/912207.Doc

原标题：golang http client 连接池调优
简介：golang tidb 数据库 go 项目适配，go 程序适配 tidb，兼容 mysql 协议，分布式数据库业务开发。
 | 原文链接：http://wiki.0a865u.asia/arts/567425.Doc

原标题：快速入门ORM，实现简单数据库增删改查
简介：golang go 服务日志输出 journald，systemd journald 接收程序 stdout 日志，统一管理服务日志。
 | 原文链接：http://wiki.0a865u.asia/arts/204911.Doc

原标题：golang 系统设计雪花算法 id 原理剖析
简介：数据库连接及时关闭连接泄漏，确保数据库连接使用完毕释放归还连接池，杜绝连接泄漏耗尽连接。
 | 原文链接：http://wiki.0a865u.asia/arts/181258.Doc

原标题：实践：数据库慢查询分析与索引优化实战演练
简介：集成测试业务流程编写示例，编写业务流程集成测试，覆盖完整业务链路，验证模块之间协同工作是否正常。
 | 原文链接：http://wiki.0a865u.asia/arts/130777.Doc

原标题：golang 简易埋点日志上报实现
简介：vite 项目配置与构建提速技巧，讲解 vite 配置优化手段，提升开发热更新速度与生产构建打包效率。
 | 原文链接：http://wiki.0a865u.asia/arts/103551.Doc

原标题：调优方案：JVM内存参数优化，降低GC频率
简介：golang strings 常用函数业务实战，字符串分割替换包含判断前缀后缀，掌握 strings 包高频函数。
 | 原文链接：http://wiki.0a865u.asia/arts/489897.Doc

原标题：开发记录：表单文件类型校验后端安全校验实践
简介：golang 项目 makefile 脚本编写，编写 Makefile 脚本，封装编译、测试、构建命令，简化项目操作。
 | 原文链接：http://wiki.0a865u.asia/arts/720548.Doc

原标题：HelloGitHubPages：部署你的第一个静态博客
简介：Nginx 静态代理负载均衡全套配置，一套 Nginx 配置示例，覆盖静态资源、反向代理、负载均衡场景。
 | 原文链接：http://wiki.0a865u.asia/arts/564612.Doc

原标题：缓存基础原理与简单代码实现
简介：golang go http 安全头配置实践，设置 http 安全响应头，防范 XSS、点击劫持，提升 web 服务安全性。
 | 原文链接：http://wiki.0a865u.asia/arts/169578.Doc

原标题：Hands‑on：简易事件驱动架构原型开发
简介：API 接口调试与异常处理实战，覆盖接口请求、参数组装、错误捕获，提供调试思路，高效定位接口返回异常问题。
 | 原文链接：http://wiki.0a865u.asia/arts/315105.Doc

原标题：webpack chunk 分包策略详解
简介：golang trace 可视化分析协程阻塞，使用 trace 网页 UI，定位协程阻塞、系统调用阻塞、锁等待。
 | 原文链接：http://wiki.0a865u.asia/arts/449836.Doc

原标题：golang redis lua 脚本原子操作
简介：golang go‑pg postgres 客户端实操，go‑pg 操作 PostgreSQL 数据库，CRUD 关联查询业务开发。
 | 原文链接：http://wiki.0a865u.asia/arts/226219.Doc

原标题：golang 链路 traceId 透传中间件
简介：golang 静态文件服务搭建教程，Go 搭建静态文件服务，托管静态资源，实现文件直接对外访问。
 | 原文链接：http://wiki.0a865u.asia/arts/303308.Doc

原标题：架构笔记：冷热数据分离架构设计与迁移
简介：golang os 文件目录操作大全，文件创建删除重命名，目录遍历，文件信息读取，完成各类文件系统操作。
 | 原文链接：http://wiki.0a865u.asia/arts/336500.Doc

原标题：Performance：大事务拆分，减少锁持有时间
简介：golang 分布式唯一 id 多种方案对比，雪花、redis、uuid 对比各方案优缺点，指导业务选型使用。
 | 原文链接：http://wiki.0a865u.asia/arts/039923.Doc


二、踩坑排错｜Troubleshooting
原标题：数据库连接池参数调优
简介：文件句柄上限调整上传随机失败，调高系统文件句柄上限，解决高并发上传场景随机打开文件失败。
 | 原文链接：http://wiki.0a865u.asia/arts/930934.Doc

原标题：Hands‑on：简易配置热更新组件开发实践
简介：golang go 爬虫请求速率控制，爬虫限频、代理轮换，设置 UA，防止爬虫被目标站点封禁 IP。
 | 原文链接：http://wiki.0a865u.asia/arts/754801.Doc

原标题：快速入门YAML配置文件语法与示例
简介：序列化版本不一致解析失败，保证序列化对象版本对齐，修复版本不匹配导致对象反序列化失败。
 | 原文链接：http://wiki.0a865u.asia/arts/486428.Doc

原标题：golang 项目 makefile 脚本编写
简介：golang prometheus 指标埋点开发，业务埋点计数器、仪表盘、直方图，对接 prometheus 采集监控指标。
 | 原文链接：http://wiki.0a865u.asia/arts/084838.Doc

原标题：monorepo 项目多包管理最佳实践
简介：golang 静态编译缩小镜像体积，Go 程序静态编译，不依赖系统库，产出单二进制文件，缩小镜像。
 | 原文链接：http://wiki.0a865u.asia/arts/715870.Doc

原标题：golang 布隆过滤器实现去重
简介：golang 数据库分表策略按时间分片，按时间维度分表，历史数据拆分，单表数据量控制保证查询性能。
 | 原文链接：http://wiki.0a865u.asia/arts/274919.Doc

原标题：golang 接口请求日志记录中间件
简介：golang go 比较运算符可比较类型，哪些类型可以直接 == 比较，map slice 函数不可直接比较。
 | 原文链接：http://wiki.0a865u.asia/arts/074455.Doc

原标题：golang redis zset 排行榜业务实现
简介：本地运行正常线上报错排查，对比本地与线上环境差异，从配置、系统版本、文件权限定位线上独有的 bug。
 | 原文链接：http://wiki.0a865u.asia/arts/266968.Doc

原标题：golang 系统设计 grpc http2 多路复用讲解
简介：golang sqlx 原生 SQL 代码简化，sqlx 简化原生 SQL 结果映射结构体，兼顾性能与开发效率。
 | 原文链接：http://wiki.0a865u.asia/arts/078108.Doc

原标题：Architecture：大文件上传下载系统架构设计
简介：GET POST 接口请求参数处理，讲解两种请求方式参数传递区别，演示参数接收、解析、校验，适配不同接口调用场景。
 | 原文链接：http://wiki.0a865u.asia/arts/126782.Doc

原标题：Practice：实现业务id生成不连续有序ID方案
简介：golang redis 客户端业务使用，Go Redis 客户端对接，实现缓存、计数器，适配各类 Redis 业务场景。
 | 原文链接：http://wiki.0a865u.asia/arts/856061.Doc

原标题：坑点：gitrebase操作失误，代码提交丢失
简介：golang 配置文件多格式兼容加载，同时支持 yaml toml json 多种格式配置文件，灵活适配不同部署环境。
 | 原文链接：http://wiki.0a865u.asia/arts/285804.Doc

原标题：项目实践：实现统一接口返回封装与全局异常处理
简介：golang yaml 解析配置加载实操，Go 解析 YAML 配置文件，读取配置参数，驱动业务运行。
 | 原文链接：http://wiki.0a865u.asia/arts/044767.Doc

原标题：零基础理解跨域问题产生原因与基础方案
简介：开源项目构建失败排查步骤，梳理构建报错排查流程，从依赖、网络、权限、脚本多角度定位项目构建失败原因。
 | 原文链接：http://wiki.0a865u.asia/arts/147656.Doc

原标题：golang rsa 非对称加密签名验签
简介：文件监控服务自动重启开发，监控项目文件变更，代码修改自动重启服务，提升本地开发调试效率。
 | 原文链接：http://wiki.0a865u.asia/arts/290348.Doc

原标题：异步任务堆积消费能力优化
简介：golang csv 读写批量数据处理，Go 读写 CSV 文件，批量导入导出业务数据，处理 CSV 格式解析。
 | 原文链接：http://wiki.0a865u.asia/arts/882718.Doc

原标题：golang 系统设计短链接服务实现思路
简介：Git commit 钩子提交规范校验，配置 Git 提交钩子，提交代码自动校验提交信息格式，规范提交记录。
 | 原文链接：http://wiki.0a865u.asia/arts/710345.Doc

原标题：实战项目：HTTPS本地自签名证书配置实践
简介：Shell 运维脚本服务器效率提升，编写常用运维 Shell 脚本，自动化服务器运维操作，减少手工重复工作。
 | 原文链接：http://wiki.0a865u.asia/arts/389701.Doc

原标题：项目实践：接口压测，逐步加压观察系统表现
简介：数据库 utf8mb4 支持 emoji 存储，数据库字段设置 utf8mb4 字符集，完整支持 emoji 表情存储入库。
 | 原文链接：http://wiki.0a865u.asia/arts/169004.Doc

原标题：golang 系统设计开源项目维护简单经验分享
简介：全局本地依赖隔离冲突规避，区分全局依赖与项目本地依赖，隔离环境，防止全局包干扰项目运行。
 | 原文链接：http://wiki.0a865u.asia/arts/596289.Doc

原标题：Hands‑on：简易频率统计组件Redis实现
简介：golang mock 单元测试编写技巧，单元测试 mock 外部依赖，隔离数据库网络，只测试业务逻辑本身。
 | 原文链接：http://wiki.0a865u.asia/arts/712910.Doc

原标题：Practice：模拟网络抖动验证服务容错能力
简介：golang 单元测试 table‑driven，表格驱动单元测试写法，批量输入多组测试用例，简化单元测试代码。
 | 原文链接：http://wiki.0a865u.asia/arts/411467.Doc

原标题：重复提交幂等防护再次讲解
简介：golang 项目目录分层规范设计，Go 后端项目目录分层规范，按领域分层，提高项目可读性可维护性。
 | 原文链接：http://wiki.0a865u.asia/arts/971049.Doc

原标题：golang 系统设计混沌测试简单场景模拟实现
简介：golang io.Copy 流式拷贝数据，io.Copy 拷贝 reader 到 writer，不用加载全部数据到内存。
 | 原文链接：http://wiki.0a865u.asia/arts/110008.Doc

原标题：Debug：长连接未设置心跳，连接僵死不回收
简介：golang excel 简单读写操作示例，Go 实现 Excel 简单读写，业务数据导出 Excel 报表。
 | 原文链接：http://wiki.0a865u.asia/arts/403043.Doc

原标题：golang 系统设计分布式锁红锁优缺点梳理
简介：接口压测定位系统性能瓶颈，使用压测工具对接口施压，观察指标，定位系统性能瓶颈点。
 | 原文链接：http://wiki.0a865u.asia/arts/996043.Doc

原标题：MySQL 慢查询索引优化实战
简介：golang 参数校验业务接口处理，Go 接口入参参数校验，拦截非法入参，减少业务层参数判断代码。
 | 原文链接：http://wiki.0a865u.asia/arts/374584.Doc

原标题：golang 链路追踪简易实现方案
简介：接口请求重试容错机制实现，封装请求重试逻辑，遇到临时网络故障自动重试，提升第三方调用稳定性。
 | 原文链接：http://wiki.0a865u.asia/arts/560959.Doc

原标题：性能笔记：锁优化减少竞争提升并发吞吐
简介：上传接口跨域配置特殊适配，针对文件上传接口，适配复杂请求，修复上传场景下跨域失效问题。
 | 原文链接：http://wiki.0a865u.asia/arts/693009.Doc

原标题：开发记录：表单文件类型校验后端安全校验实践
简介：golang net/http 超时全套配置，完整配置 Go HTTP 服务读写空闲超时，全方位防止请求挂住。
 | 原文链接：http://wiki.0a865u.asia/arts/186594.Doc

原标题：前端打包分包加载提速方案
简介：golang 消息队列 kafka 消费开发，Go 开发 Kafka 消费程序，消费消息执行业务，理解 Kafka 消费逻辑。
 | 原文链接：http://wiki.0a865u.asia/arts/141073.Doc

原标题：性能笔记：数据库表字段设计影响查询性能
简介：golang contract 契约测试微服务，微服务契约测试，保证接口变更不破坏调用方，提前发现兼容性问题。
 | 原文链接：http://wiki.0a865u.asia/arts/078494.Doc

原标题：golang 系统设计开源项目维护简单经验分享
简介：golang sync.Map 适用场景与性能对比，读多写少，离散 key，对比普通 map 加锁性能差异。
 | 原文链接：http://wiki.0a865u.asia/arts/489501.Doc

原标题：灰度发布策略服务平滑升级
简介：golang 服务注册 etcd 简单示例，etcd 实现服务注册发现，微服务实例注册元数据，客户端发现节点。
 | 原文链接：http://wiki.0a865u.asia/arts/520116.Doc

原标题：golang 系统设计大表结构变更不停机方案
简介：包管理器依赖冲突解决方案，分析依赖冲突产生根源，提供版本调整、锁定依赖等手段，解决项目依赖报错问题。
 | 原文链接：http://wiki.0a865u.asia/arts/055149.Doc

原标题：golang 系统设计密钥轮换安全实践思路
简介：golang net/http/httptest 服务端模拟，httptest.NewRecorder 记录 handler 响应，校验返回状态码 body。
 | 原文链接：http://wiki.0a865u.asia/arts/931946.Doc

原标题：golang 系统设计 ci 流水线安全管控思路
简介：golang grpc keepalive 保活配置，grpc keepalive 参数调优，检测断开僵死连接，释放无效连接资源。
 | 原文链接：http://wiki.0a865u.asia/arts/411362.Doc

原标题：避坑：定时任务重复执行带来业务脏数据
简介：golang go test 单元测试命令参数详解，gotest 参数覆盖率，指定测试用例，跳过测试，单元测试命令实操。
 | 原文链接：http://wiki.0a865u.asia/arts/593020.Doc

原标题：golang k8s 资源请求限制配置
简介：DNS 解析异常第三方调用故障，排查 DNS 解析故障，修复域名解析，恢复第三方接口网络调用。
 | 原文链接：http://wiki.0a865u.asia/arts/719956.Doc

原标题：Hands‑on：代码生成器，一键生成CRUD模板
简介：golang bcrypt 密码哈希加密存储，bcrypt 做用户密码哈希，加盐存储密码，保障用户密码安全。
 | 原文链接：http://wiki.0a865u.asia/arts/367438.Doc

三、实战开发｜Practice
原标题：golang 系统设计多级缓存架构落地
简介：express 中间件开发业务实践，开发 Express 自定义中间件，拦截请求，实现鉴权、日志记录等通用逻辑。
 | 原文链接：http://wiki.0a865u.asia/arts/897098.Doc

原标题：实战：基于DockerCompose搭建本地开发栈
简介：golang strings.Builder 字符串高效拼接，strings.Builder 做字符串拼接，比 += 性能更高，减少内存拷贝。
 | 原文链接：http://wiki.0a865u.asia/arts/225286.Doc

原标题：golang 系统设计内存瓶颈定位优化思路
简介：golang redis lua 脚本原子操作，使用 Lua 脚本实现原子逻辑，减少网络往返，保障多命令原子执行。
 | 原文链接：http://wiki.0a865u.asia/arts/785210.Doc

原标题：架构复盘：跨机房多活架构基础概念与代价
简介：golang go 值传递引用传递理解，go 全部为值传递，指针本质拷贝指针值，理清参数传递行为。
 | 原文链接：http://wiki.0a865u.asia/arts/451620.Doc

原标题：golang 系统设计混沌测试简单场景模拟实现
简介：golang go proxy 私有代理配置，配置 go proxy 私有代理，加速依赖下载，内网环境构建项目。
 | 原文链接：http://wiki.0a865u.asia/arts/826812.Doc

原标题：线上故障：热点Key打满RedisCPU节点过载
简介：golang netlink 系统信息获取，netlink 获取系统网络信息，网卡地址，内核网络状态读取。
 | 原文链接：http://wiki.0a865u.asia/arts/722646.Doc

原标题：架构笔记：数据脱敏架构接入层与存储层方案
简介：golang io.MultiReader MultiWriter 拼接流，多个 reader 拼接，多 writer 同时写入一份数据。
 | 原文链接：http://wiki.0a865u.asia/arts/011097.Doc

原标题：nodejs redis 缓存业务实战
简介：API 大版本不兼容平滑迁移，API 版本迭代不兼容旧接口，设计平滑迁移方案，逐步完成版本切换。
 | 原文链接：http://wiki.0a865u.asia/arts/952842.Doc

原标题：实战：Redis过期回调实现业务事件通知实践
简介：nodejs 跨域中间件配置细节，Express 跨域中间件配置细节，处理预检请求，修复偶现跨域失效。
 | 原文链接：http://wiki.0a865u.asia/arts/518422.Doc

原标题：golang 系统设计数据库表设计通用规范模板
简介：大文件导出内存溢出防护，流式处理大文件导出，边读边写，不把全部数据加载内存，规避 OOM。
 | 原文链接：http://wiki.0a865u.asia/arts/389348.Doc

原标题：golang minio 对象存储接口开发
简介：golang go 服务压测前后性能对比，压测记录 QPS 延迟，优化前后对比，验证优化效果。
 | 原文链接：http://wiki.0a865u.asia/arts/267681.Doc

原标题：golang es 分页深分页性能优化
简介：上传接口跨域配置特殊适配，针对文件上传接口，适配复杂请求，修复上传场景下跨域失效问题。
 | 原文链接：http://wiki.0a865u.asia/arts/607957.Doc

原标题：golang 系统设计缓存降级开关快速切库实现
简介：开发环境变量配置全平台教程，区分 Windows、macOS、Linux 系统，讲解环境变量配置、加载优先级与常见失效原因。
 | 原文链接：http://wiki.0a865u.asia/arts/086271.Doc

原标题：golang 系统设计接口防刷 ip 限流实现
简介：golang 配置中心 apollo go 客户端，apollo go sdk 读取配置，配置变更自动热更新无需重启服务。
 | 原文链接：http://wiki.0a865u.asia/arts/829800.Doc

原标题：golang 系统设计依赖版本升级风险评估
简介：golang redis geo 地理位置存储查询，Redis GEO 存储经纬度，查询附近点位，实现附近人业务功能。
 | 原文链接：http://wiki.0a865u.asia/arts/715974.Doc

原标题：golang websocket 消息广播实现
简介：Dockerfile 编写容器打包实战，讲解 Dockerfile 指令含义，编写镜像构建脚本，将本地项目打包成可分发容器镜像。
 | 原文链接：http://wiki.0a865u.asia/arts/045802.Doc

原标题：golang grpc protobuf 开发实操
简介：css 动画性能优化 GPU 加速，优化 CSS 动画，使用 GPU 加速属性，避免动画过程页面卡顿掉帧。
 | 原文链接：http://wiki.0a865u.asia/arts/738761.Doc

原标题：golang ci 流水线代码质量扫描集成
简介：golang go 代码覆盖率线上统计，单元测试覆盖率统计，找出未测试代码分支，提升测试质量。
 | 原文链接：http://wiki.0a865u.asia/arts/297728.Doc

原标题：golang etcd watch 监听配置变更
简介：ORM 隐式慢查询问题规避，识别 ORM 框架隐式查询，避免循环查询数据库，减少不必要慢 SQL 产生。
 | 原文链接：http://wiki.0a865u.asia/arts/967498.Doc

原标题：Architecture：CI/CD流水线架构完整设计思考
简介：golang go 符号表与调试信息取舍，区分生产环境调试符号取舍，平衡镜像体积与故障排查能力。
 | 原文链接：http://wiki.0a865u.asia/arts/312562.Doc

原标题：Hands‑on：简易反向代理中间件实现
简介：golang go 自定义错误类型实现，自定义 error 结构体，携带错误码、堆栈信息，统一业务错误。
 | 原文链接：http://wiki.0a865u.asia/arts/318769.Doc

原标题：golang aes 对称加密解密示例
简介：程序日志分级输出规范实践，区分日志等级，规范日志打印内容，合理输出日志，方便线上问题排查定位。
 | 原文链接：http://wiki.0a865u.asia/arts/715465.Doc

原标题：实践：Git大仓库历史清理减小仓库体积实践
简介：全局本地依赖隔离冲突规避，区分全局依赖与项目本地依赖，隔离环境，防止全局包干扰项目运行。
 | 原文链接：http://wiki.0a865u.asia/arts/918691.Doc

原标题：Architecture：服务注册发现架构原理与选型
简介：golang 系统信号信号量处理，Go 处理系统各类信号，SIGINT、SIGTERM，实现程序可控退出。
 | 原文链接：http://wiki.0a865u.asia/arts/278869.Doc

原标题：排错：macOS权限保护导致脚本执行被拦截
简介：golang ssh 客户端远程命令执行，golang ssh 连接远程服务器，执行 shell 命令，获取命令输出结果。
 | 原文链接：http://wiki.0a865u.asia/arts/261011.Doc

原标题：eslint prettier 代码规范落地
简介：golang go http 安全头配置实践，设置 http 安全响应头，防范 XSS、点击劫持，提升 web 服务安全性。
 | 原文链接：http://wiki.0a865u.asia/arts/451100.Doc

原标题：golang 分布式锁防死锁处理
简介：golang rsa 非对称加密签名验签，RSA 非对称加密与签名验签，实现非对称安全通信。
 | 原文链接：http://wiki.0a865u.asia/arts/712548.Doc

原标题：调优方案：MySQL缓冲池参数性能调优实践
简介：golang fasthttp 高性能 http 库使用，fasthttp 高性能 http 实现，适合超高 QPS 场景，对比 net/http 差异。
 | 原文链接：http://wiki.0a865u.asia/arts/907055.Doc

原标题：golang kafka 消息丢失重复消费
简介：golang strconv 字符串类型转换，字符串转数字布尔，处理转换失败 error，避免 panic。
 | 原文链接：http://wiki.0a865u.asia/arts/265292.Doc

原标题：性能复盘：网络IO优化减少接口等待时间
简介：golang sql 注入风险规避要点，参数化查询杜绝 sql 注入，禁止字符串拼接 SQL 语句执行。
 | 原文链接：http://wiki.0a865u.asia/arts/355785.Doc

原标题：golang es 更新文档注意版本冲突
简介：golang 配置热更新不重启服务，实现配置热加载，监听配置变更，更新内存配置，无需重启服务实例。
 | 原文链接：http://wiki.0a865u.asia/arts/280629.Doc

原标题：线上异常：缓存雪崩带来数据库压力瞬间飙升
简介：golang 子进程执行命令标准流处理，exec.Command 执行外部命令，处理 stdout stderr，防止缓冲区阻塞卡死。
 | 原文链接：http://wiki.0a865u.asia/arts/131255.Doc

原标题：静态网页 HTML CSS 快速入门实战
简介：缓存基础原理与简单代码实现，讲解缓存设计思路，编写简易缓存逻辑，减少重复计算与重复请求，提升程序响应速度。
 | 原文链接：http://wiki.0a865u.asia/arts/423609.Doc

原标题：限流组件计数器令牌桶模式实现
简介：nestjs 权限守卫鉴权实现方案，使用 Nest 守卫实现接口鉴权，角色权限控制，拦截未授权接口访问。
 | 原文链接：http://wiki.0a865u.asia/arts/185947.Doc

原标题：架构复盘：供应链安全架构依赖包风险治理
简介：golang 优雅关闭 grpc 服务示例，gRPC 服务优雅关闭，等待现有请求处理完成再停止服务。
 | 原文链接：http://wiki.0a865u.asia/arts/692860.Doc

原标题：golang 系统设计延迟消息实现几种方案对比
简介：Nginx 丢失请求头配置修正，修复 Nginx 代理转发丢失请求头配置，保证上游服务拿到完整请求头信息。
 | 原文链接：http://wiki.0a865u.asia/arts/600662.Doc

原标题：golang 系统设计避免索引失效书写 sql 原则
简介：多环境配置中心灵活切换方案，简易配置中心实现，支持多套环境配置，动态下发无需重启服务。
 | 原文链接：http://wiki.0a865u.asia/arts/851929.Doc

原标题：开发记录：实现完整用户登录鉴权业务模块
简介：RPC 报文大小上限调优大请求，调大 RPC 框架报文最大限制，支持传输大体积请求报文不被截断。
 | 原文链接：http://wiki.0a865u.asia/arts/886816.Doc

原标题：接口签名验签完整安全方案
简介：golang go 程序守护进程实现思路，go 程序不做 daemon 化，依靠 systemd pm2 k8s 实现进程守护。
 | 原文链接：http://wiki.0a865u.asia/arts/156305.Doc

原标题：磁盘 inode 耗尽文件创建失败
简介：异步任务堆积消费能力优化，处理消息任务堆积问题，提升消费处理速度，恢复队列正常处理水位。
 | 原文链接：http://wiki.0a865u.asia/arts/825737.Doc

四、架构设计｜Architecture
原标题：项目实践：幂等表实现接口幂等业务实践
简介：开源源码阅读拆解学习思路，分享阅读大型开源项目方法，从入口文件逐层拆解模块，降低源码学习门槛。
 | 原文链接：http://wiki.0a865u.asia/arts/750706.Doc

原标题：golang 系统设计 api 文档 swagger redoc 落地
简介：golang go 基准测试 benchmark 编写，Benchmark 性能基准测试，测量函数执行耗时内存分配情况。
 | 原文链接：http://wiki.0a865u.asia/arts/187672.Doc

原标题：前端错误监控上报系统搭建
简介：多线程线程安全脏数据规避，梳理多线程共享变量，做好同步控制，避免并发修改产生脏数据。
 | 原文链接：http://wiki.0a865u.asia/arts/417878.Doc

原标题：Performance：批量导入数据性能优化实践
简介：golang 限流熔断放在代理层实践，代理层统一限流熔断，对后端服务做流量保护。
 | 原文链接：http://wiki.0a865u.asia/arts/601187.Doc

原标题：部署复盘：蓝绿发布实现零停机业务更新
简介：数据库索引重建提升查询速度，针对碎片化索引，重建数据库索引，恢复 SQL 查询执行性能。
 | 原文链接：http://wiki.0a865u.asia/arts/896158.Doc

原标题：golang 系统设计海量数据分页查询
简介：nodejs 多进程任务分发处理，多进程拆分处理 CPU 密集任务，主进程分发任务，利用多核提升处理速度。
 | 原文链接：http://wiki.0a865u.asia/arts/331496.Doc

原标题：golang 系统设计 README 开源文档模板
简介：golang 系统调用跟踪 strace 排查 go 程序，strace 跟踪系统调用，定位文件网络 IO 慢的底层原因。
 | 原文链接：http://wiki.0a865u.asia/arts/712057.Doc

原标题：架构复盘：服务灰度发布架构设计与流量切分
简介：golang 设置 net.Conn 读写超时，每次读写设置超时，防止连接永久阻塞挂起不返回。
 | 原文链接：http://wiki.0a865u.asia/arts/155455.Doc

原标题：设计思考：缓存分层架构设计与失效处理策略
简介：golang redis bitmap 位图业务实战，bitmap 做签到统计、用户状态标记，节省大量内存空间。
 | 原文链接：http://wiki.0a865u.asia/arts/282103.Doc

原标题：坑点：依赖缓存未更新，旧代码持续运行
简介：golang go 零停机升级实践要点，socket 继承，流量无损，旧连接处理完毕后旧进程退出。
 | 原文链接：http://wiki.0a865u.asia/arts/744472.Doc

原标题：Cookie 跨环境登录配置调整
简介：项目依赖安全扫描漏洞防范，扫描项目第三方依赖包，修复存在安全漏洞依赖，防范供应链攻击。
 | 原文链接：http://wiki.0a865u.asia/arts/137661.Doc

原标题：部署复盘：服务启动顺序依赖处理方案
简介：golang go test 单元测试命令参数详解，gotest 参数覆盖率，指定测试用例，跳过测试，单元测试命令实操。
 | 原文链接：http://wiki.0a865u.asia/arts/855705.Doc

原标题：架构复盘：跨机房多活架构基础概念与代价
简介：golang testify testify 断言库使用，testify assert require 断言，简化单元测试断言代码。
 | 原文链接：http://wiki.0a865u.asia/arts/526938.Doc

原标题：golang 系统设计日志规范结构化日志落地
简介：golang nats jetstream 持久消息队列，nats jetstream 持久化消息，保证消息不丢失，实现可靠消费。
 | 原文链接：http://wiki.0a865u.asia/arts/334391.Doc

原标题：golang 数据库批量更新性能优化
简介：golang ssh 客户端远程命令执行，golang ssh 连接远程服务器，执行 shell 命令，获取命令输出结果。
 | 原文链接：http://wiki.0a865u.asia/arts/158178.Doc

原标题：golang 系统设计开源项目自动化 ci 配置示例
简介：集成测试业务流程编写示例，编写业务流程集成测试，覆盖完整业务链路，验证模块之间协同工作是否正常。
 | 原文链接：http://wiki.0a865u.asia/arts/142449.Doc

原标题：DevOps：日志标准输出容器日志收集方案
简介：HTTP 状态码请求头完整梳理，汇总常用 HTTP 状态码与请求头含义，帮助快速看懂网络请求，排查接口通信问题。
 | 原文链接：http://wiki.0a865u.asia/arts/826098.Doc

原标题：开发复盘：避免大报文导致服务OOM优化实践
简介：golang fuzz corpus 语料库使用，fuzz 语料存储历史输入，回归测试，持续复现曾经触发 bug 输入。
 | 原文链接：http://wiki.0a865u.asia/arts/782703.Doc

?
