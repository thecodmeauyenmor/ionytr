最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计配置敏感信息加密存储
简介：开发测试生产多环境配置区分，讲解三套环境配置分离思路，配置文件隔离，防止开发配置泄露到生产环境。
 | 原文链接：http://zhishi.drmdtp.asia/blog/3427365.sHtMl

原标题：golang 系统设计短信发送限流降级
简介：用户敏感数据脱敏代码实现，编写数据脱敏工具，对手机号、身份证做脱敏处理，防止敏感信息直接泄露。
 | 原文链接：http://zhishi.drmdtp.asia/blog/3782229.sHtMl

原标题：踩坑：幂等键生成逻辑错误造成重复业务
简介：多操作系统开发兼容处理，解决不同系统路径、换行符、权限差异，保证项目跨平台正常运行。
 | 原文链接：http://zhishi.drmdtp.asia/blog/9387622.sHtMl

原标题：golang k8s secret 加密敏感信息
简介：代理 HTTPS 证书访问异常处理，配置代理根证书，解决代理环境 HTTPS 证书校验失败无法访问外网。
 | 原文链接：http://zhishi.drmdtp.asia/blog/0574232.sHtMl

原标题：golang 系统设计分布式配置中心思路
简介：golang goroutine 泄露检测告警实现，监控 goroutine 数量，突增触发告警，提早发现协程泄露。
 | 原文链接：http://zhishi.drmdtp.asia/blog/8393022.sHtMl

原标题：快速入门容器基础概念，理解镜像与容器
简介：golang http 重定向策略自定义，CheckRedirect 自定义重定向逻辑，限制重定向次数，防止死循环。
 | 原文链接：http://zhishi.drmdtp.asia/blog/1257976.sHtMl

原标题：缓存基础原理与简单代码实现
简介：模拟登录鉴权权限判断示例，实现简易登录流程，会话状态维护，完成接口权限校验，理解身份鉴权基础逻辑。
 | 原文链接：http://zhishi.drmdtp.asia/blog/0958021.sHtMl

原标题：安全实践：接口速率限制防止暴力破解
简介：golang json number 数字不转 float64，使用 json.Number 保留原始数字字符串，防止大数字精度丢失。
 | 原文链接：http://zhishi.drmdtp.asia/blog/6717854.sHtMl

原标题：golang 系统设计分布式事务业务选型决策思路
简介：golang snowflake 时钟回拨解决方案，雪花算法处理时钟回拨，防止生成重复 ID，保证 ID 全局唯一。
 | 原文链接：http://zhishi.drmdtp.asia/blog/2763114.sHtMl

原标题：golang 系统设计灰度发布流量切分实现
简介：golang go‑zero 配置中心热更新，go‑zero 对接 etcd 配置中心，配置热更新无需重启服务。
 | 原文链接：http://zhishi.drmdtp.asia/blog/6498649.sHtMl

原标题：项目实践：Docker多环境镜像构建策略实践
简介：golang kitex 中间件与元数据传递，kitex 自定义中间件，透传 traceId 鉴权元数据，统一处理请求。
 | 原文链接：http://zhishi.drmdtp.asia/blog/2216825.sHtMl

原标题：开发复盘：实现定时任务调度服务支持动态任务
简介：项目语义化版本号规范管理，遵循语义化版本规范管理项目版本，明确主次版本变更含义。
 | 原文链接：http://zhishi.drmdtp.asia/blog/3403897.sHtMl

原标题：golang base64 编码解码实操
简介：Nginx 透传真实客户端 IP 配置，配置 Nginx 把真实客户端 IP 传递后端服务，后端拿到访问者真实 IP。
 | 原文链接：http://zhishi.drmdtp.asia/blog/3691725.sHtMl

原标题：记一次限流组件误配置把正常用户拦截
简介：数据库主从延迟业务兼容处理，业务适配主从复制延迟，避免读取从库拿到还未同步完成旧数据。
 | 原文链接：http://zhishi.drmdtp.asia/blog/0455544.sHtMl

原标题：golang 布隆过滤器实现去重
简介：RPC 接口字段增减兼容处理，RPC 接口新增删除字段做好向前兼容，老版本服务不会解析报错崩溃。
 | 原文链接：http://zhishi.drmdtp.asia/blog/2768058.sHtMl

原标题：优化实践：内存池思想减少频繁分配释放
简介：对象存储上传下载权限实操，演示对象存储文件上传、下载、访问权限设置，适配业务文件存储场景。
 | 原文链接：http://zhishi.drmdtp.asia/blog/0287617.sHtMl

原标题：新手向：项目目录结构规范与含义解析
简介：golang 重试退避机制代码实现，Go 实现请求重试与指数退避，处理临时故障，提升调用稳定性。
 | 原文链接：http://zhishi.drmdtp.asia/blog/5992797.sHtMl

原标题：避坑：请求未设置read超时无限挂起连接
简介：golang 优雅处理 http 超时设置，Go HTTP 请求设置各类超时，防止请求无限阻塞，保护协程与连接。
 | 原文链接：http://zhishi.drmdtp.asia/blog/2761161.sHtMl

原标题：golang 系统设计故障复盘模板 postmortem 参考
简介：golang io.Copy 流式拷贝数据，io.Copy 拷贝 reader 到 writer，不用加载全部数据到内存。
 | 原文链接：http://zhishi.drmdtp.asia/blog/7704572.sHtMl

原标题：性能复盘：数据库回滚日志过大性能影响优化
简介：golang gin 框架接口开发实战，Gin 框架搭建 HTTP 服务，开发增删改查接口，快速完成后端接口开发。
 | 原文链接：http://zhishi.drmdtp.asia/blog/4387532.sHtMl

原标题：Git 分支切换合并删除完整操作
简介：golang 结构体 json 序列化坑点，梳理 Go 结构体 JSON 序列化高频坑点，字段大小写、零值处理问题。
 | 原文链接：http://zhishi.drmdtp.asia/blog/3400772.sHtMl

原标题：golang k8s liveness readiness 探针
简介：CI 构建缓存加速编译速度，开启 CI 流水线依赖缓存，复用上一次构建依赖包，缩短流水线构建耗时。
 | 原文链接：http://zhishi.drmdtp.asia/blog/4816100.sHtMl

原标题：从零学习简单分布式ID生成思路
简介：golang rate 令牌桶限流器源码理解，拆解令牌桶限流核心逻辑，理解令牌生成消耗，掌握限流底层原理。
 | 原文链接：http://zhishi.drmdtp.asia/blog/5080648.sHtMl

原标题：运维笔记：备份策略数据库定时备份脚本
简介：react hooks 常见陷阱避坑指南，梳理 React Hooks 高频踩坑点，依赖数组、闭包陷阱，写出稳定组件。
 | 原文链接：http://zhishi.drmdtp.asia/blog/6087042.sHtMl

原标题：异步异常捕获避免进程崩溃
简介：golang json omitempty 零值坑，omitempty 会忽略零值，区分业务是否需要输出零值字段。
 | 原文链接：http://zhishi.drmdtp.asia/blog/9428750.sHtMl

原标题：golang 系统设计 mq 消息丢失完整防护
简介：golang 单元测试 table‑driven，表格驱动单元测试写法，批量输入多组测试用例，简化单元测试代码。
 | 原文链接：http://zhishi.drmdtp.asia/blog/6639139.sHtMl

原标题：项目实践：搭建个人API网关最小实现版本
简介：golang 接口限流中间件开发，Gin 开发限流中间件，接口层实现访问频率限制，防护接口流量。
 | 原文链接：http://zhishi.drmdtp.asia/blog/4578741.sHtMl

原标题：开发记录：接口请求日志记录完整中间件实现
简介：golang sync/atomic 原子操作使用注意，理解原子操作内存顺序，规避原子操作错误使用带来 bug。
 | 原文链接：http://zhishi.drmdtp.asia/blog/2155126.sHtMl

原标题：静态站点自动部署发布方案
简介：golang 云存储 s3 协议对象存储，go s3 客户端，兼容 minio 阿里云 oss，实现文件上传下载签名访问。
 | 原文链接：http://zhishi.drmdtp.asia/blog/6751069.sHtMl

原标题：复盘总结：接口重构兼容旧版本改造复盘
简介：Nginx 静态代理负载均衡全套配置，一套 Nginx 配置示例，覆盖静态资源、反向代理、负载均衡场景。
 | 原文链接：http://zhishi.drmdtp.asia/blog/4878434.sHtMl

原标题：golang 系统设计降级策略开关配置方案
简介：golang go get 升级降级依赖版本，go get 指定版本升级降级依赖包，管理第三方库版本。
 | 原文链接：http://zhishi.drmdtp.asia/blog/2602322.sHtMl

原标题：golang 系统设计故障预案编写模板参考示例
简介：golang go 接口定义原则小接口，go 小接口设计原则，接口尽量小，只定义必要方法，提升代码灵活性。
 | 原文链接：http://zhishi.drmdtp.asia/blog/4362618.sHtMl

原标题：性能笔记：连接池参数调优数据库RPC连接池
简介：线程池拒绝策略任务丢失防护，合理设置线程池拒绝策略，处理任务队列满场景，避免业务任务直接丢失。
 | 原文链接：http://zhishi.drmdtp.asia/blog/1556486.sHtMl

原标题：日志切割配置防止日志丢失
简介：移动端适配 rem vw 方案对比，对比 rem 与 vw 移动端适配方案，分析优缺点，给出选型建议。
 | 原文链接：http://zhishi.drmdtp.asia/blog/4149369.sHtMl

原标题：坑点：Docker资源限制未设置导致宿主机卡死
简介：开源项目构建失败排查步骤，梳理构建报错排查流程，从依赖、网络、权限、脚本多角度定位项目构建失败原因。
 | 原文链接：http://zhishi.drmdtp.asia/blog/0775545.sHtMl

原标题：golang 大文件 http 下载服务
简介：nodejs 信号处理优雅关闭服务，监听系统信号，执行资源清理，实现 Node 服务优雅停机，拒绝粗暴杀死进程。
 | 原文链接：http://zhishi.drmdtp.asia/blog/2984242.sHtMl

原标题：Git LFS 大文件推送失败解决
简介：golang defer panic 异常处理，理解 defer 延迟执行，panic 恐慌捕获，实现函数资源释放异常保护。
 | 原文链接：http://zhishi.drmdtp.asia/blog/0052599.sHtMl

原标题：golang 系统设计延迟消息实现几种方案对比
简介：Git commit 钩子提交规范校验，配置 Git 提交钩子，提交代码自动校验提交信息格式，规范提交记录。
 | 原文链接：http://zhishi.drmdtp.asia/blog/4058790.sHtMl

原标题：数据库排序规则统一结果一致
简介：接口签名验签完整安全方案，一套完整接口签名方案，包含签名生成、请求携带、服务端验签校验。
 | 原文链接：http://zhishi.drmdtp.asia/blog/4720505.sHtMl

原标题：安全复盘：消息队列未授权访问安全加固
简介：大事务拆分回滚日志暴涨解决，拆分大型数据库事务，减少回滚日志生成量，避免磁盘被回滚日志占满。
 | 原文链接：http://zhishi.drmdtp.asia/blog/7543686.sHtMl


二、踩坑排错｜Troubleshooting
原标题：golang 系统设计内存复用 sync.pool 使用
简介：golang 优雅处理 http 重定向逻辑，自定义控制 http 重定向跳转次数，防止无限重定向死循环。
 | 原文链接：http://zhishi.drmdtp.asia/blog/7956123.sHtMl

原标题：golang 信号量控制并发数量
简介：golang 半关闭 tcp 连接 shutdown，tcp 连接 shutdown 半关闭，单向关闭读或者写，理解 tcp 关闭流程。
 | 原文链接：http://zhishi.drmdtp.asia/blog/4207432.sHtMl

原标题：golang kafka 核心概念分区副本
简介：ICMP 放通网络丢包问题修复，放开 ICMP 协议，解决 MTU 问题导致网络丢包，修复网络不稳定现象。
 | 原文链接：http://zhishi.drmdtp.asia/blog/3008437.sHtMl

原标题：golang 系统设计定时任务调度时间校准要点
简介：golang os.Exit 退出程序注意 defer 不执行，os.Exit 会直接退出，不会执行 defer，优雅退出不要直接 os.Exit。
 | 原文链接：http://zhishi.drmdtp.asia/blog/8785462.sHtMl

原标题：golang 系统设计 ci 流水线安全管控思路
简介：golang elasticsearch 客户端 golang 实操，es 客户端文档增删改查，条件搜索聚合统计对接搜索引擎。
 | 原文链接：http://zhishi.drmdtp.asia/blog/4481671.sHtMl

原标题：golang redis 热点 key 业务规避
简介：版本升级服务启动失败处理，版本更新之后服务无法启动，对比新旧版本配置、依赖差异，完成故障修复。
 | 原文链接：http://zhishi.drmdtp.asia/blog/5866891.sHtMl

原标题：golang 系统设计逻辑删除物理删除选型对比
简介：SourceMap 生成线上报错定位，项目打包生成 SourceMap 文件，线上报错可以还原源码，快速定位报错位置。
 | 原文链接：http://zhishi.drmdtp.asia/blog/9036240.sHtMl

原标题：golang 系统设计 webhook 回调处理架构
简介：分页逻辑错误数据漏查修复，修复分页查询逻辑漏洞，解决分页漏数据、重复返回数据等业务问题。
 | 原文链接：http://zhishi.drmdtp.asia/blog/7273835.sHtMl

原标题：golang websocket 服务端开发
简介：内存广播本地进程消息通知，实现进程内内存消息广播，进程内部模块之间事件通知解耦。
 | 原文链接：http://zhishi.drmdtp.asia/blog/5920947.sHtMl

原标题：golang yaml 解析配置加载实操
简介：golang go embed 嵌入静态资源文件，使用 go embed 把静态文件编译进二进制，单文件部署携带静态资源。
 | 原文链接：http://zhishi.drmdtp.asia/blog/5064210.sHtMl

原标题：开源实践：维护开源项目Issue管理经验总结
简介：golang 制品镜像版本号规范管理，镜像版本号结合 git commit，明确每个镜像对应代码版本便于追溯。
 | 原文链接：http://zhishi.drmdtp.asia/blog/3431325.sHtMl

原标题：golang 系统设计分库分表扩容平滑迁移
简介：golang 压缩 zip 文件生成解压，golang 实现 zip 压缩打包，解压 zip 归档文件，处理批量文件归档。
 | 原文链接：http://zhishi.drmdtp.asia/blog/7807084.sHtMl

原标题：避坑：请求未设置read超时无限挂起连接
简介：golang go‑zero 分布式锁组件使用，go‑zero 内置 redis 分布式锁，业务直接调用实现并发控制。
 | 原文链接：http://zhishi.drmdtp.asia/blog/5043663.sHtMl

原标题：架构笔记：冷热数据分离架构设计与迁移
简介：golang go 包循环导入报错解决，A 导入 B B 导入 A，循环导入报错，重构代码拆分包消除循环依赖。
 | 原文链接：http://zhishi.drmdtp.asia/blog/0866245.sHtMl

原标题：golang 系统设计消息体序列化选型对比
简介：golang 子进程执行命令标准流处理，exec.Command 执行外部命令，处理 stdout stderr，防止缓冲区阻塞卡死。
 | 原文链接：http://zhishi.drmdtp.asia/blog/5320622.sHtMl

原标题：golang 系统设计缓存 key 命名规范最佳实践
简介：golang errors.Is errors.As 错误判断，判断是否为指定错误类型，提取自定义错误信息，错误处理进阶。
 | 原文链接：http://zhishi.drmdtp.asia/blog/7575910.sHtMl

原标题：golang 系统设计故障定位排查通用步骤方法论
简介：golang runtime.Gosched 主动让出调度，长计算循环主动 Gosched，让出调度权，防止其他协程饥饿。
 | 原文链接：http://zhishi.drmdtp.asia/blog/9101439.sHtMl

原标题：调优方案：Nginx性能参数调优高并发配置
简介：golang aes 对称加密解密示例，AES 对称加密解密实现，业务敏感数据加密存储传输。
 | 原文链接：http://zhishi.drmdtp.asia/blog/7591825.sHtMl

原标题：golang redis 发布订阅简单示例
简介：golang aes cbc gcm 模式加密对比，AES‑CBC AES‑GCM 模式加密解密，理解两种模式差异选型。
 | 原文链接：http://zhishi.drmdtp.asia/blog/5732725.sHtMl

原标题：图片上传预览格式大小处理
简介：golang aes 对称加密解密示例，AES 对称加密解密实现，业务敏感数据加密存储传输。
 | 原文链接：http://zhishi.drmdtp.asia/blog/3032843.sHtMl

原标题：实战：对象存储断点续传下载实践
简介：OpenAPI 自动接口文档生成，集成 OpenAPI 工具，自动扫描代码生成接口文档，减少文档维护成本。
 | 原文链接：http://zhishi.drmdtp.asia/blog/1697045.sHtMl

原标题：服务启动依赖顺序配置正确
简介：golang go‑zero 缓存自动击穿防护，go‑zero 缓存组件自带缓存击穿防护，减少缓存层故障。
 | 原文链接：http://zhishi.drmdtp.asia/blog/7442385.sHtMl

原标题：golang 系统设计 sql 注入 xss 防护实践
简介：Redis 内存淘汰策略数据防丢失，合理配置 Redis 内存淘汰策略，防止内存满后误删除业务重要数据。
 | 原文链接：http://zhishi.drmdtp.asia/blog/0993479.sHtMl

原标题：开发记录：分布式锁超时业务安全处理实践
简介：golang go 整洁架构代码组织实践，整洁架构依赖向内，解耦业务逻辑与外部基础设施。
 | 原文链接：http://zhishi.drmdtp.asia/blog/4942517.sHtMl

原标题：golang redis 过期 key 监听业务
简介：文件读写与异常捕获代码示例，演示文件读取写入操作，增加异常捕获逻辑，规避文件不存在、权限不足导致崩溃。
 | 原文链接：http://zhishi.drmdtp.asia/blog/4381316.sHtMl

原标题：新手向：看懂项目README的正确阅读姿势
简介：ORM 隐式慢查询问题规避，识别 ORM 框架隐式查询，避免循环查询数据库，减少不必要慢 SQL 产生。
 | 原文链接：http://zhishi.drmdtp.asia/blog/3746547.sHtMl

原标题：快速上手简易网关转发逻辑模拟
简介：golang go‑zero 配置中心热更新，go‑zero 对接 etcd 配置中心，配置热更新无需重启服务。
 | 原文链接：http://zhishi.drmdtp.asia/blog/5388057.sHtMl

原标题：golang 系统设计开源项目 release 发布流程
简介：CDN 缓存刷新获取最新静态资源，调用 CDN 刷新接口，清除节点旧缓存，用户访问到更新后的静态文件。
 | 原文链接：http://zhishi.drmdtp.asia/blog/5553815.sHtMl

原标题：golang 系统设计 csrf 接口防护实现
简介：HTTPS 证书过期更新操作，检测 HTTPS 证书到期，更新证书文件，恢复 HTTPS 服务正常访问。
 | 原文链接：http://zhishi.drmdtp.asia/blog/2133856.sHtMl

原标题：实践：分布式事务本地模拟验证实践
简介：后端分页查询逻辑代码实现，编写后端分页接口，处理页码、每页条数参数，优化大数据量查询返回结果。
 | 原文链接：http://zhishi.drmdtp.asia/blog/3729425.sHtMl

原标题：实战：Nginx配置静态站点、反向代理、负载均衡
简介：nodejs 定时任务生产环境避坑，Node 定时任务线上踩坑汇总，集群重复执行、任务阻塞等问题解决方案。
 | 原文链接：http://zhishi.drmdtp.asia/blog/9339766.sHtMl

原标题：RPC 接口字段增减兼容处理
简介：开源源码阅读拆解学习思路，分享阅读大型开源项目方法，从入口文件逐层拆解模块，降低源码学习门槛。
 | 原文链接：http://zhishi.drmdtp.asia/blog/7518488.sHtMl

原标题：golang docker 容器资源限制设置
简介：golang 探测文件真实内容类型，读取文件头部字节判断真实文件格式，规避后缀伪造。
 | 原文链接：http://zhishi.drmdtp.asia/blog/8061165.sHtMl

原标题：golang mysql 行锁表锁场景区分
简介：nestjs 拦截器过滤器管道实战，实操 Nest 拦截器、异常过滤器、管道校验，处理请求与响应统一逻辑。
 | 原文链接：http://zhishi.drmdtp.asia/blog/7508729.sHtMl

原标题：golang 系统设计开源项目维护简单经验分享
简介：后端大文件分片上传接口开发，开发后端分片上传接口，接收分片，合并分片完成大文件存储。
 | 原文链接：http://zhishi.drmdtp.asia/blog/6778384.sHtMl

原标题：性能笔记：TCP参数内核调优服务高并发场景
简介：golang delve 远程调试 go 线上程序，delve 远程调试，线上环境附加进程调试排查线上 bug。
 | 原文链接：http://zhishi.drmdtp.asia/blog/2313286.sHtMl

原标题：实战：GraphQL服务搭建与CRUD实操
简介：golang go 整洁架构代码组织实践，整洁架构依赖向内，解耦业务逻辑与外部基础设施。
 | 原文链接：http://zhishi.drmdtp.asia/blog/3134314.sHtMl

原标题：性能复盘：内存泄漏定位，内存持续上涨优化
简介：golang go 爬虫 robots 协议遵守，解析 robots.txt 规则，控制爬虫抓取范围，合规采集网页数据。
 | 原文链接：http://zhishi.drmdtp.asia/blog/4402106.sHtMl

原标题：实践：实现Redis分布式锁完整可运行代码
简介：golang context.Background 与 TODO 区别，Background 主流程根上下文，TODO 不确定用哪个上下文时使用。
 | 原文链接：http://zhishi.drmdtp.asia/blog/4476722.sHtMl

原标题：踩坑记录：浮点精度错误造成业务计算错误
简介：图片上传预览格式大小处理，实现图片上传接口，校验文件格式、大小，完成上传后预览处理。
 | 原文链接：http://zhishi.drmdtp.asia/blog/5864084.sHtMl

三、实战开发｜Practice
原标题：GraphQL 接口查询优化实操
简介：浏览器缓存强制刷新方案，设置 HTTP 缓存头，处理浏览器缓存旧静态资源，让用户加载更新后的页面。
 | 原文链接：http://zhishi.drmdtp.asia/blog/3154093.sHtMl

原标题：坑点：缓存穿透，大量无效请求打穿数据库
简介：express 中间件开发业务实践，开发 Express 自定义中间件，拦截请求，实现鉴权、日志记录等通用逻辑。
 | 原文链接：http://zhishi.drmdtp.asia/blog/8276610.sHtMl

原标题：golang 系统设计缓存预热缓存降级实现
简介：golang redis list 队列简易消息队列，利用 Redis List 实现简易队列，完成任务入队消费基础能力。
 | 原文链接：http://zhishi.drmdtp.asia/blog/6172518.sHtMl

原标题：网关集成鉴权限流日志一体化
简介：golang time.After 内存泄漏场景，for 循环使用 time.After 会创建大量 timer，造成内存泄漏。
 | 原文链接：http://zhishi.drmdtp.asia/blog/3162246.sHtMl

原标题：开发记录：实现完整用户登录鉴权业务模块
简介：golang go 项目 CI github actions 配置，github actions 实现 go 项目 ci，自动测试、代码检查、编译打包镜像。
 | 原文链接：http://zhishi.drmdtp.asia/blog/0997899.sHtMl

原标题：golang 系统设计缓存空值防止缓存穿透实现
简介：golang math 包常用数学函数，绝对值取整平方根三角函数，业务数学计算工具。
 | 原文链接：http://zhishi.drmdtp.asia/blog/8909354.sHtMl

原标题：优化实践：批量操作性能优化，减少数据库IO
简介：golang atomic 原子操作整数，atomic 加减比较交换，无锁更新整型变量，简单计数器场景。
 | 原文链接：http://zhishi.drmdtp.asia/blog/3211009.sHtMl

原标题：新手教程：如何给开源项目提交第一个PR
简介：axios 二次封装请求拦截处理，对 axios 做二次封装，统一请求拦截响应拦截，处理错误、token 自动刷新。
 | 原文链接：http://zhishi.drmdtp.asia/blog/1176640.sHtMl

原标题：实战：Redis集群本地搭建与功能验证
简介：无用对象回收抑制内存上涨，优化对象生命周期，及时释放不再使用对象，抑制内存持续不断增长。
 | 原文链接：http://zhishi.drmdtp.asia/blog/2422656.sHtMl

原标题：部署复盘：服务启动顺序依赖处理方案
简介：图片上传预览格式大小处理，实现图片上传接口，校验文件格式、大小，完成上传后预览处理。
 | 原文链接：http://zhishi.drmdtp.asia/blog/1507318.sHtMl

原标题：实践：API接口文档自动导出离线文档实践
简介：golang 数据库慢查询监控实现，Go 封装 SQL 执行监控，记录慢 SQL，上报日志，发现数据库性能问题。
 | 原文链接：http://zhishi.drmdtp.asia/blog/3454467.sHtMl

原标题：golang mysql limit 大分页优化
简介：golang go 随机数安全与非安全，math/rand 伪随机与 crypto/rand 密码学安全随机，区分业务场景。
 | 原文链接：http://zhishi.drmdtp.asia/blog/6432673.sHtMl

原标题：golang github actions 完整工作流示例
简介：golang html 模板渲染简单示例，Go HTML 模板渲染，服务端渲染页面，填充数据输出 HTML 页面。
 | 原文链接：http://zhishi.drmdtp.asia/blog/6497455.sHtMl

原标题：架构复盘：系统扩容缩容架构无状态优先原则
简介：后端大文件分片上传接口开发，开发后端分片上传接口，接收分片，合并分片完成大文件存储。
 | 原文链接：http://zhishi.drmdtp.asia/blog/8294687.sHtMl

原标题：项目实践：实现统一接口返回封装与全局异常处理
简介：golang go 程序敏感信息禁止打印日志，密钥密码禁止输出日志，防止敏感信息日志泄露。
 | 原文链接：http://zhishi.drmdtp.asia/blog/3565611.sHtMl

原标题：golang 系统设计限流算法原理代码实现
简介：golang etcd key 监听变更 watch 机制，watch 监听 etcd 键变化，配置变更实时感知，实现配置热更新。
 | 原文链接：http://zhishi.drmdtp.asia/blog/8089199.sHtMl

原标题：golang 系统设计延迟消息实现几种方案对比
简介：golang 工具函数库封装思路，Go 通用工具库封装思路，错误处理、类型转换，业务项目复用工具代码。
 | 原文链接：http://zhishi.drmdtp.asia/blog/8266547.sHtMl

原标题：快速上手简单性能监控指标查看
简介：golang os.Signal 信号监听完整示例，signal.Notify 监听信号，缓冲 channel 防止信号丢失。
 | 原文链接：http://zhishi.drmdtp.asia/blog/7232541.sHtMl

原标题：踩坑记录：乐观锁版本号处理不当更新失败
简介：golang slice 切片底层原理与坑点，切片扩容、截取、底层数组共享，规避切片修改互相影响数据。
 | 原文链接：http://zhishi.drmdtp.asia/blog/4416788.sHtMl

原标题：前端 pdf 预览渲染方案对比
简介：golang redis 过期键监听回调，监听 key 过期事件，过期触发业务逻辑，实现过期自动处理业务场景。
 | 原文链接：http://zhishi.drmdtp.asia/blog/1175758.sHtMl

原标题：golang 系统设计缓存预热脚本编写实操
简介：golang 字符串处理常用技巧汇总，字符串拼接、分割、替换、类型转换实操，规避字符串高频错误。
 | 原文链接：http://zhishi.drmdtp.asia/blog/0745648.sHtMl

原标题：分布式 ID 生成器高并发实现
简介：文件编码统一随机乱码修复，统一项目全部文件读写编码，消除随机中文乱码，保证文本处理稳定。
 | 原文链接：http://zhishi.drmdtp.asia/blog/2006731.sHtMl

原标题：语义化版本依赖管理防错乱
简介：golang 容器时区设置镜像构建处理，镜像内部设置正确时区，解决容器时间与宿主机不一致。
 | 原文链接：http://zhishi.drmdtp.asia/blog/3849109.sHtMl

原标题：golang redis hyperloglog 基数统计
简介：golang 布隆过滤器实现去重，Go 实现布隆过滤器，海量数据去重，节省内存开销，提升判断效率。
 | 原文链接：http://zhishi.drmdtp.asia/blog/9729887.sHtMl

原标题：golang 系统设计分布式任务调度
简介：golang go cover 覆盖率报告生成，go test‑cover 生成测试覆盖率，html 可视化查看未覆盖代码行。
 | 原文链接：http://zhishi.drmdtp.asia/blog/7870518.sHtMl

原标题：golang 系统设计回调重试幂等完整处理
简介：golang context.WithTimeout 超时上下文，WithTimeout 设置超时时间，超时自动 cancel 释放协程。
 | 原文链接：http://zhishi.drmdtp.asia/blog/8571970.sHtMl

原标题：排错：静态资源404，打包路径配置错误
简介：Docker Compose 一键搭建本地栈，使用 Compose 编排多个容器，一键拉起全套开发依赖服务。
 | 原文链接：http://zhishi.drmdtp.asia/blog/8856407.sHtMl

原标题：golang 系统设计网关路由规则动态配置实现
简介：golang json 自定义 MarshalJSON UnmarshalJSON，自定义 json 序列化反序列化逻辑，处理特殊格式字段。
 | 原文链接：http://zhishi.drmdtp.asia/blog/3198136.sHtMl

原标题：安全笔记：依赖包漏洞检测供应链安全
简介：golang json number 数字不转 float64，使用 json.Number 保留原始数字字符串，防止大数字精度丢失。
 | 原文链接：http://zhishi.drmdtp.asia/blog/7196611.sHtMl

原标题：ORM 框架数据库增删改查实操
简介：SSH 密钥配置 GitHub 免密登录，分步生成配置 SSH 密钥，实现 GitHub 免密推送拉取，免去重复输入账号密码的麻烦。
 | 原文链接：http://zhishi.drmdtp.asia/blog/8011421.sHtMl

原标题：golang 系统设计 webhook 回调处理架构
简介：golang mysql 慢查询日志程序采集解析，程序读取解析 mysql 慢查询日志，统计慢 SQL 做监控告警。
 | 原文链接：http://zhishi.drmdtp.asia/blog/0032358.sHtMl

原标题：golang github actions 缓存依赖提速
简介：Nginx 反向代理路由配置实战，配置 Nginx 反向代理，实现请求转发、路由分发，掌握 Nginx 基础配置能力。
 | 原文链接：http://zhishi.drmdtp.asia/blog/3623644.sHtMl

原标题：入门实践：项目配置文件多环境管理方案
简介：DNS TTL 配置域名切换生效，调整 DNS 解析 TTL，缩短缓存时间，域名变更后可以快速全网生效。
 | 原文链接：http://zhishi.drmdtp.asia/blog/6538174.sHtMl

原标题：TCP 心跳检测清理僵死连接
简介：golang multipart 表单文件上传解析，服务端解析 multipart 表单，获取上传文件与表单字段。
 | 原文链接：http://zhishi.drmdtp.asia/blog/1523814.sHtMl

原标题：踩坑记录：文件描述符不足，上传功能随机失败
简介：golang go 爬虫异步并发抓取，协程池控制并发抓取网页，多协程采集，提升爬虫采集速度。
 | 原文链接：http://zhishi.drmdtp.asia/blog/4459319.sHtMl

原标题：golang 系统设计 traceId 全链路透传完整方案
简介：系统文件描述符上限调大，调高操作系统文件描述符上限，解决高并发场景打开文件报错。
 | 原文链接：http://zhishi.drmdtp.asia/blog/1846239.sHtMl

原标题：架构笔记：业务系统反模式架构踩坑总结
简介：golang go 模板缓存预编译模板，预编译 html 模板，程序启动加载，避免每次请求解析模板损耗性能。
 | 原文链接：http://zhishi.drmdtp.asia/blog/4546867.sHtMl

原标题：定时任务重复执行分布式锁
简介：golang strconv 字符串类型转换，字符串转数字布尔，处理转换失败 error，避免 panic。
 | 原文链接：http://zhishi.drmdtp.asia/blog/2059411.sHtMl

原标题：golang 系统设计故障演练简单落地思路方法论
简介：数据库 utf8mb4 支持 emoji 存储，数据库字段设置 utf8mb4 字符集，完整支持 emoji 表情存储入库。
 | 原文链接：http://zhishi.drmdtp.asia/blog/6165796.sHtMl

原标题：开发记录：文件锁实现多进程互斥实践
简介：缓存过期策略优化防业务故障，合理设置缓存过期策略，规避集中过期，减少缓存失效带来业务抖动。
 | 原文链接：http://zhishi.drmdtp.asia/blog/5984353.sHtMl

四、架构设计｜Architecture
原标题：golang 系统设计字段命名类型选择最佳实践
简介：跨域偶现失败配置修复，解决跨域问题时而复现时而正常，定位配置漏配、请求头异常等隐性问题。
 | 原文链接：http://zhishi.drmdtp.asia/blog/6765465.sHtMl

原标题：golang 系统设计契约测试接口兼容性保障思路
简介：golang 高并发下锁优化减少竞争，减小锁粒度，读写锁替换互斥锁，无锁编程降低锁竞争开销。
 | 原文链接：http://zhishi.drmdtp.asia/blog/2543032.sHtMl

原标题：布隆过滤器误判问题修正
简介：nodejs 集成测试业务流程编写，编写 Node 集成测试，调用真实接口，验证完整业务链路执行结果。
 | 原文链接：http://zhishi.drmdtp.asia/blog/9065602.sHtMl

原标题：golang 系统设计混沌测试故障注入简单示例
简介：golang gin 框架接口开发实战，Gin 框架搭建 HTTP 服务，开发增删改查接口，快速完成后端接口开发。
 | 原文链接：http://zhishi.drmdtp.asia/blog/3581376.sHtMl

原标题：golang redis 事务 multi exec 使用
简介：golang 分布式事务 seata go 客户端，seata‑go 实现分布式事务，保证跨库业务数据最终一致性。
 | 原文链接：http://zhishi.drmdtp.asia/blog/1845309.sHtMl

原标题：golang mysql 慢查询日志开启分析
简介：golang dns 自定义解析器实现，自定义 dns 解析，指定 dns 服务器，控制域名解析逻辑，适配内网环境。
 | 原文链接：http://zhishi.drmdtp.asia/blog/2972953.sHtMl

原标题：优化实践：LRU本地缓存优化热点访问性能
简介：ORM 隐式慢查询问题规避，识别 ORM 框架隐式查询，避免循环查询数据库，减少不必要慢 SQL 产生。
 | 原文链接：http://zhishi.drmdtp.asia/blog/8840803.sHtMl

原标题：ORM 隐式慢查询问题规避
简介：服务健康检查监控接口开发，开发健康检查接口，反馈服务运行状态，供编排工具监控服务存活状态。
 | 原文链接：http://zhishi.drmdtp.asia/blog/1204398.sHtMl

原标题：golang 系统设计 rest 分页排序过滤参数规范
简介：golang json 解析未知动态 json 结构，解析到 map [string] any 处理未知 json，动态读取字段。
 | 原文链接：http://zhishi.drmdtp.asia/blog/3370835.sHtMl

原标题：版本升级服务启动失败处理
简介：golang golangci‑lint 静态代码检查配置，golangci‑lint 静态检查，代码规范检测，提前发现代码隐患。
 | 原文链接：http://zhishi.drmdtp.asia/blog/4955027.sHtMl

原标题：golang go test 覆盖率统计实操
简介：浏览器缓存强制刷新方案，设置 HTTP 缓存头，处理浏览器缓存旧静态资源，让用户加载更新后的页面。
 | 原文链接：http://zhishi.drmdtp.asia/blog/4325899.sHtMl

原标题：golang 系统设计监控大盘故障快速定位思路
简介：golang channel 作为函数参数方向，声明 channel 入参方向，只读 channel 只写 channel 提升代码约束。
 | 原文链接：http://zhishi.drmdtp.asia/blog/2763613.sHtMl

原标题：Debug：请求头过大Nginx拒绝连接报错
简介：golang 服务限流熔断降级监控完整实践，微服务防护体系，限流熔断降级指标监控告警整套落地。
 | 原文链接：http://zhishi.drmdtp.asia/blog/2704873.sHtMl

原标题：前端组件库按需加载性能优化
简介：golang tcp keepalive 参数程序配置，go 程序设置 tcp keepalive，操作系统 tcp 保活参数，清理僵死连接。
 | 原文链接：http://zhishi.drmdtp.asia/blog/9821429.sHtMl

原标题：大事务拆分回滚日志暴涨解决
简介：golang 协程数量监控统计方案，统计运行中 goroutine 数量，监控协程泄露，协程数量异常及时告警。
 | 原文链接：http://zhishi.drmdtp.asia/blog/6747727.sHtMl

原标题：golang 系统设计分库分表 id 全局生成策略
简介：golang context.WithTimeout 超时上下文，WithTimeout 设置超时时间，超时自动 cancel 释放协程。
 | 原文链接：http://zhishi.drmdtp.asia/blog/6100630.sHtMl

原标题：安全笔记：JWT安全风险，签名泄露过期控制
简介：日志驱动异常日志不输出修复，排查日志驱动配置，修复日志写入配置，恢复程序正常日志输出。
 | 原文链接：http://zhishi.drmdtp.asia/blog/7233706.sHtMl

原标题：业务接口幂等完整落地案例
简介：golang excel 简单读写操作示例，Go 实现 Excel 简单读写，业务数据导出 Excel 报表。
 | 原文链接：http://zhishi.drmdtp.asia/blog/5645894.sHtMl

?
