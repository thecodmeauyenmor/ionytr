最新前沿技术资讯

一、入门教程｜Getting Started
原标题：Performance：大事务拆分，减少锁持有时间
简介：golang go 模块迁移从 GOPATH 到 GoMod，老项目从 GOPATH 迁移 go mod，解决依赖管理混乱问题。
 | 原文链接：http://book.55b9pj.asia/blog/742910.Doc

原标题：开发复盘：搭建文件上传服务支持分片断点续传
简介：golang redis zset 实现延时任务队列，zset 存储任务到期时间，轮询到期任务执行，简易延迟队列。
 | 原文链接：http://book.55b9pj.asia/blog/688462.Doc

原标题：上传接口跨域配置特殊适配
简介：golang go 测试文件命名规范，_test.go 测试文件，TestXxx 单元测试函数命名规范。
 | 原文链接：http://book.55b9pj.asia/blog/273623.Doc

原标题：Troubleshooting：K8sPodOOMKilled完整排查流程
简介：golang feishu 飞书机器人消息发送，调用飞书 webhook 机器人，发送文本卡片消息，实现业务告警通知。
 | 原文链接：http://book.55b9pj.asia/blog/799132.Doc

原标题：数据库分表路由写入分片修正
简介：golang redis scan 遍历 key 避免阻塞，使用 scan 迭代遍历 redis 键，不用 keys 命令，防止阻塞 redis 服务。
 | 原文链接：http://book.55b9pj.asia/blog/729775.Doc

原标题：架构复盘：网关层、应用层、数据库层层限流架构
简介：Nginx 丢失请求头配置修正，修复 Nginx 代理转发丢失请求头配置，保证上游服务拿到完整请求头信息。
 | 原文链接：http://book.55b9pj.asia/blog/184839.Doc

原标题：实战项目：容器健康探针配置完整实践示例
简介：OAuth2 第三方登录服务搭建，搭建 OAuth2 服务，支持第三方账号登录，实现授权登录能力。
 | 原文链接：http://book.55b9pj.asia/blog/040722.Doc

原标题：golang 系统设计 api 接口兼容性设计原则
简介：内存广播本地进程消息通知，实现进程内内存消息广播，进程内部模块之间事件通知解耦。
 | 原文链接：http://book.55b9pj.asia/blog/501474.Doc

原标题：golang 系统设计定时任务分布式锁防重复执行
简介：golang lru 缓存淘汰算法编写，手写 LRU 缓存淘汰算法，实现本地缓存，淘汰最久未使用数据。
 | 原文链接：http://book.55b9pj.asia/blog/242569.Doc

原标题：golang 系统设计 rest 分页排序过滤参数规范
简介：golang io.Reader io.Writer 接口理解，io 读写接口，各类数据源统一抽象，适配 io 复制函数。
 | 原文链接：http://book.55b9pj.asia/blog/526169.Doc

原标题：后端登录鉴权模块完整开发
简介：golang 分布式唯一 id 多种方案对比，雪花、redis、uuid 对比各方案优缺点，指导业务选型使用。
 | 原文链接：http://book.55b9pj.asia/blog/567464.Doc

原标题：分布式任务调度集群原型开发
简介：golang context.Background 与 TODO 区别，Background 主流程根上下文，TODO 不确定用哪个上下文时使用。
 | 原文链接：http://book.55b9pj.asia/blog/316617.Doc

原标题：golang 系统设计网络超时故障排查思路
简介：golang accept 错误循环崩溃处理，accept 返回系统错误，处理临时错误，避免死循环占满 CPU。
 | 原文链接：http://book.55b9pj.asia/blog/764982.Doc

原标题：记一次升级操作系统内核引发服务不稳定
简介：golang 响应 body 流式返回大数据，http 流式输出数据，边生成边返回，无需在内存组装完整返回结果。
 | 原文链接：http://book.55b9pj.asia/blog/596142.Doc

原标题：golang 系统设计 protobuf json 性能对比
简介：端口占用释放资源重启服务，查找占用端口进程，结束占用进程，释放端口，让服务能够正常启动监听。
 | 原文链接：http://book.55b9pj.asia/blog/616337.Doc

原标题：Architecture：鉴权授权系统架构设计思路
简介：Cookie Session 会话状态管理，讲解 Cookie 与 Session 原理，理解登录状态保存，实现服务端会话管理逻辑。
 | 原文链接：http://book.55b9pj.asia/blog/035519.Doc

原标题：开发记录：表单文件类型校验后端安全校验实践
简介：golang 分布式事务 seata go 客户端，seata‑go 实现分布式事务，保证跨库业务数据最终一致性。
 | 原文链接：http://book.55b9pj.asia/blog/033595.Doc

原标题：从零编写简易 CLI 命令行工具
简介：接口限流逻辑简单模拟实现，编写简易限流逻辑，限制接口访问频次，保护服务，避免短时间大量请求压垮系统。
 | 原文链接：http://book.55b9pj.asia/blog/013751.Doc

原标题：golang 系统设计消息消费 offset 管理策略
简介：golang nilnil interface 陷阱复现，interface 包含类型不为 nil 值为 nil，判 ==nil 返回 false 经典坑。
 | 原文链接：http://book.55b9pj.asia/blog/134366.Doc

原标题：Cookie 跨环境登录配置调整
简介：golang 环境变量读取与类型转换，读取系统环境变量，做类型转换默认值处理，适配多环境部署。
 | 原文链接：http://book.55b9pj.asia/blog/186047.Doc

原标题：Security：接口鉴权越权漏洞检测与修复
简介：golang go 种子初始化 rand 随机，rand 初始化种子，不初始化会固定序列，理解随机数种子行为。
 | 原文链接：http://book.55b9pj.asia/blog/350982.Doc

原标题：golang 系统设计单元测试 mock 外部依赖技巧
简介：golang net.Conn 包装自定义连接，包装 net.Conn，统计读写字节，日志打印，超时控制。
 | 原文链接：http://book.55b9pj.asia/blog/927721.Doc

原标题：5分钟快速搭建个人技术文档站点
简介：数据库主从延迟业务兼容处理，业务适配主从复制延迟，避免读取从库拿到还未同步完成旧数据。
 | 原文链接：http://book.55b9pj.asia/blog/225239.Doc

原标题：快速入门对象存储基础使用场景
简介：前端图片懒加载性能优化，实现图片懒加载，页面可视区域才加载图片，减少页面初始网络请求。
 | 原文链接：http://book.55b9pj.asia/blog/262850.Doc

原标题：golang 系统设计分布式锁可重入实现思路
简介：golang redis bloom 布隆过滤器 go‑redis，go‑redis 布隆过滤器，海量数据判断是否存在，减少数据库查询。
 | 原文链接：http://book.55b9pj.asia/blog/365528.Doc

原标题：实战项目：搭建本地Mock服务快速开发联调
简介：golang staticcheck 静态代码分析，staticcheck 深度静态检查，发现代码错误、性能问题、风格问题。
 | 原文链接：http://book.55b9pj.asia/blog/115152.Doc

原标题：Troubleshooting：K8sPodOOMKilled完整排查流程
简介：golang http 文件下载断点续传服务，服务端实现断点续传，支持大文件分段下载，提升大文件下载稳定性。
 | 原文链接：http://book.55b9pj.asia/blog/455496.Doc

原标题：HTTPS 证书过期更新操作
简介：golang bcrypt 密码哈希加密存储，bcrypt 做用户密码哈希，加盐存储密码，保障用户密码安全。
 | 原文链接：http://book.55b9pj.asia/blog/000859.Doc

原标题：golang 系统设计数据库连接池调优实践
简介：golang 静态编译缩小镜像体积，Go 程序静态编译，不依赖系统库，产出单二进制文件，缩小镜像。
 | 原文链接：http://book.55b9pj.asia/blog/907305.Doc

原标题：调优方案：前端静态资源打包性能体积优化
简介：golang go 项目依赖冲突解决完整思路，定位冲突包，replace、exclude、升级降级解决版本冲突。
 | 原文链接：http://book.55b9pj.asia/blog/637355.Doc

原标题：方案设计：统一ID生成服务架构对比雪花算法
简介：golang 服务注册 etcd 简单示例，etcd 实现服务注册发现，微服务实例注册元数据，客户端发现节点。
 | 原文链接：http://book.55b9pj.asia/blog/620039.Doc

原标题：golang mysql 长连接短连接对比
简介：数据库索引重建提升查询速度，针对碎片化索引，重建数据库索引，恢复 SQL 查询执行性能。
 | 原文链接：http://book.55b9pj.asia/blog/699533.Doc

原标题：golang 系统设计 websocket 协议原理梳理
简介：golang 限制 multipart 内存大小，设置 MaxMemory，大文件写入磁盘临时文件防止内存暴涨。
 | 原文链接：http://book.55b9pj.asia/blog/774912.Doc

原标题：数据库读写分离性能优化
简介：golang go 时间 time.Timer time.Ticker，定时器与周期定时器，Stop Reset 正确使用，防止资源泄漏。
 | 原文链接：http://book.55b9pj.asia/blog/581170.Doc

原标题：golang k8s configmap secret 配置
简介：golang snowflake 时钟回拨解决方案，雪花算法处理时钟回拨，防止生成重复 ID，保证 ID 全局唯一。
 | 原文链接：http://book.55b9pj.asia/blog/620313.Doc

原标题：设计思考：防雪崩，系统过载保护架构设计
简介：golang 错误处理最佳实践汇总，Go 错误处理规范，包装错误，堆栈携带，拒绝简单忽略错误。
 | 原文链接：http://book.55b9pj.asia/blog/718393.Doc

原标题：CLI 批量处理工具文件操作开发
简介：golang net.Conn 包装自定义连接，包装 net.Conn，统计读写字节，日志打印，超时控制。
 | 原文链接：http://book.55b9pj.asia/blog/662287.Doc

原标题：golang 系统设计 ide 配置 go 开发效率提升技巧
简介：golang context.WithTimeout 超时上下文，WithTimeout 设置超时时间，超时自动 cancel 释放协程。
 | 原文链接：http://book.55b9pj.asia/blog/261928.Doc

原标题：golang 系统设计分库分表中间件思路
简介：golang go select 多路等待 channel，select 等待多个 channel，default 非阻塞，超时等待 channel。
 | 原文链接：http://book.55b9pj.asia/blog/016636.Doc

原标题：golang 系统设计测试覆盖率目标合理设定思路
简介：golang html 模板防 xss 自动转义，理解 go html/template 自动转义，防止 XSS 攻击，处理不需要转义场景。
 | 原文链接：http://book.55b9pj.asia/blog/759333.Doc


二、踩坑排错｜Troubleshooting
原标题：全局时间标准统一逻辑错乱修复
简介：消息队列重复消费业务处理，实现消息消费幂等，处理重复投递消息，保证多次消费业务结果一致。
 | 原文链接：http://book.55b9pj.asia/blog/450752.Doc

原标题：golang prometheus counter gauge 使用
简介：golang map 并发读写 panic 解决方案，map 非并发安全，讲解加锁、sync.map 方案解决并发读写崩溃。
 | 原文链接：http://book.55b9pj.asia/blog/517759.Doc

原标题：项目目录结构规范化最佳实践
简介：golang systemd 信号与优雅退出配合，systemd 停止服务发送 SIGTERM，go 程序捕获信号优雅关闭。
 | 原文链接：http://book.55b9pj.asia/blog/954366.Doc

原标题：golang docker 镜像构建最佳实践
简介：golang nacos go 客户端配置服务发现，nacos‑go 对接 nacos，配置管理、微服务注册发现。
 | 原文链接：http://book.55b9pj.asia/blog/323749.Doc

原标题：golang mysql 悲观锁乐观锁实现
简介：golang go‑zero 框架项目快速搭建，go‑zero 脚手架生成微服务项目，api rpc 服务快速开发。
 | 原文链接：http://book.55b9pj.asia/blog/130460.Doc

原标题：服务器时钟同步任务错乱修复
简介：golang html 模板防 xss 自动转义，理解 go html/template 自动转义，防止 XSS 攻击，处理不需要转义场景。
 | 原文链接：http://book.55b9pj.asia/blog/371551.Doc

原标题：golang ci 流水线环境变量管理方案
简介：文件描述符优化进程卡死修复，及时关闭文件句柄，控制打开文件数量，解决文件句柄耗尽进程卡死。
 | 原文链接：http://book.55b9pj.asia/blog/633679.Doc

原标题：golang 消息队列 kafka 消费开发
简介：golang strings 常用函数业务实战，字符串分割替换包含判断前缀后缀，掌握 strings 包高频函数。
 | 原文链接：http://book.55b9pj.asia/blog/998144.Doc

原标题：golang 系统设计第三方接口 mock 单元测试
简介：golang 分页查询封装通用工具，封装 Go 通用分页工具，统一处理分页参数，简化业务分页接口开发。
 | 原文链接：http://book.55b9pj.asia/blog/630404.Doc

原标题：eslint prettier 代码规范落地
简介：批量操作分批处理防止 OOM，大批量数据处理不一次性加载全部数据，分批循环处理，避免内存溢出。
 | 原文链接：http://book.55b9pj.asia/blog/269253.Doc

原标题：Architecture：API设计RESTful最佳实践与反模式
简介：golang gorm 索引设置与优化技巧，定义数据库索引，理解索引生效条件，避免索引失效慢查询。
 | 原文链接：http://book.55b9pj.asia/blog/440893.Doc

原标题：项目依赖安全扫描漏洞防范
简介：前端虚拟列表大数据渲染优化，实现虚拟滚动列表，只渲染可视区域 DOM，上万条数据页面流畅渲染。
 | 原文链接：http://book.55b9pj.asia/blog/835407.Doc

原标题：golang 系统设计版本号语义化规范讲解
简介：golang proto 可选字段处理方案，protobuf 可选字段正确判断，区分未赋值与零值，业务逻辑不出现偏差。
 | 原文链接：http://book.55b9pj.asia/blog/455031.Doc

原标题：golang k8s liveness readiness 探针
简介：golang minio 私有对象存储开发，minio s3 对象存储，bucket 管理，文件上传下载权限设置。
 | 原文链接：http://book.55b9pj.asia/blog/901098.Doc

原标题：前端打包产物体积压缩优化
简介：golang multipart 表单文件上传解析，服务端解析 multipart 表单，获取上传文件与表单字段。
 | 原文链接：http://book.55b9pj.asia/blog/583332.Doc

原标题：rebase 操作防止代码丢失
简介：golang 重试退避机制代码实现，Go 实现请求重试与指数退避，处理临时故障，提升调用稳定性。
 | 原文链接：http://book.55b9pj.asia/blog/084249.Doc

原标题：部署实践：服务器时间同步chrony配置
简介：golang pprof 线上采集性能数据，线上环境采集 pprof 性能样本，不用停机，分析线上性能问题。
 | 原文链接：http://book.55b9pj.asia/blog/388871.Doc

原标题：静态博客部署 GitHub Pages 教程
简介：golang aes cbc gcm 模式加密对比，AES‑CBC AES‑GCM 模式加密解密，理解两种模式差异选型。
 | 原文链接：http://book.55b9pj.asia/blog/825631.Doc

原标题：golang 系统设计 http3 quic 简单原理了解
简介：golang 分布式锁 redis 实现，基于 Redis 实现 Go 分布式锁，解决多实例并发竞争资源问题。
 | 原文链接：http://book.55b9pj.asia/blog/587774.Doc

原标题：golang 系统设计分库分表本地测试调试技巧
简介：golang 数据库 ORM 框架选型对比，gorm xorm sqlx 对比各 ORM 优缺点，根据业务场景选型。
 | 原文链接：http://book.55b9pj.asia/blog/385706.Doc

原标题：golang redis lua 脚本开发调试
简介：上传接口跨域配置特殊适配，针对文件上传接口，适配复杂请求，修复上传场景下跨域失效问题。
 | 原文链接：http://book.55b9pj.asia/blog/563835.Doc

原标题：踩坑记录：UTC时间与本地时间混用逻辑错乱
简介：多操作系统开发兼容处理，解决不同系统路径、换行符、权限差异，保证项目跨平台正常运行。
 | 原文链接：http://book.55b9pj.asia/blog/788756.Doc

原标题：开发环境变量配置全平台教程
简介：golang go 无锁并发编程技巧，原子操作 sync/atomic，简单场景替换锁，提升并发性能。
 | 原文链接：http://book.55b9pj.asia/blog/351805.Doc

原标题：实战：数据库索引设计，复合索引最佳实践
简介：golang cgroup 读取容器资源限制，go 程序读取 cgroup，获取容器 cpu 内存限额，适配容器环境。
 | 原文链接：http://book.55b9pj.asia/blog/566112.Doc

原标题：golang 系统设计服务优雅停机完整流程
简介：轻量 API 后端接口服务快速开发，快速搭建简易 API 服务，实现基础接口能力，快速支撑小型业务需求。
 | 原文链接：http://book.55b9pj.asia/blog/598473.Doc

原标题：golang 系统设计多级缓存架构落地
简介：nodejs 数据库连接池配置调优，调优 Node 数据库连接池参数，平衡性能与资源占用，避免连接耗尽。
 | 原文链接：http://book.55b9pj.asia/blog/275528.Doc

原标题：从零学习基础的接口请求与参数处理
简介：golang wasm webassembly go 编译，go 编译为 wasm，浏览器执行 go 代码，拓展 go 运行场景。
 | 原文链接：http://book.55b9pj.asia/blog/462850.Doc

原标题：分页逻辑错误数据漏查修复
简介：golang 服务限流熔断降级监控完整实践，微服务防护体系，限流熔断降级指标监控告警整套落地。
 | 原文链接：http://book.55b9pj.asia/blog/893118.Doc

原标题：零基础理解JSON、XML数据格式处理
简介：golang redis 锁超时业务处理，Redis 分布式锁超时问题处理，锁续期逻辑，防止业务未完成锁提前释放。
 | 原文链接：http://book.55b9pj.asia/blog/734053.Doc

原标题：golang 系统设计 hot‑reload 热重载 go 开发工具
简介：golang e2e 端到端测试 go 接口，编写 e2e 测试，完整模拟用户请求，校验整套业务链路正确性。
 | 原文链接：http://book.55b9pj.asia/blog/990722.Doc

原标题：golang mysql 长连接短连接对比
简介：静态资源 404 路径打包修复，修复打包后静态资源访问 404，调整资源输出路径，保证资源正常加载。
 | 原文链接：http://book.55b9pj.asia/blog/833071.Doc

原标题：入门实践：简易导出导入文件功能实现
简介：golang k8s go 服务 yaml 资源编写，k8s 部署 go 应用 deployment service，健康检查资源限制配置。
 | 原文链接：http://book.55b9pj.asia/blog/987796.Doc

原标题：业务错误码完整落地实践
简介：接口签名验签完整安全方案，一套完整接口签名方案，包含签名生成、请求携带、服务端验签校验。
 | 原文链接：http://book.55b9pj.asia/blog/635924.Doc

原标题：静态网页 HTML CSS 快速入门实战
简介：HTTP 状态码请求头完整梳理，汇总常用 HTTP 状态码与请求头含义，帮助快速看懂网络请求，排查接口通信问题。
 | 原文链接：http://book.55b9pj.asia/blog/459203.Doc

原标题：新手向：项目目录结构规范与含义解析
简介：golang arp 缓存读取操作，读取系统 arp 缓存表，获取 ip 对应的 mac 地址信息。
 | 原文链接：http://book.55b9pj.asia/blog/689537.Doc

原标题：golang 系统设计内部服务 mock 集成测试方案
简介：golang go‑zero 分布式锁组件使用，go‑zero 内置 redis 分布式锁，业务直接调用实现并发控制。
 | 原文链接：http://book.55b9pj.asia/blog/591498.Doc

原标题：golang 系统设计日志轮转切割防止磁盘占满
简介：golang go 死锁检测工具，静态检查、运行检测，发现 channel 锁导致死锁问题。
 | 原文链接：http://book.55b9pj.asia/blog/091889.Doc

原标题：系统时间同步定时任务偏移
简介：golang os 进程 pid 获取父进程 pid，os.Getpid 获取进程 id，获取父进程 pid，进程间识别。
 | 原文链接：http://book.55b9pj.asia/blog/085415.Doc

原标题：API 大版本不兼容平滑迁移
简介：前端水印防信息泄露实现，实现网页水印功能，页面叠加用户信息水印，防止页面截图信息外泄。
 | 原文链接：http://book.55b9pj.asia/blog/047009.Doc

原标题：Troubleshooting：k8s镜像拉取失败镜像仓库网络问题
简介：golang go toml 配置注释保留，toml 解析保留注释，修改配置后写回保留原有注释。
 | 原文链接：http://book.55b9pj.asia/blog/967558.Doc

三、实战开发｜Practice
原标题：golang 分页查询封装通用工具
简介：golang GC 频繁 STW 停顿优化，减少小对象分配，调整 GOGC，降低 GC 停顿对接口延迟影响。
 | 原文链接：http://book.55b9pj.asia/blog/703004.Doc

原标题：项目语义化版本号规范管理
简介：golang redis 锁超时业务处理，Redis 分布式锁超时问题处理，锁续期逻辑，防止业务未完成锁提前释放。
 | 原文链接：http://book.55b9pj.asia/blog/445524.Doc

原标题：效率笔记：提升开发效率shell脚本小工具合集
简介：golang 微服务网关简易实现，http 反向代理、路由匹配、鉴权限流，理解网关核心原理。
 | 原文链接：http://book.55b9pj.asia/blog/908305.Doc

原标题：golang es 分页深分页性能优化
简介：端口占用访问失败排查方案，讲解端口占用排查命令，定位占用进程，释放端口，解决服务启动端口被占用报错。
 | 原文链接：http://book.55b9pj.asia/blog/400636.Doc

原标题：实战：搭建本地对象存储兼容S3协议demo
简介：service‑worker 离线缓存实践，使用 ServiceWorker 实现静态资源离线缓存，弱网环境页面依然可访问。
 | 原文链接：http://book.55b9pj.asia/blog/789090.Doc

原标题：新手向：npm/pip/maven依赖版本冲突入门排查
简介：golang go 项目依赖冲突解决完整思路，定位冲突包，replace、exclude、升级降级解决版本冲突。
 | 原文链接：http://book.55b9pj.asia/blog/585367.Doc

原标题：golang 系统设计压力测试性能测试执行流程
简介：golang redis pipeline 批量操作，使用 Redis Pipeline 批量执行多条命令，减少网络往返，提升批量操作性能。
 | 原文链接：http://book.55b9pj.asia/blog/075455.Doc

原标题：golang 系统设计开源项目 release 发布流程
简介：golang cron 任务漂移问题处理，cron 任务执行超时导致任务漂移，通过分布式锁防止任务重叠执行。
 | 原文链接：http://book.55b9pj.asia/blog/047706.Doc

原标题：golang 系统设计 grpc proto 接口设计原则
简介：golang csv 百万级数据导入数据库，流式读取 csv 分批写入数据库，避免一次性加载全部数据。
 | 原文链接：http://book.55b9pj.asia/blog/814733.Doc

原标题：安全实践：最小权限原则数据库账号管控
简介：golang go embed 嵌入静态资源文件，使用 go embed 把静态文件编译进二进制，单文件部署携带静态资源。
 | 原文链接：http://book.55b9pj.asia/blog/053522.Doc

原标题：golang mongodb 聚合管道实操案例
简介：monorepo 项目多包管理最佳实践，monorepo 仓库管理多子包，统一版本管理，处理包之间互相依赖。
 | 原文链接：http://book.55b9pj.asia/blog/163222.Doc

原标题：性能笔记：HTTP连接复用性能优化实践
简介：API 接口调试与异常处理实战，覆盖接口请求、参数组装、错误捕获，提供调试思路，高效定位接口返回异常问题。
 | 原文链接：http://book.55b9pj.asia/blog/412992.Doc

原标题：Practice：实现IP黑名单拦截中间件实践
简介：golang redis geo 地理位置存储查询，Redis GEO 存储经纬度，查询附近点位，实现附近人业务功能。
 | 原文链接：http://book.55b9pj.asia/blog/267608.Doc

原标题：零基础理解读写分离基础思想
简介：golang 定时任务 cron 使用指南，Go 使用 Cron 库实现定时任务，配置 corn 表达式调度业务任务。
 | 原文链接：http://book.55b9pj.asia/blog/728451.Doc

原标题：Debug：表单自动转义特殊字符业务逻辑出错
简介：golang 内存 pprof 定位内存泄漏，pprof 分析内存快照，定位内存泄露对象，解决 Go 程序内存持续上涨。
 | 原文链接：http://book.55b9pj.asia/blog/079099.Doc

原标题：从零搭建简单的身份登录模拟示例
简介：golang http 服务性能优化调参，调优 Go HTTP 服务参数，调整连接池，提升服务并发吞吐能力。
 | 原文链接：http://book.55b9pj.asia/blog/204830.Doc

原标题：设计思考：业务系统如何做故障隔离架构
简介：golang mock 单元测试编写技巧，单元测试 mock 外部依赖，隔离数据库网络，只测试业务逻辑本身。
 | 原文链接：http://book.55b9pj.asia/blog/634811.Doc

原标题：多版本开发环境共存配置
简介：容器资源限制防止宿主机过载，设置容器 CPU 内存资源上限，避免单个容器耗尽宿主机全部硬件资源。
 | 原文链接：http://book.55b9pj.asia/blog/191764.Doc

原标题：golang docker 部署 es 本地开发
简介：GraphQL 接口查询优化实操，体验 GraphQL 查询方式，按需获取字段，减少冗余数据传输，优化接口请求效率。
 | 原文链接：http://book.55b9pj.asia/blog/284308.Doc

原标题：多线程线程安全脏数据规避
简介：并发数据覆盖加锁安全处理，多线程并发修改同一数据，增加锁机制，防止并发覆盖丢失更新数据。
 | 原文链接：http://book.55b9pj.asia/blog/418631.Doc

原标题：golang 系统设计分库分表扩容平滑迁移
简介：golang sync.WaitGroup 协程等待控制，WaitGroup 控制一组协程等待全部执行完成，完成批量协程任务调度。
 | 原文链接：http://book.55b9pj.asia/blog/414579.Doc

原标题：踩坑记录：分页逻辑错误造成数据重复输出
简介：golang cgo 内存管理 C 与 Go 内存，区分 Go 内存 C 堆内存，防止 cgo 内存泄漏，正确释放 C 内存。
 | 原文链接：http://book.55b9pj.asia/blog/837920.Doc

原标题：Hands‑on：实现WebSocket聊天室完整前后端demo
简介：HTTP 状态码请求头完整梳理，汇总常用 HTTP 状态码与请求头含义，帮助快速看懂网络请求，排查接口通信问题。
 | 原文链接：http://book.55b9pj.asia/blog/673593.Doc

原标题：HelloShell：入门常用shell脚本编写
简介：golang goreleaser 自动版本发布打包，goreleaser 自动化打包发布，生成多平台二进制归档文件。
 | 原文链接：http://book.55b9pj.asia/blog/169486.Doc

原标题：实践：消息队列死信处理业务落地实践
简介：golang mongodb 索引优化慢查询处理，mongodb 创建索引，分析慢查询，优化聚合查询执行性能。
 | 原文链接：http://book.55b9pj.asia/blog/660454.Doc

原标题：实战项目：本地搭建Prometheus监控完整demo
简介：golang grpc 负载均衡客户端实现，grpc 客户端负载均衡，轮询随机权重，分发请求到多个服务实例。
 | 原文链接：http://book.55b9pj.asia/blog/810244.Doc

原标题：实践：数据库慢查询分析与索引优化实战演练
简介：golang slice 切片底层原理与坑点，切片扩容、截取、底层数组共享，规避切片修改互相影响数据。
 | 原文链接：http://book.55b9pj.asia/blog/700342.Doc

原标题：golang 系统设计开源版本发布 changelog 维护
简介：ORM 隐式慢查询问题规避，识别 ORM 框架隐式查询，避免循环查询数据库，减少不必要慢 SQL 产生。
 | 原文链接：http://book.55b9pj.asia/blog/470340.Doc

原标题：Practice：实现定时任务动态启停管理接口
简介：golang net/http/httptest 服务端模拟，httptest.NewRecorder 记录 handler 响应，校验返回状态码 body。
 | 原文链接：http://book.55b9pj.asia/blog/116546.Doc

原标题：方案对比：本地缓存vs分布式缓存架构取舍
简介：golang k8s secret 敏感配置加载，加载 k8s secret 存储密钥密码，敏感信息不存放配置文件。
 | 原文链接：http://book.55b9pj.asia/blog/929325.Doc

原标题：golang 系统设计数据库基准压测简单思路
简介：golang 反向代理 http 服务开发，手写简易 http 反向代理，转发请求，修改请求头响应头。
 | 原文链接：http://book.55b9pj.asia/blog/664890.Doc

原标题：架构复盘：慢查询治理架构层面优化手段
简介：golang 优雅停机服务关闭实现，监听系统信号，关闭服务等待请求处理完毕，实现 Go 服务优雅停机。
 | 原文链接：http://book.55b9pj.asia/blog/732197.Doc

原标题：golang prometheus histogram 指标
简介：JWT 工具封装令牌刷新过期，封装 JWT 工具类，实现令牌生成、校验、过期刷新整套令牌管理逻辑。
 | 原文链接：http://book.55b9pj.asia/blog/787450.Doc

原标题：内存泄漏定位分析完整流程
简介：golang url 解析路径参数提取，url.Parse 解析 url，获取协议主机路径查询参数。
 | 原文链接：http://book.55b9pj.asia/blog/296135.Doc

原标题：前端静态缓存更新生效处理
简介：Docker 容器时区错误修复方案，修复 Docker 容器内部时区偏差，解决容器内时间不对引发业务逻辑异常。
 | 原文链接：http://book.55b9pj.asia/blog/581503.Doc

原标题：快速入门简单签名校验实现思路
简介：golang rsa 签名验签 pem 证书加载，加载 pem 格式密钥证书，rsa 签名与验签完整业务实现。
 | 原文链接：http://book.55b9pj.asia/blog/430745.Doc

原标题：golang 系统设计回调重试幂等完整处理
简介：大文件导出内存溢出防护，流式处理大文件导出，边读边写，不把全部数据加载内存，规避 OOM。
 | 原文链接：http://book.55b9pj.asia/blog/755752.Doc

原标题：golang mysql 字符集排序规则设置
简介：golang gin 静态资源访问配置，Gin 配置静态资源目录，直接对外提供静态文件访问服务。
 | 原文链接：http://book.55b9pj.asia/blog/581303.Doc

原标题：golang redis set 集合去重业务
简介：SSH 密钥配置 GitHub 免密登录，分步生成配置 SSH 密钥，实现 GitHub 免密推送拉取，免去重复输入账号密码的麻烦。
 | 原文链接：http://book.55b9pj.asia/blog/621312.Doc

原标题：ORM 隐式慢查询问题规避
简介：golang cgroup 读取容器资源限制，go 程序读取 cgroup，获取容器 cpu 内存限额，适配容器环境。
 | 原文链接：http://book.55b9pj.asia/blog/738055.Doc

四、架构设计｜Architecture
原标题：新手向：Mac/Windows开发环境差异踩坑
简介：golang GC 频繁 STW 停顿优化，减少小对象分配，调整 GOGC，降低 GC 停顿对接口延迟影响。
 | 原文链接：http://book.55b9pj.asia/blog/281349.Doc

原标题：系统时间同步定时任务偏移
简介：golang go 时间 time.Timer time.Ticker，定时器与周期定时器，Stop Reset 正确使用，防止资源泄漏。
 | 原文链接：http://book.55b9pj.asia/blog/995276.Doc

原标题：golang 系统设计监控大盘故障快速定位思路
简介：golang word 文档生成处理 go 方案，go 生成 word 文档报表，填充文本表格，输出 docx 文件。
 | 原文链接：http://book.55b9pj.asia/blog/180593.Doc

原标题：golang 系统设计代码评审 checklist 清单
简介：golang fasthttp 服务开发完整示例，fasthttp 搭建 http 服务，路由、参数读取、响应返回完整业务。
 | 原文链接：http://book.55b9pj.asia/blog/553852.Doc

原标题：依赖安装失败全方位排错
简介：golang trace 可视化分析协程阻塞，使用 trace 网页 UI，定位协程阻塞、系统调用阻塞、锁等待。
 | 原文链接：http://book.55b9pj.asia/blog/605182.Doc

原标题：golang kafka 批量发送消费优化
简介：文件句柄上限调整上传随机失败，调高系统文件句柄上限，解决高并发上传场景随机打开文件失败。
 | 原文链接：http://book.55b9pj.asia/blog/361909.Doc

原标题：架构笔记：数据库读写分离架构数据不一致应对
简介：Nginx 静态代理负载均衡全套配置，一套 Nginx 配置示例，覆盖静态资源、反向代理、负载均衡场景。
 | 原文链接：http://book.55b9pj.asia/blog/325558.Doc

原标题：golang 系统设计全局异常处理器实现
简介：golang nacos go 客户端配置服务发现，nacos‑go 对接 nacos，配置管理、微服务注册发现。
 | 原文链接：http://book.55b9pj.asia/blog/175437.Doc

原标题：开发记录：短信发送服务封装，失败重试策略
简介：异步编程 Promise 执行流程解析，拆解异步执行顺序，理解回调与 Promise 差异，理清异步场景下代码执行逻辑。
 | 原文链接：http://book.55b9pj.asia/blog/367314.Doc

原标题：开发记录：数据库悲观锁乐观锁业务场景实践
简介：正则表达式文本处理实战案例，结合业务场景演示正则匹配、提取、替换，处理手机号、邮箱等各类文本校验需求。
 | 原文链接：http://book.55b9pj.asia/blog/606993.Doc

原标题：批量操作分批处理防止 OOM
简介：golang gorm 软删除实现逻辑，Gorm 开启软删除，删除数据仅标记，数据保留可恢复，满足业务数据留存。
 | 原文链接：http://book.55b9pj.asia/blog/322156.Doc

原标题：golang 系统设计 mq 故障降级业务策略
简介：golang go 程序抢占调度理解，理解 go 抢占式调度原理，长循环阻塞调度，造成协程调度延迟。
 | 原文链接：http://book.55b9pj.asia/blog/143601.Doc

原标题：golang redis 过期策略内存淘汰
简介：YAML 配置文件语法快速上手，讲解 YAML 基础语法、缩进规则，编写项目配置文件，规避语法错误引发程序异常。
 | 原文链接：http://book.55b9pj.asia/blog/098694.Doc

原标题：实战：WebSocket断线重连完整业务处理实践
简介：请求重试组件退避策略实现，封装重试组件，实现指数退避策略，避免大量请求同时重试压垮下游。
 | 原文链接：http://book.55b9pj.asia/blog/619715.Doc

原标题：踩坑记录：浮点数作为Rediskey匹配异常
简介：前端打包产物体积压缩优化，多手段压缩前端打包产物，移除无用代码，压缩资源，提升页面加载速度。
 | 原文链接：http://book.55b9pj.asia/blog/887089.Doc

原标题：golang 项目环境变量加载方案
简介：SDK 版本兼容线上崩溃修复，处理 SDK 版本升级之后线上崩溃，定位 API 变更，做版本兼容适配改造。
 | 原文链接：http://book.55b9pj.asia/blog/636718.Doc

原标题：优化实践：Redis性能调优，避免大key热key
简介：前端 pdf 预览渲染方案对比，对比前端 PDF 预览库，分析性能、兼容性，给出业务选型参考。
 | 原文链接：http://book.55b9pj.asia/blog/817903.Doc

原标题：golang redis zset 排行榜业务实现
简介：golang raw socket 底层网络报文收发，raw socket 收发原始网络报文，做网络抓包数据包处理。
 | 原文链接：http://book.55b9pj.asia/blog/920545.Doc

?
