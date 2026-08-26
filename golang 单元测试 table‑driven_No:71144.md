最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 单元测试 table‑driven
简介：golang gorm 软删除实现逻辑，Gorm 开启软删除，删除数据仅标记，数据保留可恢复，满足业务数据留存。
 | 原文链接：http://wiki.mjwbao.asia/arts/949899.Doc

原标题：nodejs 项目 pm2 部署运维指南
简介：golang 时间戳秒毫秒纳秒转换，Unix UnixMilli UnixNano 互相转换，区分单位避免时间逻辑 bug。
 | 原文链接：http://wiki.mjwbao.asia/arts/820988.Doc

原标题：线上异常：接口偶发超时，完整定位过程记录
简介：golang proto 可选字段处理方案，protobuf 可选字段正确判断，区分未赋值与零值，业务逻辑不出现偏差。
 | 原文链接：http://wiki.mjwbao.asia/arts/430447.Doc

原标题：golang mysql 读写分离简单实现
简介：代理 HTTPS 证书访问异常处理，配置代理根证书，解决代理环境 HTTPS 证书校验失败无法访问外网。
 | 原文链接：http://wiki.mjwbao.asia/arts/110450.Doc

原标题：golang 协程 panic 捕获防止崩溃
简介：golang crypto 密码学最佳实践，go crypto 包加密签名，规避不安全算法，使用安全密码套件。
 | 原文链接：http://wiki.mjwbao.asia/arts/270315.Doc

原标题：快速入门Nginx基础配置，反向代理示例
简介：golang http client 全局变量复用，http Client 不要每次请求新建，复用 Transport 提升性能。
 | 原文链接：http://wiki.mjwbao.asia/arts/023887.Doc

原标题：入门实践：简易进度条CLI工具实现demo
简介：golang http 客户端连接泄漏排查，http client 未读取响应体导致连接无法复用，解决连接泄漏耗尽连接池。
 | 原文链接：http://wiki.mjwbao.asia/arts/770684.Doc

原标题：入门实践：简单重试逻辑封装实现
简介：golang websocket 服务端开发，Go 实现 WebSocket 服务端，处理连接、消息收发，实现长连接服务。
 | 原文链接：http://wiki.mjwbao.asia/arts/214032.Doc

原标题：golang es 映射 mapping 设计避坑
简介：golang channel 作为函数参数方向，声明 channel 入参方向，只读 channel 只写 channel 提升代码约束。
 | 原文链接：http://wiki.mjwbao.asia/arts/591966.Doc

原标题：golang 系统设计 protobuf json 性能对比
简介：golang init 函数合理使用边界，少用 init，优先显式调用初始化，便于控制初始化时机。
 | 原文链接：http://wiki.mjwbao.asia/arts/593047.Doc

原标题：TLS 版本兼容 HTTPS 握手失败
简介：golang net.Listener 包装自定义监听器，包装 Listener 做连接计数、连接拦截，扩展网络能力。
 | 原文链接：http://wiki.mjwbao.asia/arts/074735.Doc

原标题：golang 系统设计日志与 traceId 关联打印实现
简介：nodejs 接口限流防刷代码实现，Node 层实现接口限流，限制 IP 访问频次，防护接口被恶意高频调用。
 | 原文链接：http://wiki.mjwbao.asia/arts/017007.Doc

原标题：调优方案：数据库索引不要过度建立，权衡写性能
简介：Docker 网络模式容器互通设置，选择合适 Docker 网络模式，实现容器之间网络互相访问通信。
 | 原文链接：http://wiki.mjwbao.asia/arts/267132.Doc

原标题：新手参与开源社区贡献指南
简介：golang systemd 信号与优雅退出配合，systemd 停止服务发送 SIGTERM，go 程序捕获信号优雅关闭。
 | 原文链接：http://wiki.mjwbao.asia/arts/498275.Doc

原标题：Practice：实现异步回调处理通用组件封装
简介：golang fasthttp 高性能 http 库使用，fasthttp 高性能 http 实现，适合超高 QPS 场景，对比 net/http 差异。
 | 原文链接：http://wiki.mjwbao.asia/arts/623914.Doc

原标题：极简方式搭建个人技术文档站点
简介：golang nil channel 阻塞特性，nil channel 读写永久阻塞，理解 nil channel 行为做逻辑控制。
 | 原文链接：http://wiki.mjwbao.asia/arts/948523.Doc

原标题：排错：多实例部署session共享失效登录失效
简介：TCP 长连接参数优化 TIME_WAIT，调整 TCP 内核参数，优化长连接，减少大量 TIME_WAIT 连接占用资源。
 | 原文链接：http://wiki.mjwbao.asia/arts/830292.Doc

原标题：性能笔记：DNS缓存优化减少域名解析开销
简介：golang 定时任务 cron 使用指南，Go 使用 Cron 库实现定时任务，配置 corn 表达式调度业务任务。
 | 原文链接：http://wiki.mjwbao.asia/arts/617337.Doc

原标题：项目脚手架模板生成工具
简介：磁盘 inode 耗尽文件创建失败，排查磁盘 inode 占用，清理大量小文件，恢复文件创建能力。
 | 原文链接：http://wiki.mjwbao.asia/arts/481103.Doc

原标题：K8s 镜像拉取网络故障修复
简介：CI 构建缓存加速编译速度，开启 CI 流水线依赖缓存，复用上一次构建依赖包，缩短流水线构建耗时。
 | 原文链接：http://wiki.mjwbao.asia/arts/300444.Doc

原标题：排错：反向代理后获取真实IP全部变成内网IP
简介：golang go panic 合理使用边界，panic 只用于不可恢复程序错误，业务逻辑禁止直接 panic。
 | 原文链接：http://wiki.mjwbao.asia/arts/346821.Doc

原标题：golang 系统设计网关限流熔断降级配置思路
简介：CI 流水线构建失败日志排查，阅读 CI 流水线输出日志，定位构建脚本、依赖、环境导致流水线失败问题。
 | 原文链接：http://wiki.mjwbao.asia/arts/606033.Doc

原标题：Troubleshoot：磁盘inode耗尽，无法新建文件
简介：golang go‑zero api 接口开发与路由，go‑zero 编写 api 定义文件，生成代码开发 http 接口。
 | 原文链接：http://wiki.mjwbao.asia/arts/231171.Doc

原标题：后端登录鉴权模块完整开发
简介：golang 优雅处理 http 超时设置，Go HTTP 请求设置各类超时，防止请求无限阻塞，保护协程与连接。
 | 原文链接：http://wiki.mjwbao.asia/arts/378847.Doc

原标题：nestjs 拦截器过滤器管道实战
简介：golang net/http 超时全套配置，完整配置 Go HTTP 服务读写空闲超时，全方位防止请求挂住。
 | 原文链接：http://wiki.mjwbao.asia/arts/960695.Doc

原标题：后端分页查询逻辑代码实现
简介：nodejs 流处理大文件不占内存，使用 Node.js 流处理超大文件，边读边写，不需要全部加载进内存。
 | 原文链接：http://wiki.mjwbao.asia/arts/004165.Doc

原标题：golang 系统设计定时任务失败重试告警实现
简介：golang 压缩 zip 文件生成解压，golang 实现 zip 压缩打包，解压 zip 归档文件，处理批量文件归档。
 | 原文链接：http://wiki.mjwbao.asia/arts/421436.Doc

原标题：golang 系统设计 rest http 方法使用原则
简介：golang 大内存分配 GC 抖动规避，避免瞬时大量对象创建，分批处理，防止 GC 抖动业务抖动。
 | 原文链接：http://wiki.mjwbao.asia/arts/493654.Doc

原标题：golang 系统设计海量数据分页查询
简介：golang 信号捕获程序退出处理，Go 捕获操作系统信号，做资源回收，控制程序退出流程。
 | 原文链接：http://wiki.mjwbao.asia/arts/859329.Doc

原标题：Troubleshooting：K8sPodOOMKilled完整排查流程
简介：golang systemd 配置 go 服务部署，编写 systemd unit 文件管理 go 服务，开机自启、崩溃自动重启。
 | 原文链接：http://wiki.mjwbao.asia/arts/261711.Doc

原标题：Practice：实现异步任务结果查询回调实践
简介：golang redis 过期键监听回调，监听 key 过期事件，过期触发业务逻辑，实现过期自动处理业务场景。
 | 原文链接：http://wiki.mjwbao.asia/arts/806032.Doc

原标题：golang 系统设计一致性哈希原理讲解
简介：多版本开发环境共存配置，实现同一工具多版本并存，快速切换不同版本，适配不同项目对版本的差异化需求。
 | 原文链接：http://wiki.mjwbao.asia/arts/015115.Doc

原标题：golang consul 服务发现简单示例
简介：数据库死锁成因规避方案，讲解数据库死锁产生条件，给出业务层面规避手段，减少死锁事件发生。
 | 原文链接：http://wiki.mjwbao.asia/arts/808612.Doc

原标题：坑点：依赖缓存未更新，旧代码持续运行
简介：golang json omitempty 零值坑，omitempty 会忽略零值，区分业务是否需要输出零值字段。
 | 原文链接：http://wiki.mjwbao.asia/arts/363740.Doc

原标题：Hands‑on：静态资源CDN缓存控制头配置实践
简介：golang nats jetstream 持久消息队列，nats jetstream 持久化消息，保证消息不丢失，实现可靠消费。
 | 原文链接：http://wiki.mjwbao.asia/arts/377064.Doc

原标题：开发复盘：分布式会话共享多种方案实践
简介：golang go 爬虫异步并发抓取，协程池控制并发抓取网页，多协程采集，提升爬虫采集速度。
 | 原文链接：http://wiki.mjwbao.asia/arts/048920.Doc

原标题：golang mysql 行锁表锁场景区分
简介：pnpm 包管理工具实战避坑指南，使用 pnpm 管理项目依赖，梳理常见坑点，充分利用 pnpm 优势。
 | 原文链接：http://wiki.mjwbao.asia/arts/423536.Doc

原标题：golang 信号量控制并发数量
简介：主干开发团队代码合并策略，讲解主干开发模式，团队代码合并流程，适合高频迭代的团队协作模式。
 | 原文链接：http://wiki.mjwbao.asia/arts/704284.Doc

原标题：golang k8s 日志收集 efk 简单架构
简介：业务幂等键设计防重复逻辑，讲解幂等键设计思路，选择合适业务字段作为幂等标识，实现可靠防重复。
 | 原文链接：http://wiki.mjwbao.asia/arts/081236.Doc

原标题：开发复盘：大事务拆分优化业务性能实践
简介：浏览器本地存储安全使用技巧，讲解 localStorage、sessionStorage 使用边界，规避 XSS 泄露存储数据。
 | 原文链接：http://wiki.mjwbao.asia/arts/165844.Doc


二、踩坑排错｜Troubleshooting
原标题：Shell 运维脚本服务器效率提升
简介：golang go regexp 正则预编译，regexp.MustCompile 预编译正则，不要循环内部编译正则，节省 CPU。
 | 原文链接：http://wiki.mjwbao.asia/arts/500474.Doc

原标题：golang 系统设计 canary 金丝雀部署实操
简介：golang 协程泄露问题排查方法，识别 Go 协程泄露现象，分析泄露场景，给出排查定位协程泄露手段。
 | 原文链接：http://wiki.mjwbao.asia/arts/823874.Doc

原标题：golang 系统设计 go netpoll 多路复用简单理解
简介：TLS 版本兼容 HTTPS 握手失败，兼容老旧 TLS 协议版本，修复部分客户端 HTTPS 握手失败无法访问。
 | 原文链接：http://wiki.mjwbao.asia/arts/913922.Doc

原标题：新手教程：gitrebase基础使用与风险提示
简介：简易网关请求路由过滤模拟，模拟网关基础能力，实现请求路由转发、简单过滤，理解网关核心工作逻辑。
 | 原文链接：http://wiki.mjwbao.asia/arts/655696.Doc

原标题：RPC 接口字段增减兼容处理
简介：golang panic 崩溃日志完整收集，捕获所有 panic，打印堆栈，记录日志，方便定位崩溃根源。
 | 原文链接：http://wiki.mjwbao.asia/arts/314874.Doc

原标题：nodejs 事件循环机制完整讲解
简介：golang 程序崩溃 core dump 生成调试，开启 core dump，程序崩溃生成转储文件，事后分析崩溃原因。
 | 原文链接：http://wiki.mjwbao.asia/arts/772067.Doc

原标题：golang proto 默认值坑点梳理
简介：nodejs 流处理大文件不占内存，使用 Node.js 流处理超大文件，边读边写，不需要全部加载进内存。
 | 原文链接：http://wiki.mjwbao.asia/arts/141114.Doc

原标题：实战项目：百万日志文件解析处理脚本实践
简介：特殊输入字符过滤解析防护，过滤用户输入特殊字符，防止解析报错，规避恶意字符带来业务异常。
 | 原文链接：http://wiki.mjwbao.asia/arts/567806.Doc

原标题：webpack chunk 分包策略详解
简介：golang 跨平台系统差异处理方案，处理 windows linux mac 路径、信号、文件权限差异，代码跨平台兼容。
 | 原文链接：http://wiki.mjwbao.asia/arts/851840.Doc

原标题：golang 系统设计压力测试性能测试执行流程
简介：golang benchmark 参数‑bench‑mem 统计内存分配，benchmark 开启内存统计，观察内存分配次数大小。
 | 原文链接：http://wiki.mjwbao.asia/arts/966513.Doc

原标题：Git 误提交撤销回退实操教程
简介：文件编码统一随机乱码修复，统一项目全部文件读写编码，消除随机中文乱码，保证文本处理稳定。
 | 原文链接：http://wiki.mjwbao.asia/arts/236208.Doc

原标题：golang 系统设计 commit 提交规范约定
简介：golang grpc 双向流双向通信开发，grpc 双向流，服务端客户端持续互发消息，长连接流式业务场景。
 | 原文链接：http://wiki.mjwbao.asia/arts/775917.Doc

原标题：本地数据库开发环境搭建指南
简介：配置与镜像分离防止信息泄露，业务配置不打包进镜像，外部挂载配置，避免密钥配置随镜像泄露。
 | 原文链接：http://wiki.mjwbao.asia/arts/464047.Doc

原标题：golang 系统设计 sql 注入 xss 防护实践
简介：golang 网卡 ip 读取网络信息获取，程序读取本机网卡 IP，多网卡环境筛选业务使用 IP 地址。
 | 原文链接：http://wiki.mjwbao.asia/arts/574133.Doc

原标题：golang 系统设计主干开发 trunk‑based 讲解
简介：Git LFS 大文件推送失败解决，配置 Git LFS，处理仓库大文件，解决大文件推送报错推送失败。
 | 原文链接：http://wiki.mjwbao.asia/arts/606943.Doc

原标题：golang 系统设计 grpc http2 多路复用讲解
简介：golang grpc 客户端流上传数据，客户端流式请求，客户端分批上传数据到服务端，适合大文件传输。
 | 原文链接：http://wiki.mjwbao.asia/arts/718899.Doc

原标题：Practice：模拟第三方接口超时服务降级验证
简介：多套环境灵活切换配置方案，实现配置动态切换，通过环境变量、配置文件，快速切换开发测试生产环境。
 | 原文链接：http://wiki.mjwbao.asia/arts/345228.Doc

原标题：端口占用释放资源重启服务
简介：ICMP 放通网络丢包问题修复，放开 ICMP 协议，解决 MTU 问题导致网络丢包，修复网络不稳定现象。
 | 原文链接：http://wiki.mjwbao.asia/arts/619584.Doc

原标题：架构笔记：海量消息堆积架构处理能力设计
简介：WebSocket 双向通信 demo 开发，搭建简易 WebSocket 服务，实现客户端服务端双向消息推送，理解实时通信原理。
 | 原文链接：http://wiki.mjwbao.asia/arts/649366.Doc

原标题：golang 系统设计内部服务链路 trace 传递实现
简介：ORM 框架数据库增删改查实操，使用 ORM 框架完成数据库基础操作，减少手写 SQL，简化业务层数据库交互代码。
 | 原文链接：http://wiki.mjwbao.asia/arts/091297.Doc

原标题：优化实践：Redis性能调优，避免大key热key
简介：DNS 解析异常第三方调用故障，排查 DNS 解析故障，修复域名解析，恢复第三方接口网络调用。
 | 原文链接：http://wiki.mjwbao.asia/arts/423736.Doc

原标题：部署实践：Nginx高可用配置方案实践
简介：golang 定时任务任务持久化存储，定时任务持久化到数据库，服务重启任务不丢失，动态管理任务。
 | 原文链接：http://wiki.mjwbao.asia/arts/963519.Doc

原标题：Performance：批量导入数据性能优化实践
简介：golang json number 数字不转 float64，使用 json.Number 保留原始数字字符串，防止大数字精度丢失。
 | 原文链接：http://wiki.mjwbao.asia/arts/741070.Doc

原标题：Troubleshooting：依赖安装失败完整排查清单
简介：golang GC 频繁 STW 停顿优化，减少小对象分配，调整 GOGC，降低 GC 停顿对接口延迟影响。
 | 原文链接：http://wiki.mjwbao.asia/arts/412626.Doc

原标题：运维笔记：系统监控指标大盘搭建实操
简介：golang go 并发模式 fan‑out fan‑in，fanout 分发任务 fanin 汇总结果，多协程并发处理任务。
 | 原文链接：http://wiki.mjwbao.asia/arts/233032.Doc

原标题：golang 系统设计定时任务动态启停配置方案
简介：css 动画性能优化 GPU 加速，优化 CSS 动画，使用 GPU 加速属性，避免动画过程页面卡顿掉帧。
 | 原文链接：http://wiki.mjwbao.asia/arts/340774.Doc

原标题：Security：文件上传漏洞攻击面完整防护方案
简介：express 中间件开发业务实践，开发 Express 自定义中间件，拦截请求，实现鉴权、日志记录等通用逻辑。
 | 原文链接：http://wiki.mjwbao.asia/arts/385171.Doc

原标题：git stash 代码暂存切换分支
简介：golang redis 过期键监听回调，监听 key 过期事件，过期触发业务逻辑，实现过期自动处理业务场景。
 | 原文链接：http://wiki.mjwbao.asia/arts/992728.Doc

原标题：文件监控服务自动重启开发
简介：golang sync.Mutex 互斥锁正确模式，互斥锁 defer Unlock，锁粒度控制，避免锁范围过大。
 | 原文链接：http://wiki.mjwbao.asia/arts/208264.Doc

原标题：快速入门GraphQL基础查询语法示例
简介：程序性能指标 CPU 内存监控，讲解基础性能指标含义，简单实现监控采集，初步定位程序运行性能瓶颈。
 | 原文链接：http://wiki.mjwbao.asia/arts/225221.Doc

原标题：实战：gRPC服务编写客户端服务端完整demo
简介：golang sql 注入风险规避要点，参数化查询杜绝 sql 注入，禁止字符串拼接 SQL 语句执行。
 | 原文链接：http://wiki.mjwbao.asia/arts/482032.Doc

原标题：YAML 配置文件语法快速上手
简介：golang icmp ping 程序实现，go 实现 ping 工具发送 icmp 报文，检测网络连通性。
 | 原文链接：http://wiki.mjwbao.asia/arts/041969.Doc

原标题：Troubleshooting：数据库索引失效，查询性能暴跌
简介：golang jwt 令牌刷新逻辑实现，实现 JWT 双令牌机制，access 短期有效 refresh 刷新令牌，实现无感续期登录。
 | 原文链接：http://wiki.mjwbao.asia/arts/820503.Doc

原标题：实践：Git大仓库历史清理减小仓库体积实践
简介：批量操作分批处理防止 OOM，大批量数据处理不一次性加载全部数据，分批循环处理，避免内存溢出。
 | 原文链接：http://wiki.mjwbao.asia/arts/408430.Doc

原标题：性能笔记：锁优化减少竞争提升并发吞吐
简介：golang http 客户端连接泄漏排查，http client 未读取响应体导致连接无法复用，解决连接泄漏耗尽连接池。
 | 原文链接：http://wiki.mjwbao.asia/arts/467651.Doc

原标题：安全笔记：文件下载接口路径校验安全
简介：业务错误码完整落地实践，落地完整业务错误码，枚举全部业务异常，统一返回，配套文档说明。
 | 原文链接：http://wiki.mjwbao.asia/arts/714630.Doc

原标题：新手指南：读懂项目构建脚本作用
简介：全量回归测试提升代码质量，搭建全量回归测试集，版本发布执行回归测试，避免迭代引入旧 bug。
 | 原文链接：http://wiki.mjwbao.asia/arts/693274.Doc

原标题：跨库查询性能优化处理
简介：golang go http 静态文件禁止目录遍历，http.FileServer 防止../ 路径穿越，了解底层安全实现。
 | 原文链接：http://wiki.mjwbao.asia/arts/420360.Doc

原标题：踩坑记录：浮点数作为Rediskey匹配异常
简介：golang go 初始化顺序包变量 init 函数，包级变量初始化，init 执行顺序，理解包加载执行流程。
 | 原文链接：http://wiki.mjwbao.asia/arts/719736.Doc

原标题：golang rate‑limiter 限流组件
简介：手写简易 ORM 理解对象映射，手写极简 ORM 示例，理解对象与数据库表字段映射底层原理。
 | 原文链接：http://wiki.mjwbao.asia/arts/450954.Doc

三、实战开发｜Practice
原标题：线上接口超时故障排查思路
简介：GraphQL 接口查询优化实操，体验 GraphQL 查询方式，按需获取字段，减少冗余数据传输，优化接口请求效率。
 | 原文链接：http://wiki.mjwbao.asia/arts/826832.Doc

原标题：优化实践：Redis管道、批量命令减少网络往返
简介：GitHub Markdown 文档语法汇总，整理 Markdown 常用语法，编写仓库 README、文档，提升开源项目文档排版质量。
 | 原文链接：http://wiki.mjwbao.asia/arts/333952.Doc

原标题：坑点：依赖缓存未更新，旧代码持续运行
简介：前后端会话登录状态持久化，实现登录状态持久存储，重启服务登录状态不丢失，保障会话稳定性。
 | 原文链接：http://wiki.mjwbao.asia/arts/615480.Doc

原标题：Practice：模拟网络抖动验证服务容错能力
简介：golang 项目 go mod 依赖管理，Go Mod 管理项目依赖，下载、升级、清理依赖，解决依赖版本管理。
 | 原文链接：http://wiki.mjwbao.asia/arts/172460.Doc

原标题：安全复盘：定时任务权限过大风险管控
简介：重复提交幂等防护再次讲解，梳理前端重复点击、网络重试场景，落地接口幂等，杜绝重复业务。
 | 原文链接：http://wiki.mjwbao.asia/arts/074888.Doc

原标题：数据库事务 ACID 原理讲解
简介：golang jaeger 链路追踪部署对接，jaeger 接收 opentelemetry 链路数据，可视化完整调用链路。
 | 原文链接：http://wiki.mjwbao.asia/arts/056218.Doc

原标题：安全实践：最小权限原则数据库账号管控
简介：golang go 模板缓存预编译模板，预编译 html 模板，程序启动加载，避免每次请求解析模板损耗性能。
 | 原文链接：http://wiki.mjwbao.asia/arts/916196.Doc

原标题：OpenSource：如何高效阅读大型开源项目源码
简介：golang 容器信号转发处理问题修复，docker/k8s 正确转发 SIGTERM 信号，保证 go 程序收到信号优雅退出。
 | 原文链接：http://wiki.mjwbao.asia/arts/702259.Doc

原标题：golang 系统设计 lru 缓存算法实现思路
简介：golang 命令行交互 cobra 开发 cli，cobra 库开发功能完善命令行工具，子命令参数标志解析。
 | 原文链接：http://wiki.mjwbao.asia/arts/604361.Doc

原标题：开发记录：短信发送服务封装，失败重试策略
简介：golang make new 关键字使用区别，分清 new 与 make 适用类型，正确初始化切片 map 通道，杜绝 nil 引发 panic。
 | 原文链接：http://wiki.mjwbao.asia/arts/939592.Doc

原标题：golang 系统设计 rest api 接口设计最佳实践
简介：golang go 程序运行时动态修改配置，运行时热加载配置结构体，原子更新保证并发读取安全。
 | 原文链接：http://wiki.mjwbao.asia/arts/675999.Doc

原标题：运维笔记：服务器定时任务运维脚本编写
简介：程序日志分级输出规范实践，区分日志等级，规范日志打印内容，合理输出日志，方便线上问题排查定位。
 | 原文链接：http://wiki.mjwbao.asia/arts/155730.Doc

原标题：Architecture：中小型后端服务整体架构设计复盘
简介：nodejs 全局异常捕获进程防护，捕获未捕获异常与 Promise 拒绝，尽量保护进程不因为异常直接退出。
 | 原文链接：http://wiki.mjwbao.asia/arts/429728.Doc

原标题：调优方案：Docker容器内核参数性能调优
简介：golang 错误栈捕获打印方案，捕获错误完整调用堆栈，线上日志输出堆栈，快速定位错误发生代码位置。
 | 原文链接：http://wiki.mjwbao.asia/arts/903177.Doc

原标题：Troubleshooting：k8s镜像拉取失败镜像仓库网络问题
简介：布隆过滤器数据高效去重实现，实现布隆过滤器组件，用于海量数据去重，节省大量内存空间。
 | 原文链接：http://wiki.mjwbao.asia/arts/602552.Doc

原标题：golang prometheus 指标暴露实现
简介：多版本开发环境共存配置，实现同一工具多版本并存，快速切换不同版本，适配不同项目对版本的差异化需求。
 | 原文链接：http://wiki.mjwbao.asia/arts/018740.Doc

原标题：golang 系统设计数据库查询优化完整流程
简介：golang prometheus client 业务埋点实操，prometheus client‑go 业务埋点，计数器、仪表盘、直方图指标开发。
 | 原文链接：http://wiki.mjwbao.asia/arts/205377.Doc

原标题：架构复盘：分表扩容架构平滑迁移思路
简介：本地数据库开发环境搭建指南，讲解数据库安装配置、账号权限设置、连接测试，快速搭建用于开发调试的数据库实例。
 | 原文链接：http://wiki.mjwbao.asia/arts/385106.Doc

原标题：golang 系统设计 grpc http2 多路复用讲解
简介：golang cobra 命令行参数配置绑定，cobra 绑定配置文件环境变量命令行参数，多源配置合并。
 | 原文链接：http://wiki.mjwbao.asia/arts/564366.Doc

原标题：gRPC 服务端客户端入门示例
简介：golang go http 服务器优雅关闭完整代码，http.Server Shutdown，等待现有请求处理完成关闭服务。
 | 原文链接：http://wiki.mjwbao.asia/arts/993849.Doc

原标题：项目实践：幂等表实现接口幂等业务实践
简介：前端 pdf 预览渲染方案对比，对比前端 PDF 预览库，分析性能、兼容性，给出业务选型参考。
 | 原文链接：http://wiki.mjwbao.asia/arts/347031.Doc

原标题：线上异常：缓存雪崩带来数据库压力瞬间飙升
简介：golang 设置 net.Conn 读写超时，每次读写设置超时，防止连接永久阻塞挂起不返回。
 | 原文链接：http://wiki.mjwbao.asia/arts/534608.Doc

原标题：安全笔记：第三方SDK安全风险评估要点
简介：接口限流逻辑简单模拟实现，编写简易限流逻辑，限制接口访问频次，保护服务，避免短时间大量请求压垮系统。
 | 原文链接：http://wiki.mjwbao.asia/arts/488975.Doc

原标题：部署实践：HTTPS证书自动续期配置实践
简介：golang 定时任务任务持久化存储，定时任务持久化到数据库，服务重启任务不丢失，动态管理任务。
 | 原文链接：http://wiki.mjwbao.asia/arts/115117.Doc

原标题：项目实践：本地模拟多节点分布式系统实践
简介：nodejs jwt 登录鉴权完整示例，Node 实现 JWT 登录鉴权，登录签发令牌，接口校验令牌身份。
 | 原文链接：http://wiki.mjwbao.asia/arts/909541.Doc

原标题：Debug：异步任务堆积，服务响应越来越慢
简介：nodejs 内存溢出问题排查修复，Node.js 程序 OOM 排查流程，定位内存泄露，调整内存限制修复崩溃。
 | 原文链接：http://wiki.mjwbao.asia/arts/040971.Doc

原标题：实战：Nginx配置静态站点、反向代理、负载均衡
简介：CPU 亲和性配置负载均衡调度，配置进程 CPU 亲和，均衡利用多核 CPU，优化程序调度性能。
 | 原文链接：http://wiki.mjwbao.asia/arts/487654.Doc

原标题：golang es bool 查询条件组合技巧
简介：golang cobra 命令行参数配置绑定，cobra 绑定配置文件环境变量命令行参数，多源配置合并。
 | 原文链接：http://wiki.mjwbao.asia/arts/465243.Doc

原标题：实战项目：数据导出Excel百万级大数据导出方案
简介：golang accept 错误循环崩溃处理，accept 返回系统错误，处理临时错误，避免死循环占满 CPU。
 | 原文链接：http://wiki.mjwbao.asia/arts/603343.Doc

原标题：架构复盘：数据库主从架构设计与延迟应对方案
简介：消息消费重试次数限制防爆炸，限制消息最大重试次数，防止失败消息无限重试造成消息爆炸堆积。
 | 原文链接：http://wiki.mjwbao.asia/arts/188644.Doc

原标题：Troubleshoot：RPC序列化对象字段增减兼容踩坑
简介：golang io.Reader io.Writer 接口理解，io 读写接口，各类数据源统一抽象，适配 io 复制函数。
 | 原文链接：http://wiki.mjwbao.asia/arts/848815.Doc

原标题：golang docker 运行 etcd 本地测试
简介：GC 垃圾回收优化降低 CPU 占用，调整 GC 参数，优化对象创建销毁，降低垃圾回收带来 CPU 开销。
 | 原文链接：http://wiki.mjwbao.asia/arts/840753.Doc

原标题：零基础理解依赖管理与包管理器
简介：golang 接口返回统一封装工具，封装 Go 接口统一返回工具，标准化成功失败返回结构体。
 | 原文链接：http://wiki.mjwbao.asia/arts/470380.Doc

原标题：记一次分布式锁失效引发的数据错乱问题
简介：golang makefile 多平台编译脚本，makefile 一键交叉编译多平台二进制，打包镜像，执行测试。
 | 原文链接：http://wiki.mjwbao.asia/arts/401249.Doc

原标题：golang es 分页深分页性能优化
简介：golang k8s 客户端 client‑go 简单示例，client‑go 操作 k8s 资源，增删改查 pod deployment 等资源对象。
 | 原文链接：http://wiki.mjwbao.asia/arts/077027.Doc

原标题：golang 系统设计单元测试表驱动测试 table‑driven
简介：代理 HTTPS 证书访问异常处理，配置代理根证书，解决代理环境 HTTPS 证书校验失败无法访问外网。
 | 原文链接：http://wiki.mjwbao.asia/arts/924680.Doc

原标题：实战：WebSocket断线重连完整业务处理实践
简介：golang gzip 压缩 http 响应，服务端开启 gzip 压缩，减小接口响应体积，降低网络传输耗时。
 | 原文链接：http://wiki.mjwbao.asia/arts/326500.Doc

原标题：零基础理解跨域问题产生原因与基础方案
简介：golang sql 注入风险规避要点，参数化查询杜绝 sql 注入，禁止字符串拼接 SQL 语句执行。
 | 原文链接：http://wiki.mjwbao.asia/arts/142429.Doc

原标题：Debug：分布式会话时钟不同步令牌提前失效
简介：跨平台换行符统一异常修复，统一代码文件换行符，解决不同操作系统换行符不一致带来脚本执行异常。
 | 原文链接：http://wiki.mjwbao.asia/arts/448658.Doc

原标题：golang k8s 命名空间资源隔离方案
简介：golang 定时任务 cron 使用指南，Go 使用 Cron 库实现定时任务，配置 corn 表达式调度业务任务。
 | 原文链接：http://wiki.mjwbao.asia/arts/719511.Doc

四、架构设计｜Architecture
原标题：Performance：数据库大表优化，冷热数据分离
简介：golang go 锁竞争导致 CPU 飙升，识别锁竞争场景，减少锁粒度，优化并发逻辑降低 CPU 开销。
 | 原文链接：http://wiki.mjwbao.asia/arts/470728.Doc

原标题：golang 系统设计 e2e 端到端测试简单落地思路
简介：异步任务堆积消费能力优化，处理消息任务堆积问题，提升消费处理速度，恢复队列正常处理水位。
 | 原文链接：http://wiki.mjwbao.asia/arts/590703.Doc

原标题：快速上手搭建简易内网测试服务
简介：golang wasm 浏览器 js 交互，go wasm 与 js 互相调用，浏览器端 go 程序操作 dom 调用 js 函数。
 | 原文链接：http://wiki.mjwbao.asia/arts/522611.Doc

原标题：坑点：环境配置写死代码，上线忘记修改
简介：golang context.WithValue 传递元数据，WithValue 只传 traceId 鉴权元数据，不要传业务大对象。
 | 原文链接：http://wiki.mjwbao.asia/arts/524399.Doc

原标题：golang 系统设计消息堆积排查扩容完整步骤
简介：golang cgo 调用 C 语言代码示例，cgo 调用 C 函数，go 与 C 互相调用，对接 C 语言库能力。
 | 原文链接：http://wiki.mjwbao.asia/arts/204815.Doc

原标题：线程调度优化减少上下文切换
简介：golang 速率限制令牌桶实现，Go 实现令牌桶限流算法，可复用限流器，控制业务调用速率。
 | 原文链接：http://wiki.mjwbao.asia/arts/890692.Doc

原标题：开发记录：短信发送服务封装，失败重试策略
简介：数据库排序规则统一结果一致，统一数据库表排序规则，解决不同环境查询排序结果不一致问题。
 | 原文链接：http://wiki.mjwbao.asia/arts/029562.Doc

原标题：数据库连接池参数调优
简介：端口占用释放资源重启服务，查找占用端口进程，结束占用进程，释放端口，让服务能够正常启动监听。
 | 原文链接：http://wiki.mjwbao.asia/arts/296162.Doc

原标题：golang 系统设计 go benchmark 性能测试实操
简介：golang go 版本管理 go install 安装工具，go install 安装指定版本 go 工具，管理本地 go 工具版本。
 | 原文链接：http://wiki.mjwbao.asia/arts/306640.Doc

原标题：golang 系统设计缓存 key 命名规范最佳实践
简介：golang go 程序抢占调度理解，理解 go 抢占式调度原理，长循环阻塞调度，造成协程调度延迟。
 | 原文链接：http://wiki.mjwbao.asia/arts/673351.Doc

原标题：golang 系统设计数据库查询优化完整流程
简介：nodejs 接口限流防刷代码实现，Node 层实现接口限流，限制 IP 访问频次，防护接口被恶意高频调用。
 | 原文链接：http://wiki.mjwbao.asia/arts/661003.Doc

原标题：golang 系统设计基准测试 benchmark 编写
简介：多规则数据脱敏组件开发，封装通用脱敏组件，支持多种脱敏规则，项目多处复用脱敏逻辑。
 | 原文链接：http://wiki.mjwbao.asia/arts/960889.Doc

原标题：golang 系统设计 issue 模板 bug 反馈模板
简介：程序性能指标 CPU 内存监控，讲解基础性能指标含义，简单实现监控采集，初步定位程序运行性能瓶颈。
 | 原文链接：http://wiki.mjwbao.asia/arts/615632.Doc

原标题：golang mysql 读写分离简单实现
简介：跨平台 uniapp 多端开发实操，uniapp 开发一套代码，编译多端，梳理多端差异处理与适配技巧。
 | 原文链接：http://wiki.mjwbao.asia/arts/557271.Doc

原标题：golang 系统设计线上日志快速检索技巧
简介：golang net/url 路径拼接处理，url.ParseRequestURI 处理请求 url，正确拼接 url 路径避免拼接错误。
 | 原文链接：http://wiki.mjwbao.asia/arts/113753.Doc

原标题：踩坑：幂等键生成逻辑错误造成重复业务
简介：前后端会话登录状态持久化，实现登录状态持久存储，重启服务登录状态不丢失，保障会话稳定性。
 | 原文链接：http://wiki.mjwbao.asia/arts/488438.Doc

原标题：Performance：避免全表扫描索引失效场景汇总
简介：分布式事务最终一致性实现，基于可靠消息实现最终一致性，解决跨数据库跨服务业务数据一致性。
 | 原文链接：http://wiki.mjwbao.asia/arts/485860.Doc

原标题：golang 空接口 interface 使用技巧
简介：golang go 单二进制文件静态编译交叉编译，交叉编译不同操作系统架构二进制文件，实现一次编译多平台运行。
 | 原文链接：http://wiki.mjwbao.asia/arts/834659.Doc

?
