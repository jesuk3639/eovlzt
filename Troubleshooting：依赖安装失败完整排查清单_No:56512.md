最新前沿技术资讯

一、入门教程｜Getting Started
原标题：Troubleshooting：依赖安装失败完整排查清单
简介：golang sync.Map 高并发 map 使用场景，sync.Map 适用场景，读写实操，对比普通 map 加锁性能差异。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/129663.sHtML

原标题：golang 系统设计多级缓存架构落地
简介：golang redis hyperloglog 基数统计，hyperloglog 统计 UV 基数，海量数据去重统计，极低内存开销。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/028948.sHtML

原标题：开发测试生产多环境配置区分
简介：golang errors.Is errors.As 错误判断，判断是否为指定错误类型，提取自定义错误信息，错误处理进阶。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/928596.sHtML

原标题：Issue：日志输出包含敏感信息造成泄露风险
简介：安全组端口开放网络访问，调整服务器安全组规则，开放业务需要端口，恢复外部网络访问服务。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/667585.sHtML

原标题：开发记录：长连接连接管理自动清理僵死连接
简介：golang cgo 内存管理 C 与 Go 内存，区分 Go 内存 C 堆内存，防止 cgo 内存泄漏，正确释放 C 内存。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/840443.sHtML

原标题：Performance：数据库分表解决单表过大性能衰减
简介：golang 大文件 HTTP 流式上传接收，服务端流式接收上传文件，不全部加载内存，防止大文件 OOM 崩溃。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/908177.sHtML

原标题：开发记录：分布式ID生成器实现与压力测试
简介：golang 数据库连接耗尽排查思路，监控连接池状态，定位连接未归还，解决连接耗尽报错。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/576161.sHtML

原标题：踩坑记录：UTC时间与本地时间混用逻辑错乱
简介：golang 进程信号捕获 SIGUSR 自定义信号，捕获用户自定义信号，实现线上不重启触发调试、日志切换。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/868884.sHtML

原标题：项目实践：Docker多环境镜像构建策略实践
简介：golang 分布式追踪全链路日志打印，日志打印 traceId，各个服务日志可串联，排查跨服务调用问题。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/675827.sHtML

原标题：golang ci 流水线单元测试集成测试
简介：全平台系统环境变量配置，汇总多操作系统环境变量配置方法，统一项目读取逻辑，适配不同运行平台。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/505449.sHtML

原标题：实战项目：容器资源限制配置压力测试实践
简介：golang ctx 关闭之后资源释放，context 取消后，监听 Done ()，释放 goroutine 网络 IO 资源。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/986150.sHtML

原标题：golang 系统设计蓝绿发布滚动发布对比
简介：全局本地依赖隔离冲突规避，区分全局依赖与项目本地依赖，隔离环境，防止全局包干扰项目运行。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/995261.sHtML

原标题：golang kafka 批量发送消费优化
简介：golang 限流器熔断降级组合使用，限流熔断降级组合架构，流量防护完整方案，保障服务稳定性。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/814128.sHtML

原标题：方案对比：几种任务队列架构选型优缺点
简介：golang go 程序容器资源 requests limits，设置容器 cpu 内存配额，防止实例抢占集群资源，稳定调度。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/666199.sHtML

原标题：golang 系统设计配置敏感信息加密存储
简介：golang go 变量逃逸场景汇总，切片、指针、返回局部变量引发逃逸，变量分配到堆影响 GC。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/741079.sHtML

原标题：容器内存扩容 OOM 被杀死修复
简介：golang 任务失败重试与死信队列，异步任务失败自动重试，超过重试次数进入死信队列人工处理。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/996530.sHtML

原标题：用户敏感数据脱敏代码实现
简介：golang sort 切片排序自定义 less，sort.Slice 切片快速排序，自定义 less 函数实现业务排序。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/510392.sHtML

原标题：golang 系统设计内部服务契约测试简单思路
简介：golang 滑动窗口限流算法 go 实现，滑动窗口限流，解决固定窗口临界流量突增漏洞，限流更精准。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/199891.sHtML

原标题：golang 系统设计消息重试次数间隔策略设置
简介：golang 协程数量监控统计方案，统计运行中 goroutine 数量，监控协程泄露，协程数量异常及时告警。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/678860.sHtML

原标题：开源项目本地运行排错完整清单
简介：定时任务周期调度 demo 开发，实现简单定时调度程序，按时间周期执行业务逻辑，理解定时任务运行机制。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/315366.sHtML

原标题：golang 系统设计告警渠道钉钉邮件企业微信集成
简介：golang 异步任务队列 worker 池开发，任务入数据库或 redis，worker 池消费执行，异步处理耗时业务。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/106858.sHtML

原标题：设计思考：系统限流熔断降级完整防护体系
简介：golang go‑zero 框架项目快速搭建，go‑zero 脚手架生成微服务项目，api rpc 服务快速开发。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/569852.sHtML

原标题：golang 日志 zap 结构化日志实践
简介：开发环境变量配置全平台教程，区分 Windows、macOS、Linux 系统，讲解环境变量配置、加载优先级与常见失效原因。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/776372.sHtML

原标题：部署复盘：配置不要硬编码进镜像最佳实践
简介：文件读写与异常捕获代码示例，演示文件读取写入操作，增加异常捕获逻辑，规避文件不存在、权限不足导致崩溃。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/255868.sHtML

原标题：golang 系统设计多租户数据隔离方案
简介：golang 微服务网关简易实现，http 反向代理、路由匹配、鉴权限流，理解网关核心原理。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/377003.sHtML

原标题：golang 系统设计防爬虫简单策略
简介：golang trace 工具采集 go 程序执行轨迹，go trace 采集程序完整调度轨迹，分析协程调度阻塞问题。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/013411.sHtML

原标题：开发记录：网关实现接口鉴权、限流、日志打印
简介：缓存过期打散防止缓存雪崩，对缓存过期时间增加随机偏移，避免大量缓存同时失效引发缓存雪崩。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/991811.sHtML

原标题：golang 系统设计开源项目协作流程梳理
简介：golang html 模板渲染简单示例，Go HTML 模板渲染，服务端渲染页面，填充数据输出 HTML 页面。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/088023.sHtML

原标题：golang 系统设计 ide 配置 go 开发效率提升技巧
简介：express 中间件开发业务实践，开发 Express 自定义中间件，拦截请求，实现鉴权、日志记录等通用逻辑。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/706947.sHtML

原标题：踩坑记录：分页逻辑错误造成数据重复输出
简介：golang accept 错误循环崩溃处理，accept 返回系统错误，处理临时错误，避免死循环占满 CPU。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/630062.sHtML

原标题：线程池拒绝策略任务丢失防护
简介：golang 数据库分表策略按时间分片，按时间维度分表，历史数据拆分，单表数据量控制保证查询性能。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/058220.sHtML

原标题：golang 系统设计日志规范结构化日志落地
简介：分布式 ID 生成器高并发实现，实现高性能分布式 ID 生成器，适配高并发业务，生成全局唯一 ID。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/607117.sHtML

原标题：特殊输入字符过滤解析防护
简介：git rebase 整理提交历史实操，使用 rebase 整理杂乱提交记录，将多条提交合并，保持 git 提交历史干净线性。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/356987.sHtML

原标题：golang 工具函数库封装思路
简介：golang systemd 信号与优雅退出配合，systemd 停止服务发送 SIGTERM，go 程序捕获信号优雅关闭。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/615497.sHtML

原标题：Troubleshoot：跨域偶现失败难以复现问题
简介：golang go select 多路等待 channel，select 等待多个 channel，default 非阻塞，超时等待 channel。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/263602.sHtML

原标题：Hands‑on：简易邮件发送服务封装实践
简介：golang fasthttp 高性能 http 库使用，fasthttp 高性能 http 实现，适合超高 QPS 场景，对比 net/http 差异。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/507001.sHtML

原标题：golang 系统设计容量评估简单方法论
简介：接口请求重试容错机制实现，封装请求重试逻辑，遇到临时网络故障自动重试，提升第三方调用稳定性。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/535769.sHtML

原标题：Practice：实现请求body重复读取中间件实践
简介：golang go 服务压测前后性能对比，压测记录 QPS 延迟，优化前后对比，验证优化效果。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/823997.sHtML

原标题：系统字符集统一乱码修复
简介：golang contract 契约测试微服务，微服务契约测试，保证接口变更不破坏调用方，提前发现兼容性问题。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/331486.sHtML

原标题：CI 持续集成自动构建流程
简介：分布式 ID 生成器高并发实现，实现高性能分布式 ID 生成器，适配高并发业务，生成全局唯一 ID。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/768019.sHtML


二、踩坑排错｜Troubleshooting
原标题：调优方案：JVM内存参数优化，降低GC频率
简介：golang 错误处理最佳实践汇总，Go 错误处理规范，包装错误，堆栈携带，拒绝简单忽略错误。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/574309.sHtML

原标题：golang es 索引生命周期管理思路
简介：Shell 运维脚本服务器效率提升，编写常用运维 Shell 脚本，自动化服务器运维操作，减少手工重复工作。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/604289.sHtML

原标题：入门实践：实现简单文件读写功能
简介：golang go mod tidy 依赖清理，go mod tidy 自动增删依赖，整理 go.mod go.sum 文件。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/566955.sHtML

原标题：Git 标签版本标记发布管理
简介：大事务拆分回滚日志暴涨解决，拆分大型数据库事务，减少回滚日志生成量，避免磁盘被回滚日志占满。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/618402.sHtML

原标题：架构笔记：高并发系统核心设计思路总结
简介：golang makefile 多平台编译脚本，makefile 一键交叉编译多平台二进制，打包镜像，执行测试。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/503723.sHtML

原标题：golang redis lua 脚本开发调试
简介：TCP 心跳检测清理僵死连接，开启 TCP 心跳机制，自动清理僵死无效连接，释放连接资源。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/344667.sHtML

原标题：Hands‑on：shell脚本批量自动化运维小工具
简介：前端下载导出文件功能实现，前端实现文件流下载导出，处理异常，适配浏览器不同下载行为。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/725677.sHtML

原标题：全局时间标准统一逻辑错乱修复
简介：nodejs 全局异常捕获进程防护，捕获未捕获异常与 Promise 拒绝，尽量保护进程不因为异常直接退出。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/731817.sHtML

原标题：golang k8s 日志收集 efk 简单架构
简介：golang go 变量逃逸场景汇总，切片、指针、返回局部变量引发逃逸，变量分配到堆影响 GC。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/578859.sHtML

原标题：golang 项目目录分层规范设计
简介：本地简易配置中心动态管理，搭建轻量本地配置中心，业务动态读取配置，修改配置不重启服务。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/819933.sHtML

原标题：安全笔记：请求头伪造IP漏洞防护
简介：Redis 分布式锁高并发安全实现，基于 Redis 实现分布式锁，处理锁过期、续期，保障集群并发安全。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/597190.sHtML

原标题：前端虚拟列表大数据渲染优化
简介：golang 时间时区处理避坑指南，Go 时间时区常见坑，时区转换，时间比较，规避时间逻辑错误。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/926855.sHtML

原标题：golang 系统设计网关路由规则动态配置实现
简介：golang netlink 系统信息获取，netlink 获取系统网络信息，网卡地址，内核网络状态读取。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/101016.sHtML

原标题：坑点：软链接权限问题容器读取文件失败
简介：golang 优雅处理 http 重定向逻辑，自定义控制 http 重定向跳转次数，防止无限重定向死循环。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/493421.sHtML

原标题：记一次GC频繁，服务CPU持续高负载排查
简介：golang os 文件权限 mode，os.FileMode 文件权限，读写执行权限位，跨平台权限注意事项。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/760298.sHtML

原标题：golang 系统设计依赖漏洞扫描修复流程
简介：golang 故障演练服务模拟超时报错，程序模拟接口超时、报错，做混沌测试验证熔断降级有效性。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/634488.sHtML

原标题：数据库事务 ACID 原理讲解
简介：golang net/http 超时全套配置，完整配置 Go HTTP 服务读写空闲超时，全方位防止请求挂住。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/893492.sHtML

原标题：express 中间件开发业务实践
简介：数值类型溢出错乱问题修复，选择合适数值存储类型，处理数值溢出，避免数据存储错乱结果异常。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/018343.sHtML

原标题：设计思考：业务系统如何做故障隔离架构
简介：golang go http 安全头配置实践，设置 http 安全响应头，防范 XSS、点击劫持，提升 web 服务安全性。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/211389.sHtML

原标题：Practice：实现批量任务失败断点续跑实践
简介：golang 分布式 ID 雪花算法实现，Go 实现雪花算法，生成分布式全局唯一 ID，适配分库分表主键。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/565912.sHtML

原标题：golang 系统设计 json 解析性能优化实操
简介：golang url 解析路径参数提取，url.Parse 解析 url，获取协议主机路径查询参数。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/003781.sHtML

原标题：踩坑：批量MQ消费失败直接无限重试消息爆炸
简介：代码格式化工具团队统一风格，接入格式化工具，统一全团队代码书写风格，减少格式类 git 冲突。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/341248.sHtML

原标题：Debug：表单自动转义特殊字符业务逻辑出错
简介：TCP 长连接参数优化 TIME_WAIT，调整 TCP 内核参数，优化长连接，减少大量 TIME_WAIT 连接占用资源。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/011647.sHtML

原标题：golang redis stream 消息队列实践
简介：golang jwt 鉴权中间件完整示例，Gin JWT 鉴权中间件，令牌校验，解析用户信息，接口鉴权拦截。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/075605.sHtML

原标题：Hands‑on：简易短链接服务完整开发实践
简介：golang defer 执行顺序与坑点，defer 后进先出，循环内部 defer 陷阱，资源释放正确写法。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/241845.sHtML

原标题：golang 系统设计告警分级 p0‑p3 定义处理流程
简介：golang 网卡 ip 读取网络信息获取，程序读取本机网卡 IP，多网卡环境筛选业务使用 IP 地址。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/860079.sHtML

原标题：静态站点自动部署发布方案
简介：golang 数据库慢查询监控实现，Go 封装 SQL 执行监控，记录慢 SQL，上报日志，发现数据库性能问题。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/274631.sHtML

原标题：golang goroutine 池任务调度
简介：golang go‑pg postgres 客户端实操，go‑pg 操作 PostgreSQL 数据库，CRUD 关联查询业务开发。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/359713.sHtML

原标题：调优方案：服务实例扩容，水平扩展性能
简介：golang 延迟队列实现方案对比，时间轮、redis zset 实现延迟队列，处理延时执行业务。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/132150.sHtML

原标题：快速入门异步编程基础模型
简介：golang clickhouse go 客户端数据写入，clickhouse‑go 客户端写入查询，海量时序数据分析业务。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/670908.sHtML

原标题：静态站点自动部署发布方案
简介：golang kafka 消费者位移管理，理解 kafka offset，手动提交位移，保证消息消费至少一次语义。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/506550.sHtML

原标题：Troubleshoot：异步异常未捕获，进程悄无声息退出
简介：开发测试生产多环境配置区分，讲解三套环境配置分离思路，配置文件隔离，防止开发配置泄露到生产环境。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/157352.sHtML

原标题：golang 系统设计开源项目维护简单经验分享
简介：golang bufio.Scanner 缓冲区调大，Scanner 默认缓冲区大小不够，读取超长行需要扩大缓冲区。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/493684.sHtML

原标题：从零搭建本地数据库开发环境
简介：golang 简单爬虫请求防封禁，简易 Go 爬虫实现，增加请求间隔、UA 伪装，规避被目标站点封禁 IP。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/997115.sHtML

原标题：golang aes 对称加密解密示例
简介：golang jaeger 链路追踪部署对接，jaeger 接收 opentelemetry 链路数据，可视化完整调用链路。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/279669.sHtML

原标题：golang 系统设计 canary 金丝雀部署实操
简介：布隆过滤器误判问题修正，调整布隆过滤器参数，降低误判概率，保证业务去重逻辑准确。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/446358.sHtML

原标题：排错：DockerCompose依赖顺序启动顺序坑
简介：定时任务周期调度 demo 开发，实现简单定时调度程序，按时间周期执行业务逻辑，理解定时任务运行机制。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/192908.sHtML

原标题：golang 静态文件服务搭建教程
简介：golang rate 令牌桶限流器源码理解，拆解令牌桶限流核心逻辑，理解令牌生成消耗，掌握限流底层原理。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/574722.sHtML

原标题：golang 接口请求日志记录中间件
简介：前端打包产物体积压缩优化，多手段压缩前端打包产物，移除无用代码，压缩资源，提升页面加载速度。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/555116.sHtML

原标题：新手教程：Git撤销错误提交的几种常用方式
简介：Cookie 跨环境登录配置调整，调整 Cookie 域、Secure 属性，适配开发测试生产环境，修复登录失效。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/128258.sHtML

三、实战开发｜Practice
原标题：从零搭建简单定时任务demo
简介：golang tidb 数据库 go 项目适配，go 程序适配 tidb，兼容 mysql 协议，分布式数据库业务开发。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/863213.sHtML

原标题：nodejs http 服务性能调优实战
简介：DNS 解析异常第三方调用故障，排查 DNS 解析故障，修复域名解析，恢复第三方接口网络调用。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/964626.sHtML

原标题：Hands‑on：模板渲染引擎最小原型实现
简介：golang tls 证书加载配置 https 服务，加载证书密钥，搭建 golang https 服务，配置 tls 版本安全策略。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/115408.sHtML

原标题：golang 系统设计 protobuf 默认值坑点梳理
简介：开发生产环境资源路径统一，对齐开发环境与生产环境资源路径，防止本地正常上线后资源找不到。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/341338.sHtML

原标题：golang gitlab ci 配置自动构建镜像
简介：磁盘 inode 耗尽文件创建失败，排查磁盘 inode 占用，清理大量小文件，恢复文件创建能力。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/900998.sHtML

原标题：golang 系统设计分布式锁不同场景选型对比
简介：业务接口幂等完整落地案例，完整业务场景幂等落地示例，覆盖表单提交、回调、重试各类场景。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/604765.sHtML

原标题：开发记录：敏感数据加密存储解密业务实践
简介：golang context 取消传播机制，父 ctx 取消，所有派生子 context 全部被取消，理解上下文传播。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/729515.sHtML

原标题：性能笔记：磁盘IO过高业务优化手段
简介：golang 日志级别动态调整热更新，不用重启程序动态修改日志输出级别，线上调试排查问题十分方便。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/868191.sHtML

原标题：开发复盘：分库分表本地模拟与数据路由实践
简介：前端图片懒加载性能优化，实现图片懒加载，页面可视区域才加载图片，减少页面初始网络请求。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/684732.sHtML

原标题：Troubleshoot：跨域偶现失败难以复现问题
简介：golang go‑pg postgres 客户端实操，go‑pg 操作 PostgreSQL 数据库，CRUD 关联查询业务开发。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/070365.sHtML

原标题：架构笔记：高并发系统核心设计思路总结
简介：golang go url url.Values 参数编码，url.Values 构建 url 查询参数，自动处理参数 url 编码。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/231494.sHtML

原标题：批量操作分批处理防止 OOM
简介：接口签名验签完整安全方案，一套完整接口签名方案，包含签名生成、请求携带、服务端验签校验。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/015246.sHtML

原标题：任务执行锁防止并发重复调度
简介：golang websocket 服务端开发，Go 实现 WebSocket 服务端，处理连接、消息收发，实现长连接服务。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/418851.sHtML

原标题：Troubleshoot：CPU调度频繁上下文切换性能下降
简介：golang time 定时器重置 Reset 正确用法，Timer Reset 调用前提，避免 Reset 带来逻辑错误。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/950504.sHtML

原标题：golang redis lua 脚本开发调试
简介：进程线程并发基础概念讲解，区分进程与线程，讲解调度逻辑，理解并发执行原理，为高并发业务开发打基础。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/122469.sHtML

原标题：运维笔记：线上服务健康检查脚本编写
简介：Fork 开源项目同步上游代码，Fork 开源仓库之后，配置上游源，同步官方最新代码，保持代码版本对齐。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/064184.sHtML

原标题：DevOps：私有镜像仓库搭建与权限管控
简介：golang 处理连接被重置 reset 错误，识别 connection reset by peer，对端关闭连接异常处理逻辑。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/067699.sHtML

原标题：开发复盘：搭建文件上传服务支持分片断点续传
简介：golang go embed 嵌入静态资源文件，使用 go embed 把静态文件编译进二进制，单文件部署携带静态资源。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/715375.sHtML

原标题：入门实践：简单的请求封装与异常捕获
简介：Git 子模块更新代码不全修复，正确更新 Git 子模块，拉取子模块完整代码，解决子模块目录为空问题。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/801681.sHtML

原标题：SourceMap 生成线上报错定位
简介：消息队列生产消费模型入门，讲解消息队列生产、存储、消费流程，理解异步解耦、削峰，掌握消息队列基础概念。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/875841.sHtML

原标题：超大数据集分页性能优化方案
简介：golang trace 链路追踪 opentelemetry，opentelemetry 实现链路追踪，生成 traceId spanId，完整记录调用链路。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/399264.sHtML

原标题：golang 系统设计分表扩容数据平滑迁移思路
简介：golang 字符编码转换 go 处理，iconv‑go 做编码转换 gbk utf8 互转，处理老旧系统 gbk 编码数据。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/018508.sHtML

原标题：快速入门ORM，实现简单数据库增删改查
简介：golang arp 缓存读取操作，读取系统 arp 缓存表，获取 ip 对应的 mac 地址信息。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/617587.sHtML

原标题：golang 系统设计 rest 状态码合理使用指南
简介：WSL 文件权限访问异常修复，处理 WSL 环境文件权限错乱，调整权限配置，实现文件正常读写访问。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/887772.sHtML

原标题：Hands‑on：实现WebSocket聊天室完整前后端demo
简介：golang go 代码覆盖率线上统计，单元测试覆盖率统计，找出未测试代码分支，提升测试质量。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/072538.sHtML

原标题：HTTPS 证书过期更新操作
简介：golang go 泛型约束与类型集合，泛型 type set 约束，限制泛型支持类型，写出安全泛型代码。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/535545.sHtML

原标题：Git 分支切换合并删除完整操作
简介：前端水印防信息泄露实现，实现网页水印功能，页面叠加用户信息水印，防止页面截图信息外泄。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/978667.sHtML

原标题：开发环境变量配置全平台教程
简介：golang benchmark 减少测试干扰，benchmark 执行循环 b.N，避免循环内部做非被测逻辑干扰结果。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/612549.sHtML

原标题：手写简易 ORM 理解对象映射
简介：TLS 版本兼容 HTTPS 握手失败，兼容老旧 TLS 协议版本，修复部分客户端 HTTPS 握手失败无法访问。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/063663.sHtML

原标题：Hands‑on：简易请求转发代理中间件实现
简介：golang ip 限流黑名单实现方案，基于 IP 做限流与黑名单，拦截恶意 IP 访问，保护接口服务。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/160528.sHtML

原标题：安全复盘：业务登录暴力破解防护完整方案
简介：移动端适配 rem vw 方案对比，对比 rem 与 vw 移动端适配方案，分析优缺点，给出选型建议。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/182216.sHtML

原标题：分布式 ID 生成器高并发实现
简介：golang trace 工具采集 go 程序执行轨迹，go trace 采集程序完整调度轨迹，分析协程调度阻塞问题。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/585564.sHtML

原标题：golang alertmanager 钉钉告警推送
简介：Mock 接口服务快速搭建实操，搭建模拟后端接口，自定义返回数据、延迟响应，前端开发阶段无需依赖真实后端服务。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/597679.sHtML

原标题：文件监控服务自动重启开发
简介：WebSocket 聊天室实时通讯开发，基于 WebSocket 搭建简易聊天室，实现多人消息广播实时聊天效果。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/338021.sHtML

原标题：golang 系统设计 canary 金丝雀部署实操
简介：golang os/exec 安全执行外部命令，规避命令注入漏洞，参数分离，禁止拼接命令字符串执行。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/415957.sHtML

原标题：方案对比：本地缓存vs分布式缓存架构取舍
简介：灰度发布策略服务平滑升级，实现灰度发布逻辑，流量逐步切到新版本，出现问题快速回滚旧版本。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/450350.sHtML

原标题：实战：数据库索引设计，复合索引最佳实践
简介：golang go‑zero 中间件鉴权限流，go‑zero 自定义中间件，实现鉴权、限流、日志打印通用能力。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/666321.sHtML

原标题：CORS 跨域问题多种解决方案
简介：golang go 线上故障排查完整流程，CPU 高、内存上涨、接口超时、goroutine 泄露一套排查处理流程。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/261736.sHtML

原标题：Hands‑on：简易ID生成雪花算法完整实现
简介：前端水印防信息泄露实现，实现网页水印功能，页面叠加用户信息水印，防止页面截图信息外泄。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/424146.sHtML

原标题：golang es 查询语句 DSL 实操
简介：线程池拒绝策略任务丢失防护，合理设置线程池拒绝策略，处理任务队列满场景，避免业务任务直接丢失。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/335828.sHtML

四、架构设计｜Architecture
原标题：防火墙 IP 白名单回调接口放行
简介：WebSocket 聊天室实时通讯开发，基于 WebSocket 搭建简易聊天室，实现多人消息广播实时聊天效果。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/610638.sHtML

原标题：入门实践：项目配置文件多环境管理方案
简介：系统时间同步定时任务偏移，同步服务器系统时间，防止时间偏移，避免定时任务执行时间错乱。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/645150.sHtML

原标题：TCP 长连接参数优化 TIME_WAIT
简介：golang elasticsearch 客户端 golang 实操，es 客户端文档增删改查，条件搜索聚合统计对接搜索引擎。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/608289.sHtML

原标题：golang 系统设计本地缓存与分布式缓存
简介：golang 配置热更新不重启服务，实现配置热加载，监听配置变更，更新内存配置，无需重启服务实例。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/456848.sHtML

原标题：golang html 模板渲染简单示例
简介：前端虚拟列表大数据渲染优化，实现虚拟滚动列表，只渲染可视区域 DOM，上万条数据页面流畅渲染。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/727502.sHtML

原标题：零基础理解内存溢出基础现象与表现
简介：golang go 容器 heap 堆实现优先队列，实现 heap 接口，构建优先队列，任务优先级调度。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/231731.sHtML

原标题：业务接口幂等完整落地案例
简介：golang gzip 压缩 http 响应，服务端开启 gzip 压缩，减小接口响应体积，降低网络传输耗时。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/754667.sHtML

原标题：golang mysql exists in 性能对比
简介：golang k8s go 服务 yaml 资源编写，k8s 部署 go 应用 deployment service，健康检查资源限制配置。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/755149.sHtML

原标题：设计思考：分布式会话架构选型对比
简介：golang go ring 环形容器循环队列，ring 环形链表实现循环队列，环形缓冲区业务场景。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/745906.sHtML

原标题：golang 跨域处理中间件编写
简介：golang cgo 内存管理 C 与 Go 内存，区分 Go 内存 C 堆内存，防止 cgo 内存泄漏，正确释放 C 内存。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/239246.sHtML

原标题：golang 系统设计 tcp 粘包拆包处理方案实现
简介：golang wasm 性能优化与内存管理，wasm 内存分配释放，减少内存拷贝，优化浏览器端性能。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/750097.sHtML

原标题：golang 系统设计令牌桶漏桶算法对比
简介：golang context.WithCancel 手动取消上下文，WithCancel 生成可取消 ctx，手动调用 cancel 触发取消。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/798843.sHtML

原标题：golang 系统设计本地缓存 redis 缓存多级组合
简介：golang 服务注册 etcd 简单示例，etcd 实现服务注册发现，微服务实例注册元数据，客户端发现节点。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/756846.sHtML

原标题：Hands‑on：简易速率限制中间件完整实现
简介：golang sync.RWMutex 读写锁使用场景，读多写少场景读写锁，读共享写互斥，提升并发性能。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/383053.sHtML

原标题：Hands‑on：简易图片压缩处理服务demo
简介：时间同步修复令牌提前过期，服务器时间不同步导致 JWT 令牌提前过期，同步系统时间解决异常。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/402873.sHtML

原标题：Architecture：安全防护架构XSSCSRFSQL注入防御
简介：golang http cookie jar 会话处理，客户端 cookie jar 自动管理 cookie，处理登录态会话。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/383061.sHtML

原标题：部署复盘：静态资源版本哈希缓存策略
简介：消息队列消费堆积扩容处理，消息大量堆积时，扩容消费实例，优化消费逻辑，加快消息处理速度。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/047720.sHtML

原标题：golang 系统设计 rest 错误返回格式统一规范
简介：golang 云存储 s3 协议对象存储，go s3 客户端，兼容 minio 阿里云 oss，实现文件上传下载签名访问。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/112839.sHtML

?
