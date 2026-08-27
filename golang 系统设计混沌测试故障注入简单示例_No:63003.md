最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计混沌测试故障注入简单示例
简介：golang runtime.Gosched 主动让出调度，长计算循环主动 Gosched，让出调度权，防止其他协程饥饿。
 | 原文链接：http://book.yapmzan.asia/blog/7533910.sHtMl

原标题：golang 协程 panic 捕获防止崩溃
简介：golang 大文件 HTTP 流式上传接收，服务端流式接收上传文件，不全部加载内存，防止大文件 OOM 崩溃。
 | 原文链接：http://book.yapmzan.asia/blog/7906235.sHtMl

原标题：Troubleshooting：WSL文件权限问题大量踩坑
简介：golang os/exec 安全执行外部命令，规避命令注入漏洞，参数分离，禁止拼接命令字符串执行。
 | 原文链接：http://book.yapmzan.asia/blog/4299227.sHtMl

原标题：nodejs redis 缓存业务实战
简介：golang cgo 内存管理 C 与 Go 内存，区分 Go 内存 C 堆内存，防止 cgo 内存泄漏，正确释放 C 内存。
 | 原文链接：http://book.yapmzan.asia/blog/8165647.sHtMl

原标题：开发复盘：导出大文件避免内存溢出实现方案
简介：集成测试业务流程编写示例，编写业务流程集成测试，覆盖完整业务链路，验证模块之间协同工作是否正常。
 | 原文链接：http://book.yapmzan.asia/blog/5097386.sHtMl

原标题：golang 系统设计防重复提交实现
简介：Git 仓库瘦身加快克隆下载速度，清理 Git 仓库历史大文件，缩减仓库体积，提升克隆拉取仓库速度。
 | 原文链接：http://book.yapmzan.asia/blog/7113800.sHtMl

原标题：Troubleshooting：防火墙安全组拦截访问请求
简介：Redis 分布式锁高并发安全实现，基于 Redis 实现分布式锁，处理锁过期、续期，保障集群并发安全。
 | 原文链接：http://book.yapmzan.asia/blog/5901162.sHtMl

原标题：golang 系统设计布隆过滤器原理与落地
简介：golang kafka 同步异步消费对比，对比 Kafka 同步消费异步消费，分析优缺点，业务选型参考。
 | 原文链接：http://book.yapmzan.asia/blog/9820913.sHtMl

原标题：Practice：实现文件监控自动重启开发服务工具
简介：接口幂等性防重复请求实现，实现接口幂等逻辑，避免重复提交请求产生多条脏数据，保障业务数据安全。
 | 原文链接：http://book.yapmzan.asia/blog/6687865.sHtMl

原标题：golang rsa 非对称加密签名验签
简介：服务熔断防止故障级联传播，实现服务熔断逻辑，下游故障时快速失败，阻止故障向上游链式扩散。
 | 原文链接：http://book.yapmzan.asia/blog/6507240.sHtMl

原标题：golang ci 流水线代码质量扫描集成
简介：golang json 自定义 MarshalJSON UnmarshalJSON，自定义 json 序列化反序列化逻辑，处理特殊格式字段。
 | 原文链接：http://book.yapmzan.asia/blog/3144365.sHtMl

原标题：golang mysql 长连接短连接对比
简介：WebSocket 断线重连稳定优化，增加 WebSocket 断线自动重连逻辑，处理网络抖动，维持长连接稳定。
 | 原文链接：http://book.yapmzan.asia/blog/8956094.sHtMl

原标题：架构复盘：数据库索引架构设计原则与边界
简介：golang go‑fuzz 模糊测试开发，go fuzz 模糊测试，自动构造异常输入，发现代码隐藏 bug。
 | 原文链接：http://book.yapmzan.asia/blog/0860678.sHtMl

原标题：安全笔记：JWT安全风险，签名泄露过期控制
简介：Git 代码冲突正确处理方式，讲解冲突产生场景，演示冲突文件修改，正确合并代码，防止代码丢失。
 | 原文链接：http://book.yapmzan.asia/blog/8988463.sHtMl

原标题：golang 系统设计 go benchmark 性能测试实操
简介：golang 互斥锁读写锁并发安全，互斥锁读写锁实操，保护共享变量，解决多协程并发读写数据竞争。
 | 原文链接：http://book.yapmzan.asia/blog/6577793.sHtMl

原标题：性能复盘：系统上下文切换过高性能下降调优
简介：Redis 内存淘汰策略数据防丢失，合理配置 Redis 内存淘汰策略，防止内存满后误删除业务重要数据。
 | 原文链接：http://book.yapmzan.asia/blog/3892894.sHtMl

原标题：golang mysql 悲观锁乐观锁实现
简介：golang 空接口 interface {} 类型处理，interface {} 存储任意类型，类型转换，处理泛型之前通用数据。
 | 原文链接：http://book.yapmzan.asia/blog/5917846.sHtMl

原标题：golang redis 缓存穿透解决方案
简介：golang 优雅处理 http 重定向逻辑，自定义控制 http 重定向跳转次数，防止无限重定向死循环。
 | 原文链接：http://book.yapmzan.asia/blog/2815028.sHtMl

原标题：golang k8s 基础概念 pod deployment
简介：golang go 程序敏感信息禁止打印日志，密钥密码禁止输出日志，防止敏感信息日志泄露。
 | 原文链接：http://book.yapmzan.asia/blog/3946750.sHtMl

原标题：架构复盘：跨机房多活架构基础概念与代价
简介：CI/CD 流水线自动构建部署落地，搭建完整 CI/CD 流水线，代码提交自动构建、测试、部署到目标环境。
 | 原文链接：http://book.yapmzan.asia/blog/0049514.sHtMl

原标题：运维笔记：系统内核参数调优生产服务器
简介：容器软链接文件权限修复，修复容器内软链接文件权限，让程序能够正常读取软链接指向的文件。
 | 原文链接：http://book.yapmzan.asia/blog/7898225.sHtMl

原标题：排错：HTTPS证书过期导致接口调用失败
简介：golang go math 大数高精度计算，math/big 处理超大整数、高精度浮点数，金额大数运算。
 | 原文链接：http://book.yapmzan.asia/blog/7195264.sHtMl

原标题：golang 系统设计 ide 配置 go 开发效率提升技巧
简介：golang grpc 重试机制客户端配置，grpc 客户端配置重试策略，临时故障自动重试，提升调用稳定性。
 | 原文链接：http://book.yapmzan.asia/blog/6379877.sHtMl

原标题：golang 系统设计配置多环境本地开发适配方案
简介：golang 熔断降级简易组件开发，Go 简易熔断组件，下游故障触发熔断，保护上游服务不被拖垮。
 | 原文链接：http://book.yapmzan.asia/blog/6495013.sHtMl

原标题：DevOps：多阶段构建Dockerfile最佳实践
简介：golang goroutine 泄露常见场景汇总，channel 阻塞、context 忘记取消，导致协程无法退出发生泄露。
 | 原文链接：http://book.yapmzan.asia/blog/5890880.sHtMl

原标题：golang 系统设计单元测试边界条件覆盖思路
简介：nodejs 进程间通信 IPC 实操，演示 Node.js 主进程子进程 IPC 通信，进程之间传递消息数据。
 | 原文链接：http://book.yapmzan.asia/blog/1504673.sHtMl

原标题：全局时间标准统一逻辑错乱修复
简介：rebase 操作防止代码丢失，讲解 rebase 风险点，操作前做好备份，规避错误操作造成代码提交丢失。
 | 原文链接：http://book.yapmzan.asia/blog/9083422.sHtMl

原标题：golang gin 静态资源访问配置
简介：golang 内存缓存简单实现方案，Go 实现进程内简易内存缓存，本地缓存热点数据，减少远程调用。
 | 原文链接：http://book.yapmzan.asia/blog/6497510.sHtMl

原标题：HelloEnv：多操作系统环境变量配置汇总
简介：Git 分支管理多人协作实战教程，详解分支创建、合并、冲突处理，适配团队开发场景，规范多人协同代码工作流。
 | 原文链接：http://book.yapmzan.asia/blog/2790203.sHtMl

原标题：golang docker compose 完整语法
简介：缓存基础原理与简单代码实现，讲解缓存设计思路，编写简易缓存逻辑，减少重复计算与重复请求，提升程序响应速度。
 | 原文链接：http://book.yapmzan.asia/blog/6391752.sHtMl

原标题：nestjs 框架模块化项目搭建
简介：golang go 服务压测前后性能对比，压测记录 QPS 延迟，优化前后对比，验证优化效果。
 | 原文链接：http://book.yapmzan.asia/blog/2857970.sHtMl

原标题：Practice：实现业务唯一流水号生成组件实践
简介：Nginx 透传真实客户端 IP 配置，配置 Nginx 把真实客户端 IP 传递后端服务，后端拿到访问者真实 IP。
 | 原文链接：http://book.yapmzan.asia/blog/0401601.sHtMl

原标题：golang 系统设计 grpc proto 接口设计原则
简介：golang testify testify 断言库使用，testify assert require 断言，简化单元测试断言代码。
 | 原文链接：http://book.yapmzan.asia/blog/0509024.sHtMl

原标题：golang github actions 完整工作流示例
简介：golang goreleaser 自动版本发布打包，goreleaser 自动化打包发布，生成多平台二进制归档文件。
 | 原文链接：http://book.yapmzan.asia/blog/5955164.sHtMl

原标题：golang mysql 分表自增 id 方案
简介：golang sync.Pool 对象池复用对象，sync.Pool 复用临时对象，减少内存分配，降低 GC 频率提升性能。
 | 原文链接：http://book.yapmzan.asia/blog/6697828.sHtMl

原标题：Performance：数据库分表解决单表过大性能衰减
简介：golang net.Conn 包装自定义连接，包装 net.Conn，统计读写字节，日志打印，超时控制。
 | 原文链接：http://book.yapmzan.asia/blog/6734528.sHtMl

原标题：DevOps：WSL2生产环境使用风险提示
简介：react hooks 常见陷阱避坑指南，梳理 React Hooks 高频踩坑点，依赖数组、闭包陷阱，写出稳定组件。
 | 原文链接：http://book.yapmzan.asia/blog/6086266.sHtMl

原标题：数据库读写分离性能优化
简介：golang 项目 go mod 依赖管理，Go Mod 管理项目依赖，下载、升级、清理依赖，解决依赖版本管理。
 | 原文链接：http://book.yapmzan.asia/blog/5390027.sHtMl

原标题：Hands‑on：本地模拟消息重复消费处理实践
简介：Redis 分布式锁高并发安全实现，基于 Redis 实现分布式锁，处理锁过期、续期，保障集群并发安全。
 | 原文链接：http://book.yapmzan.asia/blog/5319590.sHtMl

原标题：golang 系统设计 mq 消息顺序性保证思路
简介：golang 雪花 id 重复问题排查，排查雪花算法 ID 重复问题，时钟回拨、机器 ID 冲突，给出修复方案。
 | 原文链接：http://book.yapmzan.asia/blog/8020417.sHtMl


二、踩坑排错｜Troubleshooting
原标题：Troubleshooting：代理环境下证书校验失败HTTPS报错
简介：网关超时时间调优后端等待，调大网关向后端转发请求超时时间，给后端业务充足处理时间。
 | 原文链接：http://book.yapmzan.asia/blog/9767131.sHtMl

原标题：golang 系统设计限流服务架构讲解
简介：golang redis geo 地理位置存储查询，Redis GEO 存储经纬度，查询附近点位，实现附近人业务功能。
 | 原文链接：http://book.yapmzan.asia/blog/0913664.sHtMl

原标题：golang gin 静态资源访问配置
简介：前端权限路由动态生成实现，根据后端返回权限，动态生成前端路由菜单，实现页面权限控制。
 | 原文链接：http://book.yapmzan.asia/blog/3501657.sHtMl

原标题：新手指南：本地多版本环境共存配置
简介：分布式任务调度集群原型开发，开发简易分布式调度原型，集群多节点运行，保证任务只执行一次。
 | 原文链接：http://book.yapmzan.asia/blog/3005124.sHtMl

原标题：golang mysql 主从同步延迟兼容
简介：golang 消息死信处理业务逻辑，Go 实现死信队列逻辑，消费失败消息转入死信，不阻塞正常消息队列。
 | 原文链接：http://book.yapmzan.asia/blog/2899682.sHtMl

原标题：ServiceWorker 缓存页面更新清理
简介：批量操作分批处理防止 OOM，大批量数据处理不一次性加载全部数据，分批循环处理，避免内存溢出。
 | 原文链接：http://book.yapmzan.asia/blog/9424783.sHtMl

原标题：快速入门消息队列基础概念模型
简介：golang sort 搜索查找切片元素，sort.Search 二分查找有序切片，快速定位元素索引位置。
 | 原文链接：http://book.yapmzan.asia/blog/5275074.sHtMl

原标题：golang 系统设计 ide 配置 go 开发效率提升技巧
简介：gitignore 文件编写过滤规则，讲解 gitignore 语法，编写过滤配置，忽略缓存、编译产物、密钥文件，保持仓库整洁。
 | 原文链接：http://book.yapmzan.asia/blog/9228862.sHtMl

原标题：实战：数据库explain执行计划分析实操演练
简介：依赖安装失败全方位排错，从网络、镜像源、权限、版本多角度，定位依赖安装失败，给出对应修复手段。
 | 原文链接：http://book.yapmzan.asia/blog/3756337.sHtMl

原标题：依赖安装失败全方位排错
简介：golang redis 过期键监听回调，监听 key 过期事件，过期触发业务逻辑，实现过期自动处理业务场景。
 | 原文链接：http://book.yapmzan.asia/blog/0144261.sHtMl

原标题：运维笔记：服务器Swap分区调优生产实践
简介：golang 正则表达式 Go 实操案例，正则匹配提取替换，处理手机号邮箱校验，规避正则回溯 CPU 暴涨。
 | 原文链接：http://book.yapmzan.asia/blog/4501799.sHtMl

原标题：布隆过滤器数据高效去重实现
简介：后端大文件分片上传接口开发，开发后端分片上传接口，接收分片，合并分片完成大文件存储。
 | 原文链接：http://book.yapmzan.asia/blog/9338201.sHtMl

原标题：从零搭建本地开发环境完整教程
简介：golang atomic 原子操作整数，atomic 加减比较交换，无锁更新整型变量，简单计数器场景。
 | 原文链接：http://book.yapmzan.asia/blog/8453273.sHtMl

原标题：golang 系统设计数据库死锁分析规避
简介：golang proto 可选字段处理方案，protobuf 可选字段正确判断，区分未赋值与零值，业务逻辑不出现偏差。
 | 原文链接：http://book.yapmzan.asia/blog/5422924.sHtMl

原标题：架构复盘：多实例部署业务状态无状态改造
简介：gRPC 服务端客户端入门示例，搭建 gRPC 服务端与调用客户端，学习 protobuf 定义，掌握 RPC 基础开发流程。
 | 原文链接：http://book.yapmzan.asia/blog/2200268.sHtMl

原标题：golang 系统设计错误码体系完整设计
简介：golang 错误栈捕获打印方案，捕获错误完整调用堆栈，线上日志输出堆栈，快速定位错误发生代码位置。
 | 原文链接：http://book.yapmzan.asia/blog/7420679.sHtMl

原标题：golang redis 过期策略内存淘汰
简介：golang nacos go 客户端配置服务发现，nacos‑go 对接 nacos，配置管理、微服务注册发现。
 | 原文链接：http://book.yapmzan.asia/blog/0411876.sHtMl

原标题：golang mysql 悲观锁乐观锁实现
简介：接口幂等性防重复请求实现，实现接口幂等逻辑，避免重复提交请求产生多条脏数据，保障业务数据安全。
 | 原文链接：http://book.yapmzan.asia/blog/9785080.sHtMl

原标题：golang 系统设计服务优雅停机完整流程
简介：webpack chunk 分包策略详解，讲解 webpack chunk 分包策略，拆分第三方包与业务代码，优化缓存复用。
 | 原文链接：http://book.yapmzan.asia/blog/3989159.sHtMl

原标题：架构复盘：分表扩容架构平滑迁移思路
简介：golang io.Reader io.Writer 接口理解，io 读写接口，各类数据源统一抽象，适配 io 复制函数。
 | 原文链接：http://book.yapmzan.asia/blog/7315077.sHtMl

原标题：效率笔记：Git高级命令日常开发高频使用汇总
简介：站内邮件消息通知功能开发，实现站内消息、邮件通知推送，业务事件触发通知，提醒用户业务状态变更。
 | 原文链接：http://book.yapmzan.asia/blog/1277127.sHtMl

原标题：部署复盘：静态资源版本哈希缓存策略
简介：golang strings 常用函数业务实战，字符串分割替换包含判断前缀后缀，掌握 strings 包高频函数。
 | 原文链接：http://book.yapmzan.asia/blog/4900425.sHtMl

原标题：Hands‑on：简易链路追踪原型开发实践
简介：golang go 泛型约束与类型集合，泛型 type set 约束，限制泛型支持类型，写出安全泛型代码。
 | 原文链接：http://book.yapmzan.asia/blog/0771213.sHtMl

原标题：全局时间标准统一逻辑错乱修复
简介：重复提交幂等防护再次讲解，梳理前端重复点击、网络重试场景，落地接口幂等，杜绝重复业务。
 | 原文链接：http://book.yapmzan.asia/blog/5470576.sHtMl

原标题：开发记录：实现完整用户登录鉴权业务模块
简介：nodejs 单元测试 jest 实操教程，Jest 单元测试实操，编写测试用例，mock 依赖，验证业务逻辑正确性。
 | 原文链接：http://book.yapmzan.asia/blog/6417140.sHtMl

原标题：golang 系统设计网络超时故障排查思路
简介：golang race 检测器性能开销，race 检测器有性能损耗，只用于测试环境，禁止生产开启 race。
 | 原文链接：http://book.yapmzan.asia/blog/9345506.sHtMl

原标题：实战：Redis过期回调实现业务事件通知实践
简介：golang cgo 性能开销避坑指南，cgo 调用开销，减少频繁 cgo 调用，规避 cgo 带来内存泄漏风险。
 | 原文链接：http://book.yapmzan.asia/blog/5314909.sHtMl

原标题：golang 接口请求日志记录中间件
简介：Shell 脚本自动化命令编写，讲解 Shell 基础语法，编写自动化脚本，完成批量执行、文件处理，解放重复手工操作。
 | 原文链接：http://book.yapmzan.asia/blog/1657145.sHtMl

原标题：nodejs 日志轮转生产环境配置
简介：golang redis 锁超时业务处理，Redis 分布式锁超时问题处理，锁续期逻辑，防止业务未完成锁提前释放。
 | 原文链接：http://book.yapmzan.asia/blog/2268459.sHtMl

原标题：前后端交互跨域问题完整处理
简介：golang 配置文件多格式兼容加载，同时支持 yaml toml json 多种格式配置文件，灵活适配不同部署环境。
 | 原文链接：http://book.yapmzan.asia/blog/1891753.sHtMl

原标题：golang http 请求重试封装工具
简介：golang https 客户端跳过证书校验，开发测试环境跳过 tls 证书校验，仅用于内网测试禁止生产使用。
 | 原文链接：http://book.yapmzan.asia/blog/9010575.sHtMl

原标题：golang redis 连接池参数最佳值
简介：golang dns 自定义解析器实现，自定义 dns 解析，指定 dns 服务器，控制域名解析逻辑，适配内网环境。
 | 原文链接：http://book.yapmzan.asia/blog/9264275.sHtMl

原标题：Docker 容器入门镜像实操教程
简介：golang pdf 生成 go 服务端生成 pdf，服务端动态生成 pdf 报表文件，直接输出下载给到前端。
 | 原文链接：http://book.yapmzan.asia/blog/8863614.sHtMl

原标题：Nginx 缓冲区调优大文件上传
简介：golang go 变量逃逸场景汇总，切片、指针、返回局部变量引发逃逸，变量分配到堆影响 GC。
 | 原文链接：http://book.yapmzan.asia/blog/7765675.sHtMl

原标题：调优方案：JVM内存参数优化，降低GC频率
简介：golang ctx 关闭之后资源释放，context 取消后，监听 Done ()，释放 goroutine 网络 IO 资源。
 | 原文链接：http://book.yapmzan.asia/blog/0878599.sHtMl

原标题：Git commit 钩子提交规范校验
简介：RPC 报文大小上限调优大请求，调大 RPC 框架报文最大限制，支持传输大体积请求报文不被截断。
 | 原文链接：http://book.yapmzan.asia/blog/2803876.sHtMl

原标题：css 动画性能优化 GPU 加速
简介：OpenAPI 自动接口文档生成，集成 OpenAPI 工具，自动扫描代码生成接口文档，减少文档维护成本。
 | 原文链接：http://book.yapmzan.asia/blog/1704244.sHtMl

原标题：golang 系统设计覆盖索引减少回表查询实现
简介：golang go‑zero api 接口开发与路由，go‑zero 编写 api 定义文件，生成代码开发 http 接口。
 | 原文链接：http://book.yapmzan.asia/blog/5604557.sHtMl

原标题：实践：数据库慢查询分析与索引优化实战演练
简介：golang gorm select 指定查询字段，指定查询字段，避免查询全部字段，减少数据传输，提升查询性能。
 | 原文链接：http://book.yapmzan.asia/blog/5313572.sHtMl

原标题：Git 代码冲突正确处理方式
简介：文件编码统一随机乱码修复，统一项目全部文件读写编码，消除随机中文乱码，保证文本处理稳定。
 | 原文链接：http://book.yapmzan.asia/blog/7872008.sHtMl

三、实战开发｜Practice
原标题：golang redis 缓存雪崩完整处理
简介：golang jwt jwk 公钥验证令牌，使用 jwk 公钥校验 jwt，非对称方式签发校验令牌，提升安全性。
 | 原文链接：http://book.yapmzan.asia/blog/8795865.sHtMl

原标题：WSL 内存上限限制防止资源耗尽
简介：golang go 二进制安全 strip 减小体积，strip 剥离二进制调试符号，缩小程序二进制文件体积。
 | 原文链接：http://book.yapmzan.asia/blog/5505903.sHtMl

原标题：Debug：预加载逻辑错误服务启动时间成倍拉长
简介：golang go 网络编程 net 包基础，net 包 tcp udp socket 编程，监听接收连接，读写数据。
 | 原文链接：http://book.yapmzan.asia/blog/7968251.sHtMl

原标题：golang 系统设计告警规则阈值设置方法论
简介：开发代理服务网络限制解决，搭建本地代理服务，解决开发环境网络访问受限，实现外部接口正常调用。
 | 原文链接：http://book.yapmzan.asia/blog/0325992.sHtMl

原标题：极简 API 网关路由转发实现
简介：golang 时间轮算法实现延时调度，手写简易时间轮，高并发大量延时任务，降低轮询 CPU 消耗。
 | 原文链接：http://book.yapmzan.asia/blog/1176024.sHtMl

原标题：golang 系统设计 cpu 高占用排查步骤
简介：golang go 泛型约束与类型集合，泛型 type set 约束，限制泛型支持类型，写出安全泛型代码。
 | 原文链接：http://book.yapmzan.asia/blog/0209016.sHtMl

原标题：golang 系统设计全局异常处理器实现
简介：开源项目构建失败排查步骤，梳理构建报错排查流程，从依赖、网络、权限、脚本多角度定位项目构建失败原因。
 | 原文链接：http://book.yapmzan.asia/blog/6722577.sHtMl

原标题：golang redis 发布订阅简单示例
简介：golang 异步任务队列 worker 池开发，任务入数据库或 redis，worker 池消费执行，异步处理耗时业务。
 | 原文链接：http://book.yapmzan.asia/blog/4877311.sHtMl

原标题：实战项目：GitHubAction自动测试构建实践
简介：WebSocket 断线重连稳定优化，增加 WebSocket 断线自动重连逻辑，处理网络抖动，维持长连接稳定。
 | 原文链接：http://book.yapmzan.asia/blog/5651415.sHtMl

原标题：golang 系统设计熔断降级架构讲解
简介：golang gorm 预加载关联查询优化，GORM 预加载关联数据，避免 N+1 查询问题，提升数据库查询性能。
 | 原文链接：http://book.yapmzan.asia/blog/5751342.sHtMl

原标题：线上故障：慢查询拖垮整个数据库服务
简介：golang os 文件权限 mode，os.FileMode 文件权限，读写执行权限位，跨平台权限注意事项。
 | 原文链接：http://book.yapmzan.asia/blog/9535139.sHtMl

原标题：Practice：手写简易限流组件，计数器、令牌桶实现
简介：golang go race 竞态检测工具，‑race 检测数据竞争，编译运行检测并发读写数据竞争 bug。
 | 原文链接：http://book.yapmzan.asia/blog/9351427.sHtMl

原标题：golang cron 定时任务防并发执行
简介：golang 分表跨表 join 查询处理方案，分表后跨分片关联查询解决方案，业务层聚合代替数据库 join。
 | 原文链接：http://book.yapmzan.asia/blog/8492724.sHtMl

原标题：前后端交互跨域问题完整处理
简介：nodejs 流处理大文件不占内存，使用 Node.js 流处理超大文件，边读边写，不需要全部加载进内存。
 | 原文链接：http://book.yapmzan.asia/blog/5536020.sHtMl

原标题：开发生产环境资源路径统一
简介：golang bufio 缓冲读写性能优化，bufio 带缓冲读写，减少系统调用，提升文件网络 IO 性能。
 | 原文链接：http://book.yapmzan.asia/blog/4905394.sHtMl

原标题：Hands‑on：简易压缩中间件gzip实现实践
简介：golang context 取消传播机制，父 ctx 取消，所有派生子 context 全部被取消，理解上下文传播。
 | 原文链接：http://book.yapmzan.asia/blog/0258550.sHtMl

原标题：golang gitlab ci 配置自动构建镜像
简介：日志驱动异常日志不输出修复，排查日志驱动配置，修复日志写入配置，恢复程序正常日志输出。
 | 原文链接：http://book.yapmzan.asia/blog/8581458.sHtMl

原标题：golang 系统设计一致性哈希原理讲解
简介：异步异常捕获避免进程崩溃，捕获异步代码内部抛出异常，防止未捕获异常直接导致整个进程退出。
 | 原文链接：http://book.yapmzan.asia/blog/6083649.sHtMl

原标题：golang 系统设计 tcc 事务简单原理业务示例
简介：网络读取超时设置连接挂起防护，设置网络读取超时时间，防止请求无限挂起不返回，占用连接资源。
 | 原文链接：http://book.yapmzan.asia/blog/8664720.sHtMl

原标题：实战：容器内执行调试排错完整实操流程
简介：golang go 版本管理 go install 安装工具，go install 安装指定版本 go 工具，管理本地 go 工具版本。
 | 原文链接：http://book.yapmzan.asia/blog/3706969.sHtMl

原标题：nodejs 读取大文件 csv 处理方案
简介：golang go 并发模式 errgroup 使用，errgroup 结合 context，协程组，任意协程出错整体取消任务。
 | 原文链接：http://book.yapmzan.asia/blog/0400451.sHtMl

原标题：Security：业务操作审计日志安全留存
简介：golang docker compose 开发环境 go 服务，docker compose 编排 go 服务与中间件，本地一键拉起整套开发环境。
 | 原文链接：http://book.yapmzan.asia/blog/8211199.sHtMl

原标题：golang 系统设计 tcp 三次握手四次挥手梳理
简介：golang k8s secret 敏感配置加载，加载 k8s secret 存储密钥密码，敏感信息不存放配置文件。
 | 原文链接：http://book.yapmzan.asia/blog/6839180.sHtMl

原标题：手写简易 ORM 理解对象映射
简介：golang go 测试 t.Run 子测试分组，t.Run 实现子测试，分组执行用例，输出分组测试结果。
 | 原文链接：http://book.yapmzan.asia/blog/5909939.sHtMl

原标题：开发复盘：百万数据批量导入数据库优化方案
简介：golang http3 quic 客户端服务端示例，go 实现 http3 quic 服务端客户端，体验 quic 协议低延迟特性。
 | 原文链接：http://book.yapmzan.asia/blog/2082002.sHtMl

原标题：golang 内存缓存简单实现方案
简介：前端 pdf 预览渲染方案对比，对比前端 PDF 预览库，分析性能、兼容性，给出业务选型参考。
 | 原文链接：http://book.yapmzan.asia/blog/5663446.sHtMl

原标题：开发记录：敏感数据加密存储解密业务实践
简介：全局异常处理器接口返回统一，接入全局异常捕获，拦截业务全部异常，对外输出统一格式返回值。
 | 原文链接：http://book.yapmzan.asia/blog/1864074.sHtMl

原标题：golang 项目 makefile 脚本编写
简介：golang regexp 正则捕获分组提取数据，正则捕获分组提取子匹配内容，拿到需要业务字段。
 | 原文链接：http://book.yapmzan.asia/blog/0598641.sHtMl

原标题：坑点：环境配置被打包进镜像引发安全泄露
简介：Git commit 钩子提交规范校验，配置 Git 提交钩子，提交代码自动校验提交信息格式，规范提交记录。
 | 原文链接：http://book.yapmzan.asia/blog/8174782.sHtMl

原标题：golang 系统设计 protobuf 默认值坑点梳理
简介：简易日志收集集中管理方案，搭建轻量日志收集方案，把多服务日志汇总，集中检索查看日志信息。
 | 原文链接：http://book.yapmzan.asia/blog/4409711.sHtMl

原标题：golang 系统设计开源项目维护简单经验分享
简介：nodejs 脚手架工具开发完整教程，从零开发 Node 命令行脚手架，实现项目模板生成，理解 CLI 开发。
 | 原文链接：http://book.yapmzan.asia/blog/9627084.sHtMl

原标题：golang k8s 镜像拉取密钥配置
简介：Docker 多阶段构建镜像瘦身，使用 Docker 多阶段构建，剔除编译阶段依赖，产出体积更小运行镜像。
 | 原文链接：http://book.yapmzan.asia/blog/6368387.sHtMl

原标题：快速上手阅读开源项目源码的入门思路
简介：golang 项目 go mod 依赖管理，Go Mod 管理项目依赖，下载、升级、清理依赖，解决依赖版本管理。
 | 原文链接：http://book.yapmzan.asia/blog/6873329.sHtMl

原标题：开发记录：容器日志标准输出采集实践方案
简介：golang socket 文件描述符继承重启，父进程传递 listener fd 给子进程，实现 go 程序零停机热重启。
 | 原文链接：http://book.yapmzan.asia/blog/8600464.sHtMl

原标题：nodejs 信号处理优雅关闭服务
简介：golang 系统 IO 阻塞 goroutine 场景，理解系统调用阻塞 M，P 会调度其他 M，掌握 go 调度行为。
 | 原文链接：http://book.yapmzan.asia/blog/1522057.sHtMl

原标题：内网 DNS 不稳定随机报错排查
简介：golang bufio 缓冲读写性能优化，bufio 带缓冲读写，减少系统调用，提升文件网络 IO 性能。
 | 原文链接：http://book.yapmzan.asia/blog/8330159.sHtMl

原标题：快速入门ORM，实现简单数据库增删改查
简介：golang proto 可选字段处理方案，protobuf 可选字段正确判断，区分未赋值与零值，业务逻辑不出现偏差。
 | 原文链接：http://book.yapmzan.asia/blog/6658970.sHtMl

原标题：集成测试业务流程编写示例
简介：golang 半关闭 tcp 连接 shutdown，tcp 连接 shutdown 半关闭，单向关闭读或者写，理解 tcp 关闭流程。
 | 原文链接：http://book.yapmzan.asia/blog/6449053.sHtMl

原标题：golang 系统设计消息队列解耦削峰
简介：配置与镜像分离防止信息泄露，业务配置不打包进镜像，外部挂载配置，避免密钥配置随镜像泄露。
 | 原文链接：http://book.yapmzan.asia/blog/4425919.sHtMl

原标题：GraphQL 接口查询优化实操
简介：golang 本地消息表实现最终一致性，本地消息表 + 定时任务轮询，可靠消息实现分布式事务。
 | 原文链接：http://book.yapmzan.asia/blog/1201355.sHtMl

四、架构设计｜Architecture
原标题：静态站点自动部署发布方案
简介：多实例部署 Session 共享方案，多服务实例部署场景，实现 Session 共享，保证用户登录状态跨实例生效。
 | 原文链接：http://book.yapmzan.asia/blog/2638640.sHtMl

原标题：实践：静态站点自动化部署到GitHubPages
简介：单元测试用例编写入门实操，讲解测试用例设计思路，演示基础单元测试代码，提升代码健壮性，提前发现逻辑 bug。
 | 原文链接：http://book.yapmzan.asia/blog/8622932.sHtMl

原标题：golang 系统设计异步化改造业务流程思路
简介：golang go 服务日志输出 journald，systemd journald 接收程序 stdout 日志，统一管理服务日志。
 | 原文链接：http://book.yapmzan.asia/blog/2947613.sHtMl

原标题：golang k8s configmap secret 配置
简介：golang redis list 队列简易消息队列，利用 Redis List 实现简易队列，完成任务入队消费基础能力。
 | 原文链接：http://book.yapmzan.asia/blog/6004265.sHtMl

原标题：golang 项目 docker compose 本地调试
简介：golang go 并发模式 errgroup 使用，errgroup 结合 context，协程组，任意协程出错整体取消任务。
 | 原文链接：http://book.yapmzan.asia/blog/8196853.sHtMl

原标题：golang 系统设计 docker compose 本地开发环境搭建
简介：golang cgo 内存管理 C 与 Go 内存，区分 Go 内存 C 堆内存，防止 cgo 内存泄漏，正确释放 C 内存。
 | 原文链接：http://book.yapmzan.asia/blog/3734761.sHtMl

原标题：CI 构建缓存加速编译速度
简介：手写简易 ORM 理解对象映射，手写极简 ORM 示例，理解对象与数据库表字段映射底层原理。
 | 原文链接：http://book.yapmzan.asia/blog/5936340.sHtMl

原标题：实战：数据库索引设计，复合索引最佳实践
简介：react hooks 常见陷阱避坑指南，梳理 React Hooks 高频踩坑点，依赖数组、闭包陷阱，写出稳定组件。
 | 原文链接：http://book.yapmzan.asia/blog/0467373.sHtMl

原标题：golang 系统设计批量处理优化业务性能
简介：Git 标签版本标记发布管理，使用 Git 标签标记项目版本，打标签推送远程，用于版本发布、版本回溯。
 | 原文链接：http://book.yapmzan.asia/blog/3813863.sHtMl

原标题：golang 系统设计锁优化减少竞争提升吞吐
简介：golang 处理连接被重置 reset 错误，识别 connection reset by peer，对端关闭连接异常处理逻辑。
 | 原文链接：http://book.yapmzan.asia/blog/6035964.sHtMl

原标题：golang 系统设计短链接服务实现思路
简介：golang os 主机名内核版本读取，os 读取主机名，内核信息，操作系统版本，获取运行环境信息。
 | 原文链接：http://book.yapmzan.asia/blog/2701643.sHtMl

原标题：Debug：预加载逻辑错误服务启动时间成倍拉长
简介：golang go 爬虫 robots 协议遵守，解析 robots.txt 规则，控制爬虫抓取范围，合规采集网页数据。
 | 原文链接：http://book.yapmzan.asia/blog/4427372.sHtMl

原标题：线上接口超时故障排查思路
简介：golang atomic 原子操作整数，atomic 加减比较交换，无锁更新整型变量，简单计数器场景。
 | 原文链接：http://book.yapmzan.asia/blog/8331983.sHtMl

原标题：Docker 网络模式容器互通设置
简介：数值 key 浮点匹配异常规避，避免浮点数作为 Redis 等存储的 key，防止精度问题引发 key 匹配失败。
 | 原文链接：http://book.yapmzan.asia/blog/4682688.sHtMl

原标题：跨域偶现失败配置修复
简介：golang 信号触发配置重载实践，收到 SIGUSR1 信号重新加载配置，线上无需重启刷新配置。
 | 原文链接：http://book.yapmzan.asia/blog/3880402.sHtMl

原标题：golang 系统设计逻辑删除物理删除选型对比
简介：golang go‑zero api 接口开发与路由，go‑zero 编写 api 定义文件，生成代码开发 http 接口。
 | 原文链接：http://book.yapmzan.asia/blog/3511424.sHtMl

原标题：golang 系统设计指标埋点代码低侵入实现
简介：YAML 配置文件语法快速上手，讲解 YAML 基础语法、缩进规则，编写项目配置文件，规避语法错误引发程序异常。
 | 原文链接：http://book.yapmzan.asia/blog/3119536.sHtMl

原标题：Hands‑on：简易反向代理中间件实现
简介：golang 反向代理 http 服务开发，手写简易 http 反向代理，转发请求，修改请求头响应头。
 | 原文链接：http://book.yapmzan.asia/blog/6347698.sHtMl

?
