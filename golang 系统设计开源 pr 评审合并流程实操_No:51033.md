最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计开源 pr 评审合并流程实操
简介：任务执行锁防止并发重复调度，增加任务执行锁，多实例环境，防止同一个定时任务并发多次运行。
 | 原文链接：http://book.1kjp1k.asia/blog/877471.Doc

原标题：代码格式化工具团队统一风格
简介：业务错误码体系设计方案，设计项目统一错误码，区分不同业务异常，标准化错误返回，便于前端识别处理。
 | 原文链接：http://book.1kjp1k.asia/blog/190470.Doc

原标题：golang 系统设计消息 key 选择保证顺序性方案
简介：golang go 并发模式 fan‑out fan‑in，fanout 分发任务 fanin 汇总结果，多协程并发处理任务。
 | 原文链接：http://book.1kjp1k.asia/blog/183621.Doc

原标题：golang 单元测试 table‑driven
简介：golang cgroup 读取容器资源限制，go 程序读取 cgroup，获取容器 cpu 内存限额，适配容器环境。
 | 原文链接：http://book.1kjp1k.asia/blog/156291.Doc

原标题：golang mysql 读写分离简单实现
简介：消息队列重复消费业务处理，实现消息消费幂等，处理重复投递消息，保证多次消费业务结果一致。
 | 原文链接：http://book.1kjp1k.asia/blog/976103.Doc

原标题：golang 系统设计数据库连接池调优实践
简介：依赖版本冲突兼容修复方案，定位依赖版本冲突根源，通过版本约束、替换包，解决版本不兼容运行报错。
 | 原文链接：http://book.1kjp1k.asia/blog/229394.Doc

原标题：DevOps：容器健康探针livenessreadiness配置
简介：echarts 大数据渲染性能调优，大数据量 ECharts 图表调优，数据采样、分片渲染，解决图表卡顿。
 | 原文链接：http://book.1kjp1k.asia/blog/561047.Doc

原标题：安全实践：最小权限原则数据库账号管控
简介：golang 模糊测试 go fuzz 基础编写，Fuzz 测试函数，自动生成随机输入，发现代码崩溃 panic。
 | 原文链接：http://book.1kjp1k.asia/blog/250761.Doc

原标题：实战：对象存储断点续传下载实践
简介：golang go mod replace 本地模块替换，replace 替换模块为本地目录，修改第三方库本地调试。
 | 原文链接：http://book.1kjp1k.asia/blog/853259.Doc

原标题：开发复盘：分布式会话共享多种方案实践
简介：golang go test 单元测试命令参数详解，gotest 参数覆盖率，指定测试用例，跳过测试，单元测试命令实操。
 | 原文链接：http://book.1kjp1k.asia/blog/971422.Doc

原标题：golang 系统设计 mq 消息重复消费处理
简介：并发数据覆盖加锁安全处理，多线程并发修改同一数据，增加锁机制，防止并发覆盖丢失更新数据。
 | 原文链接：http://book.1kjp1k.asia/blog/971843.Doc

原标题：架构复盘：多实例部署业务状态无状态改造
简介：golang go mod 私有 git 仓库配置，配置 go mod 拉取私有仓库代码，处理私有模块依赖拉取问题。
 | 原文链接：http://book.1kjp1k.asia/blog/634407.Doc

原标题：看懂报错日志快速定位问题
简介：golang 雪花算法 workId 自动获取，自动获取机器 workId，不用手动配置，简化分布式 id 部署。
 | 原文链接：http://book.1kjp1k.asia/blog/045468.Doc

原标题：golang mysql 长连接短连接对比
简介：golang ioutil 已废弃替换方案，ioutil 废弃之后替换为 os io 包函数，更新旧项目代码。
 | 原文链接：http://book.1kjp1k.asia/blog/227175.Doc

原标题：多线程线程安全脏数据规避
简介：golang atomic.Value 存储任意类型数据，atomic.Value 安全存储读取任意类型，配置热更新常用。
 | 原文链接：http://book.1kjp1k.asia/blog/355334.Doc

原标题：分布式锁失效问题排查修复
简介：Mock 接口服务快速搭建实操，搭建模拟后端接口，自定义返回数据、延迟响应，前端开发阶段无需依赖真实后端服务。
 | 原文链接：http://book.1kjp1k.asia/blog/189140.Doc

原标题：避坑：定时任务重复执行带来业务脏数据
简介：前端图片懒加载性能优化，实现图片懒加载，页面可视区域才加载图片，减少页面初始网络请求。
 | 原文链接：http://book.1kjp1k.asia/blog/486104.Doc

原标题：踩坑：重试逻辑未做幂等，重复生成业务数据
简介：golang 消息死信处理业务逻辑，Go 实现死信队列逻辑，消费失败消息转入死信，不阻塞正常消息队列。
 | 原文链接：http://book.1kjp1k.asia/blog/101771.Doc

原标题：golang redis zset 延时队列实现
简介：不必要字符转义关闭业务异常，关闭多余自动转义逻辑，防止业务数据被错误转义，破坏原始数据。
 | 原文链接：http://book.1kjp1k.asia/blog/505014.Doc

原标题：代码模块化组件化拆分思路
简介：golang go 优雅处理信号丢失场景，处理信号丢失、信号被忽略，保障程序可以正常接收终止信号。
 | 原文链接：http://book.1kjp1k.asia/blog/512737.Doc

原标题：优化实践：业务定时任务错开高峰避免资源争抢
简介：程序信号中断退出处理逻辑，捕获系统中断信号，执行资源释放、关闭连接，实现程序优雅退出。
 | 原文链接：http://book.1kjp1k.asia/blog/152857.Doc

原标题：Dockerfile 编写容器打包实战
简介：死信队列处理消息阻塞业务，配置死信队列，处理消费失败消息，避免失败消息阻塞整个队列业务。
 | 原文链接：http://book.1kjp1k.asia/blog/274144.Doc

原标题：快速上手简单的限流逻辑模拟实现
简介：golang go cover 覆盖率报告生成，go test‑cover 生成测试覆盖率，html 可视化查看未覆盖代码行。
 | 原文链接：http://book.1kjp1k.asia/blog/855851.Doc

原标题：golang 系统设计日志级别业务使用原则梳理
简介：golang viper 多源配置管理实操，viper 读取配置文件环境变量命令行参数，多源配置优先级管理。
 | 原文链接：http://book.1kjp1k.asia/blog/641394.Doc

原标题：Troubleshoot：CPU调度频繁上下文切换性能下降
简介：多环境配置中心灵活切换方案，简易配置中心实现，支持多套环境配置，动态下发无需重启服务。
 | 原文链接：http://book.1kjp1k.asia/blog/460477.Doc

原标题：实战：gRPC服务编写客户端服务端完整demo
简介：golang http 服务并发连接数限制，自定义 listener 统计连接数量，限制最大并发连接数保护服务。
 | 原文链接：http://book.1kjp1k.asia/blog/594996.Doc

原标题：实战项目：实现简单缓存服务缓存穿透击穿防护
简介：死信队列处理消息阻塞业务，配置死信队列，处理消费失败消息，避免失败消息阻塞整个队列业务。
 | 原文链接：http://book.1kjp1k.asia/blog/483228.Doc

原标题：部署实践：Nginx反向代理传递真实客户端IP
简介：文件监控服务自动重启开发，监控项目文件变更，代码修改自动重启服务，提升本地开发调试效率。
 | 原文链接：http://book.1kjp1k.asia/blog/078744.Doc

原标题：异步异常捕获避免进程崩溃
简介：静态网页 HTML CSS 快速入门实战，通过简单页面案例讲解标签、样式布局，从零编写页面，理解网页基础渲染原理。
 | 原文链接：http://book.1kjp1k.asia/blog/676538.Doc

原标题：golang toml 配置文件解析教程
简介：内网 DNS 不稳定随机报错排查，定位内网 DNS 抖动问题，配置备选 DNS，解决偶现域名解析失败。
 | 原文链接：http://book.1kjp1k.asia/blog/086238.Doc

原标题：golang 系统设计消息堆积排查扩容完整步骤
简介：golang go 调度器 GMP 模型通俗讲解，拆解 GMP 模型，理解 goroutine M P 调度原理，看懂调度状态。
 | 原文链接：http://book.1kjp1k.asia/blog/427698.Doc

原标题：golang redis 事务 multi exec 使用
简介：主干开发团队代码合并策略，讲解主干开发模式，团队代码合并流程，适合高频迭代的团队协作模式。
 | 原文链接：http://book.1kjp1k.asia/blog/196591.Doc

原标题：golang 系统设计线上问题复现思路简单讲解
简介：golang time.After 内存泄漏场景，for 循环使用 time.After 会创建大量 timer，造成内存泄漏。
 | 原文链接：http://book.1kjp1k.asia/blog/716691.Doc

原标题：golang 系统设计缓存基准测试对比方案
简介：golang go‑zero 框架项目快速搭建，go‑zero 脚手架生成微服务项目，api rpc 服务快速开发。
 | 原文链接：http://book.1kjp1k.asia/blog/425919.Doc

原标题：golang prometheus histogram 指标
简介：golang go 容器 heap 堆实现优先队列，实现 heap 接口，构建优先队列，任务优先级调度。
 | 原文链接：http://book.1kjp1k.asia/blog/725400.Doc

原标题：业务接口幂等完整落地案例
简介：golang go sum 校验失败处理方案，go sum 校验不匹配，排查网络代理，清理缓存解决校验报错。
 | 原文链接：http://book.1kjp1k.asia/blog/459112.Doc

原标题：性能复盘：磁盘Swap大量使用系统卡顿优化
简介：配置外部化线上部署防错误，把配置从代码剥离，外部传入配置，修改配置不需要重新打包构建。
 | 原文链接：http://book.1kjp1k.asia/blog/234280.Doc

原标题：实战项目：数据导出Excel百万级大数据导出方案
简介：golang errors.Is errors.As 错误判断，判断是否为指定错误类型，提取自定义错误信息，错误处理进阶。
 | 原文链接：http://book.1kjp1k.asia/blog/212881.Doc

原标题：nodejs http 服务性能调优实战
简介：golang go mod graph 查看依赖关系，go mod graph 打印依赖树，定位间接依赖来源，解决版本冲突。
 | 原文链接：http://book.1kjp1k.asia/blog/267969.Doc

原标题：golang gin 路由分组权限管控
简介：golang go work 多模块本地开发，go work 多模块本地同时开发，本地模块互相引用，无需推送仓库。
 | 原文链接：http://book.1kjp1k.asia/blog/034096.Doc


二、踩坑排错｜Troubleshooting
原标题：golang 大文件 http 下载服务
简介：分布式 ID 全局唯一生成方案，讲解分布式 ID 生成思路，实现全局唯一 ID，满足分布式系统主键生成需求。
 | 原文链接：http://book.1kjp1k.asia/blog/616422.Doc

原标题：Troubleshoot：磁盘inode耗尽，无法新建文件
简介：golang 压缩 zip 文件生成解压，golang 实现 zip 压缩打包，解压 zip 归档文件，处理批量文件归档。
 | 原文链接：http://book.1kjp1k.asia/blog/889988.Doc

原标题：golang 单元测试 mock http 请求
简介：golang 自定义 pprof 扩展业务指标，扩展 pprof，输出业务自定义指标，结合性能数据分析业务状态。
 | 原文链接：http://book.1kjp1k.asia/blog/466887.Doc

原标题：安全笔记：依赖包漏洞检测供应链安全
简介：API 接口调试与异常处理实战，覆盖接口请求、参数组装、错误捕获，提供调试思路，高效定位接口返回异常问题。
 | 原文链接：http://book.1kjp1k.asia/blog/804633.Doc

原标题：设计思考：系统降级开关架构设计快速切流量
简介：服务器时钟同步任务错乱修复，配置服务器 NTP 时间同步，保证集群所有机器时间保持一致。
 | 原文链接：http://book.1kjp1k.asia/blog/571078.Doc

原标题：代理 HTTPS 证书访问异常处理
简介：golang go proxy 私有代理配置，配置 go proxy 私有代理，加速依赖下载，内网环境构建项目。
 | 原文链接：http://book.1kjp1k.asia/blog/019118.Doc

原标题：golang redis 客户端业务使用
简介：golang sftp 文件上传下载操作，sftp 协议远程文件上传下载，实现服务器之间文件传输功能。
 | 原文链接：http://book.1kjp1k.asia/blog/522966.Doc

原标题：golang 单元测试 mock http 请求
简介：golang 分布式追踪全链路日志打印，日志打印 traceId，各个服务日志可串联，排查跨服务调用问题。
 | 原文链接：http://book.1kjp1k.asia/blog/529114.Doc

原标题：快速上手简单性能监控指标查看
简介：开源项目构建失败排查步骤，梳理构建报错排查流程，从依赖、网络、权限、脚本多角度定位项目构建失败原因。
 | 原文链接：http://book.1kjp1k.asia/blog/635864.Doc

原标题：读懂开源项目 README 实用技巧
简介：文件句柄上限调整上传随机失败，调高系统文件句柄上限，解决高并发上传场景随机打开文件失败。
 | 原文链接：http://book.1kjp1k.asia/blog/494184.Doc

原标题：golang kafka 生产者参数调优
简介：golang 日志级别动态调整热更新，不用重启程序动态修改日志输出级别，线上调试排查问题十分方便。
 | 原文链接：http://book.1kjp1k.asia/blog/404685.Doc

原标题：golang rate‑limiter 限流组件
简介：golang 数据库 ORM 框架选型对比，gorm xorm sqlx 对比各 ORM 优缺点，根据业务场景选型。
 | 原文链接：http://book.1kjp1k.asia/blog/420592.Doc

原标题：golang 系统设计 grpc http2 多路复用讲解
简介：文件监控服务自动重启开发，监控项目文件变更，代码修改自动重启服务，提升本地开发调试效率。
 | 原文链接：http://book.1kjp1k.asia/blog/803023.Doc

原标题：入门实践：简易导出导入文件功能实现
简介：服务健康检查监控接口开发，开发健康检查接口，反馈服务运行状态，供编排工具监控服务存活状态。
 | 原文链接：http://book.1kjp1k.asia/blog/866628.Doc

原标题：golang 系统设计分布式任务调度
简介：golang 消息队列 kafka 消费开发，Go 开发 Kafka 消费程序，消费消息执行业务，理解 Kafka 消费逻辑。
 | 原文链接：http://book.1kjp1k.asia/blog/415604.Doc

原标题：实战：gRPC服务编写客户端服务端完整demo
简介：golang ip2regionIP 地址解析实战，集成 ip2region 库，根据 IP 解析归属地城市，实现 IP 地域解析。
 | 原文链接：http://book.1kjp1k.asia/blog/726217.Doc

原标题：golang 系统设计内部服务链路 trace 传递实现
简介：golang http 服务性能优化调参，调优 Go HTTP 服务参数，调整连接池，提升服务并发吞吐能力。
 | 原文链接：http://book.1kjp1k.asia/blog/558940.Doc

原标题：安全实践：防止重放攻击接口签名方案
简介：全局时间标准统一逻辑错乱修复，全服务统一使用同一时间标准，不要混用本地时间 UTC，修复时间逻辑 bug。
 | 原文链接：http://book.1kjp1k.asia/blog/528928.Doc

原标题：Debug：多线程共享可变变量产生脏数据
简介：配置外部化线上部署防错误，把配置从代码剥离，外部传入配置，修改配置不需要重新打包构建。
 | 原文链接：http://book.1kjp1k.asia/blog/055136.Doc

原标题：golang 系统设计告警风暴抑制方案实现
简介：golang html 模板渲染简单示例，Go HTML 模板渲染，服务端渲染页面，填充数据输出 HTML 页面。
 | 原文链接：http://book.1kjp1k.asia/blog/201667.Doc

原标题：golang gin 中间件执行顺序讲解
简介：golang tar gz 压缩解压处理，tar.gz 归档压缩解压，服务端日志备份、文件打包场景使用。
 | 原文链接：http://book.1kjp1k.asia/blog/443311.Doc

原标题：golang 系统设计数据库连接池调优实践
简介：前端大文件分片上传完整方案，前端分片切割大文件，配合后端分片接口，实现稳定大文件上传。
 | 原文链接：http://book.1kjp1k.asia/blog/374788.Doc

原标题：安全复盘：Nginx配置不当带来的安全风险
简介：golang httptest 模拟外部 http 服务，httptest.NewServer 模拟第三方 http 服务，单元测试 mock 外部接口。
 | 原文链接：http://book.1kjp1k.asia/blog/883586.Doc

原标题：内网 DNS 不稳定随机报错排查
简介：golang oss 签名 URL 临时访问，生成 oss 临时签名 url，限时访问私有文件，保障文件访问安全可控。
 | 原文链接：http://book.1kjp1k.asia/blog/629255.Doc

原标题：golang 系统设计消息队列解耦削峰
简介：golang 项目 go mod 依赖管理，Go Mod 管理项目依赖，下载、升级、清理依赖，解决依赖版本管理。
 | 原文链接：http://book.1kjp1k.asia/blog/723686.Doc

原标题：Security：限流防爬虫防恶意攻击防护体系
简介：大事务拆分防止连接池耗尽，将执行时间很长的大事务拆分为小事务，减少事务占用连接时长。
 | 原文链接：http://book.1kjp1k.asia/blog/292025.Doc

原标题：Practice：实现请求ID透传全链路日志实践
简介：golang 限流器熔断降级组合使用，限流熔断降级组合架构，流量防护完整方案，保障服务稳定性。
 | 原文链接：http://book.1kjp1k.asia/blog/678156.Doc

原标题：golang 系统设计定时任务执行超时中断防护
简介：golang go‑zero 配置中心热更新，go‑zero 对接 etcd 配置中心，配置热更新无需重启服务。
 | 原文链接：http://book.1kjp1k.asia/blog/948798.Doc

原标题：golang redis 缓存更新策略讲解
简介：分布式任务调度集群原型开发，开发简易分布式调度原型，集群多节点运行，保证任务只执行一次。
 | 原文链接：http://book.1kjp1k.asia/blog/824500.Doc

原标题：项目实践：搭建个人API网关最小实现版本
简介：golang tcp 连接泄露排查定位，netstat 查看连接状态，找出未正常关闭连接，定位连接泄漏代码。
 | 原文链接：http://book.1kjp1k.asia/blog/208439.Doc

原标题：golang 配置热更新不重启服务
简介：新手参与开源社区贡献指南，介绍开源社区基础规则，讲解阅读 issue、提交 PR 流程，指导开发者参与开源贡献。
 | 原文链接：http://book.1kjp1k.asia/blog/926247.Doc

原标题：Issue：本地数据库与线上数据库排序规则差异
简介：golang rate 令牌桶限流器源码理解，拆解令牌桶限流核心逻辑，理解令牌生成消耗，掌握限流底层原理。
 | 原文链接：http://book.1kjp1k.asia/blog/272628.Doc

原标题：golang 系统设计 tcp 三次握手四次挥手梳理
简介：分布式 ID 全局唯一生成方案，讲解分布式 ID 生成思路，实现全局唯一 ID，满足分布式系统主键生成需求。
 | 原文链接：http://book.1kjp1k.asia/blog/716311.Doc

原标题：golang 参数校验业务接口处理
简介：golang grpc protobuf 开发实操，Go gRPC 开发，编写 Protobuf 定义，服务端客户端完整示例。
 | 原文链接：http://book.1kjp1k.asia/blog/263788.Doc

原标题：项目实践：Docker镜像安全扫描本地实操
简介：golang errors.Is errors.As 错误判断，判断是否为指定错误类型，提取自定义错误信息，错误处理进阶。
 | 原文链接：http://book.1kjp1k.asia/blog/520025.Doc

原标题：前端错误监控上报系统搭建
简介：golang go 第三方库选型评估要点，评估库活跃度维护情况、性能、依赖数量，选择合适开源库。
 | 原文链接：http://book.1kjp1k.asia/blog/939166.Doc

原标题：golang prometheus counter gauge 使用
简介：golang 时间时区处理避坑指南，Go 时间时区常见坑，时区转换，时间比较，规避时间逻辑错误。
 | 原文链接：http://book.1kjp1k.asia/blog/862937.Doc

原标题：golang prometheus 指标暴露实现
简介：golang go mod why 查询依赖引入原因，go mod why 查询为什么引入某个包，理清依赖来源。
 | 原文链接：http://book.1kjp1k.asia/blog/193918.Doc

原标题：golang makefile 自动化构建脚本
简介：golang 负载均衡轮询加权轮询实现，手写负载均衡算法，轮询、加权轮询分发请求到后端节点。
 | 原文链接：http://book.1kjp1k.asia/blog/675272.Doc

原标题：golang 系统设计网络 io 模型 epoll 原理讲解
简介：golang 速率限制令牌桶实现，Go 实现令牌桶限流算法，可复用限流器，控制业务调用速率。
 | 原文链接：http://book.1kjp1k.asia/blog/553384.Doc

三、实战开发｜Practice
原标题：golang 系统设计日志系统架构思路
简介：线上接口超时故障排查思路，从网络、数据库、代码逻辑逐层排查接口超时，定位慢请求根因。
 | 原文链接：http://book.1kjp1k.asia/blog/525730.Doc

原标题：golang 系统设计传输加密 tls 配置要点
简介：进程线程并发基础概念讲解，区分进程与线程，讲解调度逻辑，理解并发执行原理，为高并发业务开发打基础。
 | 原文链接：http://book.1kjp1k.asia/blog/190351.Doc

原标题：架构笔记：海量消息堆积架构处理能力设计
简介：golang 自定义 pprof 扩展业务指标，扩展 pprof，输出业务自定义指标，结合性能数据分析业务状态。
 | 原文链接：http://book.1kjp1k.asia/blog/120571.Doc

原标题：OOMKilled 容器被杀完整排查
简介：配置与镜像分离防止信息泄露，业务配置不打包进镜像，外部挂载配置，避免密钥配置随镜像泄露。
 | 原文链接：http://book.1kjp1k.asia/blog/421499.Doc

原标题：性能笔记：连接池参数调优数据库RPC连接池
简介：golang prometheus 指标埋点开发，业务埋点计数器、仪表盘、直方图，对接 prometheus 采集监控指标。
 | 原文链接：http://book.1kjp1k.asia/blog/819764.Doc

原标题：golang 系统设计用户签到统计方案
简介：git rebase 整理提交历史实操，使用 rebase 整理杂乱提交记录，将多条提交合并，保持 git 提交历史干净线性。
 | 原文链接：http://book.1kjp1k.asia/blog/044356.Doc

原标题：golang 分布式 ID 雪花算法实现
简介：golang go ring 环形容器循环队列，ring 环形链表实现循环队列，环形缓冲区业务场景。
 | 原文链接：http://book.1kjp1k.asia/blog/151424.Doc

原标题：Hands‑on：简易链路追踪原型开发实践
简介：golang go 锁竞争导致 CPU 飙升，识别锁竞争场景，减少锁粒度，优化并发逻辑降低 CPU 开销。
 | 原文链接：http://book.1kjp1k.asia/blog/539659.Doc

原标题：golang 系统设计 webhook 回调处理架构
简介：golang 表格驱动测试完整示例，表格驱动多组输入输出，批量执行测试用例，减少重复代码。
 | 原文链接：http://book.1kjp1k.asia/blog/237679.Doc

原标题：golang 系统设计缓存一致性方案对比
简介：golang 定时任务 cron 使用指南，Go 使用 Cron 库实现定时任务，配置 corn 表达式调度业务任务。
 | 原文链接：http://book.1kjp1k.asia/blog/021587.Doc

原标题：golang 系统设计开源 issue 处理回复沟通技巧
简介：WebSocket 聊天室实时通讯开发，基于 WebSocket 搭建简易聊天室，实现多人消息广播实时聊天效果。
 | 原文链接：http://book.1kjp1k.asia/blog/089513.Doc

原标题：快速上手简单性能监控指标查看
简介：golang go 第三方库选型评估要点，评估库活跃度维护情况、性能、依赖数量，选择合适开源库。
 | 原文链接：http://book.1kjp1k.asia/blog/451103.Doc

原标题：golang 配置热更新不重启服务
简介：golang go‑zero 监控指标埋点，go‑zero 内置 metrics 监控，上报业务指标对接监控平台。
 | 原文链接：http://book.1kjp1k.asia/blog/906352.Doc

原标题：项目构建脚本编译打包解析
简介：前后端交互跨域问题完整处理，讲解跨域产生原理，列举多种解决方案，适配开发、生产不同环境的跨域处理。
 | 原文链接：http://book.1kjp1k.asia/blog/717435.Doc

原标题：踩坑：批量MQ消费失败直接无限重试消息爆炸
简介：golang gzip 压缩 http 响应，服务端开启 gzip 压缩，减小接口响应体积，降低网络传输耗时。
 | 原文链接：http://book.1kjp1k.asia/blog/152591.Doc

原标题：golang 熔断降级简易组件开发
简介：golang gitlab ci go 项目流水线编写，gitlab ci 流水线执行单元测试、静态检查、构建推送镜像。
 | 原文链接：http://book.1kjp1k.asia/blog/890540.Doc

原标题：Git 误提交撤销回退实操教程
简介：golang sqlx 原生 SQL 代码简化，sqlx 简化原生 SQL 结果映射结构体，兼顾性能与开发效率。
 | 原文链接：http://book.1kjp1k.asia/blog/266352.Doc

原标题：golang aes 对称加密解密示例
简介：全局时间标准统一逻辑错乱修复，全服务统一使用同一时间标准，不要混用本地时间 UTC，修复时间逻辑 bug。
 | 原文链接：http://book.1kjp1k.asia/blog/168394.Doc

原标题：golang 系统设计 debug 远程调试 go 程序实操
简介：golang 内存缓存简单实现方案，Go 实现进程内简易内存缓存，本地缓存热点数据，减少远程调用。
 | 原文链接：http://book.1kjp1k.asia/blog/018577.Doc

原标题：golang 大文件 http 下载服务
简介：K8s 镜像拉取网络故障修复，排查 K8s 集群镜像拉取网络问题，配置镜像源，恢复镜像正常拉取。
 | 原文链接：http://book.1kjp1k.asia/blog/658902.Doc

原标题：Practice：简易限流器分布式版本Redis实现
简介：golang go 项目安全检查漏洞扫描，扫描 go 项目依赖漏洞，代码安全审计，规避安全风险。
 | 原文链接：http://book.1kjp1k.asia/blog/301959.Doc

原标题：golang redis 过期策略内存淘汰
简介：分页逻辑错误数据漏查修复，修复分页查询逻辑漏洞，解决分页漏数据、重复返回数据等业务问题。
 | 原文链接：http://book.1kjp1k.asia/blog/489656.Doc

原标题：数据库索引重建提升查询速度
简介：golang fuzz corpus 语料库使用，fuzz 语料存储历史输入，回归测试，持续复现曾经触发 bug 输入。
 | 原文链接：http://book.1kjp1k.asia/blog/900102.Doc

原标题：golang 系统设计定时任务动态启停配置方案
简介：golang time.After 内存泄漏场景，for 循环使用 time.After 会创建大量 timer，造成内存泄漏。
 | 原文链接：http://book.1kjp1k.asia/blog/535582.Doc

原标题：开发复盘：大JSON解析分批处理避免内存溢出
简介：GitHub 项目提交推送完整流程讲解，从仓库初始化到提交推送远程仓库，梳理全流程细节，避开新手高频错误。
 | 原文链接：http://book.1kjp1k.asia/blog/547685.Doc

原标题：图片上传预览格式大小处理
简介：golang grpc protobuf 开发实操，Go gRPC 开发，编写 Protobuf 定义，服务端客户端完整示例。
 | 原文链接：http://book.1kjp1k.asia/blog/007613.Doc

原标题：golang 系统设计第三方接口 mock 单元测试
简介：内网 DNS 不稳定随机报错排查，定位内网 DNS 抖动问题，配置备选 DNS，解决偶现域名解析失败。
 | 原文链接：http://book.1kjp1k.asia/blog/827447.Doc

原标题：设计思考：业务埋点架构日志埋点设计原则
简介：golang 反向代理 http 服务开发，手写简易 http 反向代理，转发请求，修改请求头响应头。
 | 原文链接：http://book.1kjp1k.asia/blog/055607.Doc

原标题：架构笔记：OAuth2授权服务架构模式拆解
简介：golang docker compose 开发环境 go 服务，docker compose 编排 go 服务与中间件，本地一键拉起整套开发环境。
 | 原文链接：http://book.1kjp1k.asia/blog/879333.Doc

原标题：golang gin 静态资源访问配置
简介：golang socket 文件描述符继承重启，父进程传递 listener fd 给子进程，实现 go 程序零停机热重启。
 | 原文链接：http://book.1kjp1k.asia/blog/128810.Doc

原标题：踩坑：对象未释放，长时间运行内存持续上涨
简介：golang go yaml 解析自定义类型，yaml 自定义序列化，时间、特殊类型自定义解析逻辑。
 | 原文链接：http://book.1kjp1k.asia/blog/451727.Doc

原标题：vite 项目配置与构建提速技巧
简介：golang k8s secret 敏感配置加载，加载 k8s secret 存储密钥密码，敏感信息不存放配置文件。
 | 原文链接：http://book.1kjp1k.asia/blog/509069.Doc

原标题：踩坑：数据库连接未关闭，连接池泄露
简介：多规则数据脱敏组件开发，封装通用脱敏组件，支持多种脱敏规则，项目多处复用脱敏逻辑。
 | 原文链接：http://book.1kjp1k.asia/blog/266475.Doc

原标题：golang redis 计数器防超卖示例
简介：golang 静态文件服务搭建教程，Go 搭建静态文件服务，托管静态资源，实现文件直接对外访问。
 | 原文链接：http://book.1kjp1k.asia/blog/233063.Doc

原标题：排错：GitLFS大文件推送失败完整排障
简介：golang go 锁竞争导致 CPU 飙升，识别锁竞争场景，减少锁粒度，优化并发逻辑降低 CPU 开销。
 | 原文链接：http://book.1kjp1k.asia/blog/889309.Doc

原标题：Hands‑on：简易短消息模板渲染组件实践
简介：golang 多协程任务池并发控制，实现协程任务池，控制并发协程数量，防止无限制创建 goroutine。
 | 原文链接：http://book.1kjp1k.asia/blog/915694.Doc

原标题：Practice：模拟缓存雪崩缓存击穿验证防护策略
简介：golang 项目 makefile 脚本编写，编写 Makefile 脚本，封装编译、测试、构建命令，简化项目操作。
 | 原文链接：http://book.1kjp1k.asia/blog/240108.Doc

原标题：网络读取超时设置连接挂起防护
简介：跨平台 uniapp 多端开发实操，uniapp 开发一套代码，编译多端，梳理多端差异处理与适配技巧。
 | 原文链接：http://book.1kjp1k.asia/blog/065723.Doc

原标题：Docker 网络模式容器互通设置
简介：golang uuid 生成多种版本实现，生成 uuid v1 v4，生成唯一标识，业务用于单据编号场景。
 | 原文链接：http://book.1kjp1k.asia/blog/329903.Doc

原标题：Architecture：事件溯源架构模式适用业务场景
简介：golang 正则表达式 Go 实操案例，正则匹配提取替换，处理手机号邮箱校验，规避正则回溯 CPU 暴涨。
 | 原文链接：http://book.1kjp1k.asia/blog/200407.Doc

四、架构设计｜Architecture
原标题：golang kafka 死信队列业务落地
简介：golang go yaml 解析自定义类型，yaml 自定义序列化，时间、特殊类型自定义解析逻辑。
 | 原文链接：http://book.1kjp1k.asia/blog/588771.Doc

原标题：踩坑记录：时间戳精度不一致引发判断错误
简介：golang 进程信号捕获 SIGUSR 自定义信号，捕获用户自定义信号，实现线上不重启触发调试、日志切换。
 | 原文链接：http://book.1kjp1k.asia/blog/141294.Doc

原标题：golang base64 编码解码实操
简介：数据库索引重建提升查询速度，针对碎片化索引，重建数据库索引，恢复 SQL 查询执行性能。
 | 原文链接：http://book.1kjp1k.asia/blog/389927.Doc

原标题：架构笔记：冷热数据分离架构设计与迁移
简介：golang defer 闭包变量捕获坑，defer 捕获循环变量引用，变量被复写，理解闭包变量捕获规则。
 | 原文链接：http://book.1kjp1k.asia/blog/966784.Doc

原标题：架构笔记：业务系统反模式架构踩坑总结
简介：golang 系统 IO 阻塞 goroutine 场景，理解系统调用阻塞 M，P 会调度其他 M，掌握 go 调度行为。
 | 原文链接：http://book.1kjp1k.asia/blog/353660.Doc

原标题：避坑：正则回溯引发CPU占满DoS风险
简介：golang 故障演练服务模拟超时报错，程序模拟接口超时、报错，做混沌测试验证熔断降级有效性。
 | 原文链接：http://book.1kjp1k.asia/blog/243712.Doc

原标题：golang 系统设计指标埋点代码低侵入实现
简介：macOS 脚本执行权限开启，给 Shell 脚本添加可执行权限，解决 macOS 下脚本无法运行权限报错。
 | 原文链接：http://book.1kjp1k.asia/blog/507969.Doc

原标题：实战项目：本地模拟磁盘IO高负载观察服务行为
简介：Git 误删提交代码恢复找回，使用 Git reflog 工具找回被误删除提交记录，恢复误删除代码。
 | 原文链接：http://book.1kjp1k.asia/blog/491007.Doc

原标题：Practice：实现数据库事务消息最终一致性demo
简介：浮点计算精度错误处理方案，讲解浮点数计算精度丢失问题，使用合适数据类型，规避金额计算出错。
 | 原文链接：http://book.1kjp1k.asia/blog/819117.Doc

原标题：golang traceId spanId 传递方案
简介：容器资源限制防止宿主机过载，设置容器 CPU 内存资源上限，避免单个容器耗尽宿主机全部硬件资源。
 | 原文链接：http://book.1kjp1k.asia/blog/485910.Doc

原标题：golang prometheus 指标暴露实现
简介：静态网页 HTML CSS 快速入门实战，通过简单页面案例讲解标签、样式布局，从零编写页面，理解网页基础渲染原理。
 | 原文链接：http://book.1kjp1k.asia/blog/577111.Doc

原标题：架构复盘：业务系统中如何合理使用分库分表
简介：golang 延迟队列实现方案对比，时间轮、redis zset 实现延迟队列，处理延时执行业务。
 | 原文链接：http://book.1kjp1k.asia/blog/744648.Doc

原标题：百万数据 Excel 导出内存优化
简介：内存广播本地进程消息通知，实现进程内内存消息广播，进程内部模块之间事件通知解耦。
 | 原文链接：http://book.1kjp1k.asia/blog/307157.Doc

原标题：golang prometheus metrics 埋点开发
简介：golang channel 关闭规则与坑点，关闭已经关闭 channel 会 panic，判断 channel 是否关闭正确写法。
 | 原文链接：http://book.1kjp1k.asia/blog/684435.Doc

原标题：线上故障：热点Key打满RedisCPU节点过载
简介：golang websocket 服务端开发，Go 实现 WebSocket 服务端，处理连接、消息收发，实现长连接服务。
 | 原文链接：http://book.1kjp1k.asia/blog/382767.Doc

原标题：性能笔记：服务CPU高负载定位分析完整步骤
简介：golang net.Conn 包装自定义连接，包装 net.Conn，统计读写字节，日志打印，超时控制。
 | 原文链接：http://book.1kjp1k.asia/blog/677858.Doc

原标题：golang 系统设计消息发送确认机制配置实操
简介：慢查询分析索引调优数据库实战，抓取慢查询，分析执行计划，优化索引，解决数据库慢查询拖慢业务。
 | 原文链接：http://book.1kjp1k.asia/blog/015462.Doc

原标题：nodejs 日志轮转生产环境配置
简介：golang go 泛型约束与类型集合，泛型 type set 约束，限制泛型支持类型，写出安全泛型代码。
 | 原文链接：http://book.1kjp1k.asia/blog/832886.Doc

?
