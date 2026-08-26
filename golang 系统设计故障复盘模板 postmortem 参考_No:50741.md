最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计故障复盘模板 postmortem 参考
简介：golang io.MultiReader MultiWriter 拼接流，多个 reader 拼接，多 writer 同时写入一份数据。
 | 原文链接：http://wiki.d65un2.asia/arts/343827.Doc

原标题：排错：打包后资源路径，开发生产行为不一致
简介：golang 单元测试 table‑driven，表格驱动单元测试写法，批量输入多组测试用例，简化单元测试代码。
 | 原文链接：http://wiki.d65un2.asia/arts/056959.Doc

原标题：golang 系统设计内部服务链路 trace 传递实现
简介：golang sync.RWMutex 读写锁使用场景，读多写少场景读写锁，读共享写互斥，提升并发性能。
 | 原文链接：http://wiki.d65un2.asia/arts/423466.Doc

原标题：设计思考：分布式系统时钟同步带来的架构问题
简介：axios 二次封装请求拦截处理，对 axios 做二次封装，统一请求拦截响应拦截，处理错误、token 自动刷新。
 | 原文链接：http://wiki.d65un2.asia/arts/049550.Doc

原标题：Debug：请求头过大Nginx拒绝连接报错
简介：golang http 服务并发连接数限制，自定义 listener 统计连接数量，限制最大并发连接数保护服务。
 | 原文链接：http://wiki.d65un2.asia/arts/687007.Doc

原标题：Debug：网关超时时间小于后端接口超时设置
简介：golang channel 缓冲无缓冲区别，缓冲 channel 与无缓冲 channel，底层行为差异业务选型参考。
 | 原文链接：http://wiki.d65un2.asia/arts/969744.Doc

原标题：实践：灰度流量切分简易实现方案
简介：golang kafka 消费者位移管理，理解 kafka offset，手动提交位移，保证消息消费至少一次语义。
 | 原文链接：http://wiki.d65un2.asia/arts/239526.Doc

原标题：AI‑Dev：AI辅助编码高效使用提示词技巧
简介：golang 时间戳秒毫秒纳秒转换，Unix UnixMilli UnixNano 互相转换，区分单位避免时间逻辑 bug。
 | 原文链接：http://wiki.d65un2.asia/arts/998460.Doc

原标题：项目依赖安全扫描漏洞防范
简介：golang 接口限流中间件开发，Gin 开发限流中间件，接口层实现访问频率限制，防护接口流量。
 | 原文链接：http://wiki.d65un2.asia/arts/152514.Doc

原标题：版本升级服务启动失败处理
简介：golang 处理连接被重置 reset 错误，识别 connection reset by peer，对端关闭连接异常处理逻辑。
 | 原文链接：http://wiki.d65un2.asia/arts/498747.Doc

原标题：Practice：模拟主从延迟业务兼容方案实践
简介：golang json omitempty 零值坑，omitempty 会忽略零值，区分业务是否需要输出零值字段。
 | 原文链接：http://wiki.d65un2.asia/arts/059405.Doc

原标题：避坑：Spring事务传播行为理解错误事务失效
简介：golang 本地消息表实现最终一致性，本地消息表 + 定时任务轮询，可靠消息实现分布式事务。
 | 原文链接：http://wiki.d65un2.asia/arts/059115.Doc

原标题：优化实践：读写分离分担主库查询压力
简介：Docker 多阶段构建镜像瘦身，使用 Docker 多阶段构建，剔除编译阶段依赖，产出体积更小运行镜像。
 | 原文链接：http://wiki.d65un2.asia/arts/202887.Doc

原标题：Troubleshoot：异步异常未捕获，进程悄无声息退出
简介：golang csv 百万级数据导入数据库，流式读取 csv 分批写入数据库，避免一次性加载全部数据。
 | 原文链接：http://wiki.d65un2.asia/arts/777225.Doc

原标题：golang prometheus 告警规则编写
简介：网关超时时间调优后端等待，调大网关向后端转发请求超时时间，给后端业务充足处理时间。
 | 原文链接：http://wiki.d65un2.asia/arts/121311.Doc

原标题：实战：Redis管道批量操作性能优化实践
简介：日志输出规范防止磁盘爆满，控制日志输出量，配置日志切割轮转，避免日志文件无限增长占满磁盘。
 | 原文链接：http://wiki.d65un2.asia/arts/033981.Doc

原标题：HelloMarkdown：GitHubMarkdown完整语法速查
简介：单元测试用例编写入门实操，讲解测试用例设计思路，演示基础单元测试代码，提升代码健壮性，提前发现逻辑 bug。
 | 原文链接：http://wiki.d65un2.asia/arts/087140.Doc

原标题：CLI 工具进度条交互效果开发
简介：Redis 热点 key 拆分降低集群压力，拆分访问量极高的热点 Key，分散请求压力，避免 Redis 节点压力过高。
 | 原文链接：http://wiki.d65un2.asia/arts/663103.Doc

原标题：开源项目本地运行排错完整清单
简介：golang http 服务优雅关闭完整示例，接收终止信号，停止接收新请求，等待现有请求处理完毕后退出服务。
 | 原文链接：http://wiki.d65un2.asia/arts/714849.Doc

原标题：golang consul 服务发现简单示例
简介：GitHub Markdown 文档语法汇总，整理 Markdown 常用语法，编写仓库 README、文档，提升开源项目文档排版质量。
 | 原文链接：http://wiki.d65un2.asia/arts/825505.Doc

原标题：方案设计：异步解耦业务架构边界识别
简介：调试工具断点调试变量查看技巧，演示断点设置、变量监视、调用栈查看，借助调试工具高效排查业务逻辑错误。
 | 原文链接：http://wiki.d65un2.asia/arts/999306.Doc

原标题：golang 分布式锁防死锁处理
简介：CI 流水线构建失败日志排查，阅读 CI 流水线输出日志，定位构建脚本、依赖、环境导致流水线失败问题。
 | 原文链接：http://wiki.d65un2.asia/arts/631178.Doc

原标题：开发记录：服务优雅关闭释放资源完整实现
简介：开源项目构建失败排查步骤，梳理构建报错排查流程，从依赖、网络、权限、脚本多角度定位项目构建失败原因。
 | 原文链接：http://wiki.d65un2.asia/arts/815118.Doc

原标题：HelloTest：理解集成测试基础编写思路
简介：macOS 脚本执行权限开启，给 Shell 脚本添加可执行权限，解决 macOS 下脚本无法运行权限报错。
 | 原文链接：http://wiki.d65un2.asia/arts/299923.Doc

原标题：golang k8s helm chart 简单编写
简介：数据库 utf8mb4 支持 emoji 存储，数据库字段设置 utf8mb4 字符集，完整支持 emoji 表情存储入库。
 | 原文链接：http://wiki.d65un2.asia/arts/195287.Doc

原标题：golang mysql 存储过程简单使用
简介：golang netlink 系统信息获取，netlink 获取系统网络信息，网卡地址，内核网络状态读取。
 | 原文链接：http://wiki.d65un2.asia/arts/441655.Doc

原标题：golang 工具函数库封装思路
简介：golang 分库分表简单路由实现，简易分表路由逻辑实现，根据分片 key 计算分片位置，数据路由写入。
 | 原文链接：http://wiki.d65un2.asia/arts/089093.Doc

原标题：Hands‑on：编写shell健康检查自动重启脚本
简介：rebase 操作防止代码丢失，讲解 rebase 风险点，操作前做好备份，规避错误操作造成代码提交丢失。
 | 原文链接：http://wiki.d65un2.asia/arts/746742.Doc

原标题：golang 系统设计 rest 错误返回格式统一规范
简介：golang gitlab ci go 项目流水线编写，gitlab ci 流水线执行单元测试、静态检查、构建推送镜像。
 | 原文链接：http://wiki.d65un2.asia/arts/909735.Doc

原标题：优化实践：LRU本地缓存优化热点访问性能
简介：golang tls 证书加载配置 https 服务，加载证书密钥，搭建 golang https 服务，配置 tls 版本安全策略。
 | 原文链接：http://wiki.d65un2.asia/arts/222472.Doc

原标题：golang mongodb 索引优化查询速度
简介：语义化版本依赖管理防错乱，项目依赖遵循语义版本约束，规避依赖自动升级引入不兼容变更。
 | 原文链接：http://wiki.d65un2.asia/arts/016409.Doc

原标题：安全复盘：Nginx配置不当带来的安全风险
简介：golang cgo 调用 C 语言代码示例，cgo 调用 C 函数，go 与 C 互相调用，对接 C 语言库能力。
 | 原文链接：http://wiki.d65un2.asia/arts/004755.Doc

原标题：开发记录：长连接连接管理自动清理僵死连接
简介：代码模块化组件化拆分思路，讲解代码拆分原则，将大业务拆分为独立模块组件，提升代码复用与维护能力。
 | 原文链接：http://wiki.d65un2.asia/arts/049248.Doc

原标题：新手指南：虚拟机WSL开发环境入门配置
简介：golang context 上下文传参讲解，讲解 Context 使用场景，传递元数据、控制协程超时取消，规范协程控制。
 | 原文链接：http://wiki.d65un2.asia/arts/418055.Doc

原标题：开发复盘：消息队列消息顺序性业务落地实践
简介：程序性能指标 CPU 内存监控，讲解基础性能指标含义，简单实现监控采集，初步定位程序运行性能瓶颈。
 | 原文链接：http://wiki.d65un2.asia/arts/986092.Doc

原标题：Issue：连接池参数不合理，大量连接被耗尽
简介：nestjs 权限守卫鉴权实现方案，使用 Nest 守卫实现接口鉴权，角色权限控制，拦截未授权接口访问。
 | 原文链接：http://wiki.d65un2.asia/arts/641277.Doc

原标题：Architecture：API设计RESTful最佳实践与反模式
简介：程序预加载加快服务启动速度，把高频使用资源提前预加载，减少请求阶段初始化，加快服务启动。
 | 原文链接：http://wiki.d65un2.asia/arts/992611.Doc

原标题：golang 系统设计消息可靠性投递实现
简介：golang gin 参数绑定 query form json，掌握 Gin 多种参数绑定方式，适配不同请求格式参数读取。
 | 原文链接：http://wiki.d65un2.asia/arts/658927.Doc

原标题：golang 系统设计对象池复用减少内存分配
简介：golang init 函数合理使用边界，少用 init，优先显式调用初始化，便于控制初始化时机。
 | 原文链接：http://wiki.d65un2.asia/arts/474359.Doc

原标题：golang git 提交信息规范校验
简介：golang prometheus 指标埋点开发，业务埋点计数器、仪表盘、直方图，对接 prometheus 采集监控指标。
 | 原文链接：http://wiki.d65un2.asia/arts/826395.Doc


二、踩坑排错｜Troubleshooting
原标题：Architecture：静态资源分发CDN整体架构思路
简介：golang gif 图片帧处理操作，解析 gif 图片帧，压缩、拆分 gif 动图，处理动图业务。
 | 原文链接：http://wiki.d65un2.asia/arts/739558.Doc

原标题：Fork 开源项目同步上游代码
简介：golang 项目 makefile 脚本编写，编写 Makefile 脚本，封装编译、测试、构建命令，简化项目操作。
 | 原文链接：http://wiki.d65un2.asia/arts/462811.Doc

原标题：golang 系统设计线上故障排查完整流程
简介：golang 限流器熔断降级组合使用，限流熔断降级组合架构，流量防护完整方案，保障服务稳定性。
 | 原文链接：http://wiki.d65un2.asia/arts/616269.Doc

原标题：DevOps：Docker镜像安全扫描集成CI流程
简介：vue pinia 状态管理实战教程，Pinia 完整实战示例，实现状态定义修改，模块拆分替代 Vuex。
 | 原文链接：http://wiki.d65un2.asia/arts/344721.Doc

原标题：设计思考：分布式系统时钟同步带来的架构问题
简介：express 中间件开发业务实践，开发 Express 自定义中间件，拦截请求，实现鉴权、日志记录等通用逻辑。
 | 原文链接：http://wiki.d65un2.asia/arts/385912.Doc

原标题：golang mysql 事务回滚异常处理
简介：golang context 包标准用法规范，context 传递请求元数据、超时、取消，函数第一个参数传入 ctx。
 | 原文链接：http://wiki.d65un2.asia/arts/640287.Doc

原标题：golang 系统设计 commit 提交规范约定
简介：golang testify mock 模拟接口，mock 接口生成 mock 对象，单元测试模拟外部依赖行为。
 | 原文链接：http://wiki.d65un2.asia/arts/592809.Doc

原标题：golang 系统设计消息队列 topic 设计原则梳理
简介：CLI 批量处理工具文件操作开发，开发命令行批量工具，实现批量文件处理，提升重复文件处理效率。
 | 原文链接：http://wiki.d65un2.asia/arts/466183.Doc

原标题：坑点：gitpull冲突处理不当造成代码丢失
简介：golang sql 注入风险规避要点，参数化查询杜绝 sql 注入，禁止字符串拼接 SQL 语句执行。
 | 原文链接：http://wiki.d65un2.asia/arts/591318.Doc

原标题：从零学习简单分页逻辑实现思路
简介：golang kafka 同步异步消费对比，对比 Kafka 同步消费异步消费，分析优缺点，业务选型参考。
 | 原文链接：http://wiki.d65un2.asia/arts/648013.Doc

原标题：golang redis 计数器防超卖示例
简介：WSL 搭建 Windows Linux 开发环境，配置 WSL 环境，在 Windows 系统使用 Linux 工具链，适配 Linux 开发项目。
 | 原文链接：http://wiki.d65un2.asia/arts/450745.Doc

原标题：开发环境变量配置全平台教程
简介：golang go http 静态文件禁止目录遍历，http.FileServer 防止../ 路径穿越，了解底层安全实现。
 | 原文链接：http://wiki.d65un2.asia/arts/264817.Doc

原标题：优化实践：批量操作性能优化，减少数据库IO
简介：版本升级服务启动失败处理，版本更新之后服务无法启动，对比新旧版本配置、依赖差异，完成故障修复。
 | 原文链接：http://wiki.d65un2.asia/arts/967249.Doc

原标题：nodejs 集群模式多核利用实现
简介：Nginx 缓冲区调优大文件上传，调大 Nginx 请求缓冲区，支持客户端上传大体积文件，避免上传被截断。
 | 原文链接：http://wiki.d65un2.asia/arts/749166.Doc

原标题：踩坑：消息队列消息堆积，消费者处理能力不足
简介：容器资源限制防止宿主机过载，设置容器 CPU 内存资源上限，避免单个容器耗尽宿主机全部硬件资源。
 | 原文链接：http://wiki.d65un2.asia/arts/128507.Doc

原标题：运维笔记：系统内核参数调优生产服务器
简介：golang 开发环境快速搭建指南，快速完成 Golang 开发环境配置，工具链安装，环境变量设置，准备开发。
 | 原文链接：http://wiki.d65un2.asia/arts/560600.Doc

原标题：快速上手调试工具定位简单代码错误
简介：golang prometheus client 业务埋点实操，prometheus client‑go 业务埋点，计数器、仪表盘、直方图指标开发。
 | 原文链接：http://wiki.d65un2.asia/arts/944077.Doc

原标题：golang 系统设计开源项目依赖版本升级维护
简介：golang redis 过期键监听回调，监听 key 过期事件，过期触发业务逻辑，实现过期自动处理业务场景。
 | 原文链接：http://wiki.d65un2.asia/arts/299037.Doc

原标题：项目目录结构规范化最佳实践
简介：golang redis pipeline 批量操作，使用 Redis Pipeline 批量执行多条命令，减少网络往返，提升批量操作性能。
 | 原文链接：http://wiki.d65un2.asia/arts/945843.Doc

原标题：业务错误码体系设计方案
简介：OAuth2 第三方登录服务搭建，搭建 OAuth2 服务，支持第三方账号登录，实现授权登录能力。
 | 原文链接：http://wiki.d65un2.asia/arts/041207.Doc

原标题：golang 系统设计单元测试编写原则最佳实践
简介：golang go ring 环形容器循环队列，ring 环形链表实现循环队列，环形缓冲区业务场景。
 | 原文链接：http://wiki.d65un2.asia/arts/671662.Doc

原标题：异步编程 Promise 执行流程解析
简介：golang 限流熔断放在代理层实践，代理层统一限流熔断，对后端服务做流量保护。
 | 原文链接：http://wiki.d65un2.asia/arts/943952.Doc

原标题：开发记录：批量接口请求并发控制实践
简介：golang go 容器 heap 堆实现优先队列，实现 heap 接口，构建优先队列，任务优先级调度。
 | 原文链接：http://wiki.d65un2.asia/arts/238709.Doc

原标题：golang 系统设计缓存热点 key 问题业务规避
简介：golang prometheus client 业务埋点实操，prometheus client‑go 业务埋点，计数器、仪表盘、直方图指标开发。
 | 原文链接：http://wiki.d65un2.asia/arts/600954.Doc

原标题：实战项目：WebSocket消息广播房间分组实践
简介：批量操作分批处理防止 OOM，大批量数据处理不一次性加载全部数据，分批循环处理，避免内存溢出。
 | 原文链接：http://wiki.d65un2.asia/arts/344949.Doc

原标题：调优方案：服务实例扩容，水平扩展性能
简介：GET POST 接口请求参数处理，讲解两种请求方式参数传递区别，演示参数接收、解析、校验，适配不同接口调用场景。
 | 原文链接：http://wiki.d65un2.asia/arts/881188.Doc

原标题：新手指南：项目本地编译输出产物解析
简介：golang go 容器 heap 堆实现优先队列，实现 heap 接口，构建优先队列，任务优先级调度。
 | 原文链接：http://wiki.d65un2.asia/arts/591795.Doc

原标题：golang ci 流水线单元测试集成测试
简介：golang 读写分离 gorm 实现主从切换，gorm 配置主库写入从库查询，读写分离分担数据库查询压力。
 | 原文链接：http://wiki.d65un2.asia/arts/333488.Doc

原标题：手写简易 ORM 理解对象映射
简介：依赖安装失败全方位排错，从网络、镜像源、权限、版本多角度，定位依赖安装失败，给出对应修复手段。
 | 原文链接：http://wiki.d65un2.asia/arts/414603.Doc

原标题：golang jwt 过期刷新 token 实现
简介：浏览器内存泄漏排查前端页面，梳理前端页面内存泄漏场景，讲解排查手段，修复页面内存持续上涨。
 | 原文链接：http://wiki.d65un2.asia/arts/266252.Doc

原标题：Practice：实现跨机器文件同步脚本实践
简介：golang fasthttp 客户端连接池调优，fasthttp 客户端连接池配置，复用连接提升请求性能。
 | 原文链接：http://wiki.d65un2.asia/arts/308740.Doc

原标题：项目实践：接口压测，逐步加压观察系统表现
简介：css 变量主题切换方案实现，使用 CSS 变量实现网页主题切换，多套主题样式快速切换无需大量 CSS。
 | 原文链接：http://wiki.d65un2.asia/arts/773020.Doc

原标题：golang 系统设计集成测试环境准备清理实操
简介：服务熔断防止故障级联传播，实现服务熔断逻辑，下游故障时快速失败，阻止故障向上游链式扩散。
 | 原文链接：http://wiki.d65un2.asia/arts/899242.Doc

原标题：一次数据库死锁现场分析与解决方案记录
简介：golang go 信号处理优雅重启实现，USR2 触发程序重启，不关闭监听 socket 实现零停机升级。
 | 原文链接：http://wiki.d65un2.asia/arts/024089.Doc

原标题：DNS TTL 配置域名切换生效
简介：golang json number 数字不转 float64，使用 json.Number 保留原始数字字符串，防止大数字精度丢失。
 | 原文链接：http://wiki.d65un2.asia/arts/841746.Doc

原标题：golang 系统设计 mq 故障降级业务策略
简介：golang strings 常用函数业务实战，字符串分割替换包含判断前缀后缀，掌握 strings 包高频函数。
 | 原文链接：http://wiki.d65un2.asia/arts/747374.Doc

原标题：项目构建脚本编译打包解析
简介：golang go 调度器 GMP 模型通俗讲解，拆解 GMP 模型，理解 goroutine M P 调度原理，看懂调度状态。
 | 原文链接：http://wiki.d65un2.asia/arts/302926.Doc

原标题：前端组件库按需加载性能优化
简介：golang 单例模式实现几种方式，Go 单例模式多种实现对比，sync.Once 等方式，实现全局唯一实例。
 | 原文链接：http://wiki.d65un2.asia/arts/892383.Doc

原标题：开发复盘：大JSON解析分批处理避免内存溢出
简介：golang 服务注册 etcd 简单示例，etcd 实现服务注册发现，微服务实例注册元数据，客户端发现节点。
 | 原文链接：http://wiki.d65un2.asia/arts/567226.Doc

原标题：部署实践：多实例服务部署无状态改造
简介：golang k8s 客户端 client‑go 简单示例，client‑go 操作 k8s 资源，增删改查 pod deployment 等资源对象。
 | 原文链接：http://wiki.d65un2.asia/arts/446838.Doc

三、实战开发｜Practice
原标题：架构复盘：系统扩容缩容架构无状态优先原则
简介：正则表达式优化 CPU 占满问题，优化正则表达式写法，避免回溯，防止正则运算 CPU 占用 100%。
 | 原文链接：http://wiki.d65un2.asia/arts/535386.Doc

原标题：golang mysql 联合索引最左匹配
简介：golang redis bitmap 位图业务实战，bitmap 做签到统计、用户状态标记，节省大量内存空间。
 | 原文链接：http://wiki.d65un2.asia/arts/418245.Doc

原标题：效率笔记：终端开发工具提升日常调试效率
简介：golang os 打开文件 O_APPEND O_CREATE 标志，OpenFile 标志位，控制文件创建追加截断行为。
 | 原文链接：http://wiki.d65un2.asia/arts/899923.Doc

原标题：全局异常处理器接口返回统一
简介：nodejs 全局异常捕获进程防护，捕获未捕获异常与 Promise 拒绝，尽量保护进程不因为异常直接退出。
 | 原文链接：http://wiki.d65un2.asia/arts/193152.Doc

原标题：快速上手简单的限流逻辑模拟实现
简介：golang os 进程 pid 获取父进程 pid，os.Getpid 获取进程 id，获取父进程 pid，进程间识别。
 | 原文链接：http://wiki.d65un2.asia/arts/603186.Doc

原标题：排错：前端打包chunk过大浏览器加载缓慢
简介：热更新开发环境配置教程，配置代码热重载，修改代码无需重启服务立即生效，大幅提升本地开发调试效率。
 | 原文链接：http://wiki.d65un2.asia/arts/871050.Doc

原标题：golang 系统设计 pre‑commit 钩子本地代码校验
简介：依赖版本冲突兼容修复方案，定位依赖版本冲突根源，通过版本约束、替换包，解决版本不兼容运行报错。
 | 原文链接：http://wiki.d65un2.asia/arts/098836.Doc

原标题：优化实践：内存池思想减少频繁分配释放
简介：golang go get 升级降级依赖版本，go get 指定版本升级降级依赖包，管理第三方库版本。
 | 原文链接：http://wiki.d65un2.asia/arts/078878.Doc

原标题：Hands‑on：模板渲染引擎最小原型实现
简介：golang 模板函数自定义拓展，自定义 template 模板函数，在 html 模板调用自定义逻辑处理数据。
 | 原文链接：http://wiki.d65un2.asia/arts/395797.Doc

原标题：进程线程并发基础概念讲解
简介：nodejs 内存溢出问题排查修复，Node.js 程序 OOM 排查流程，定位内存泄露，调整内存限制修复崩溃。
 | 原文链接：http://wiki.d65un2.asia/arts/426553.Doc

原标题：golang 系统设计 api 文档 swagger redoc 落地
简介：golang go math 大数高精度计算，math/big 处理超大整数、高精度浮点数，金额大数运算。
 | 原文链接：http://wiki.d65un2.asia/arts/079099.Doc

原标题：golang 系统设计 issue 模板 bug 反馈模板
简介：golang proto 可选字段处理方案，protobuf 可选字段正确判断，区分未赋值与零值，业务逻辑不出现偏差。
 | 原文链接：http://wiki.d65un2.asia/arts/387584.Doc

原标题：Practice：实现跨机器文件同步脚本实践
简介：极简 API 网关路由转发实现，开发极简网关服务，完成请求路由转发，理解网关基础实现原理。
 | 原文链接：http://wiki.d65un2.asia/arts/932386.Doc

原标题：golang redis 限流几种实现方案
简介：golang delve 远程调试 go 线上程序，delve 远程调试，线上环境附加进程调试排查线上 bug。
 | 原文链接：http://wiki.d65un2.asia/arts/196838.Doc

原标题：golang 系统设计线上问题复现思路简单讲解
简介：golang jwt 令牌刷新逻辑实现，实现 JWT 双令牌机制，access 短期有效 refresh 刷新令牌，实现无感续期登录。
 | 原文链接：http://wiki.d65un2.asia/arts/564404.Doc

原标题：线程池拒绝策略任务丢失防护
简介：golang 协程数量监控统计方案，统计运行中 goroutine 数量，监控协程泄露，协程数量异常及时告警。
 | 原文链接：http://wiki.d65un2.asia/arts/447174.Doc

原标题：网关集成鉴权限流日志一体化
简介：golang 单元测试 table‑driven，表格驱动单元测试写法，批量输入多组测试用例，简化单元测试代码。
 | 原文链接：http://wiki.d65un2.asia/arts/963194.Doc

原标题：快速入门消息队列基础概念模型
简介：代码模块化组件化拆分思路，讲解代码拆分原则，将大业务拆分为独立模块组件，提升代码复用与维护能力。
 | 原文链接：http://wiki.d65un2.asia/arts/125145.Doc

原标题：端口占用访问失败排查方案
简介：golang cpu pprof 性能分析实操，使用 pprof 采集 CPU 性能数据，定位 CPU 高占用函数，做性能优化。
 | 原文链接：http://wiki.d65un2.asia/arts/078709.Doc

原标题：golang mysql 读写分离简单实现
简介：golang go 并发模式 fan‑out fan‑in，fanout 分发任务 fanin 汇总结果，多协程并发处理任务。
 | 原文链接：http://wiki.d65un2.asia/arts/884761.Doc

原标题：Performance：数据库大表优化，冷热数据分离
简介：多套环境灵活切换配置方案，实现配置动态切换，通过环境变量、配置文件，快速切换开发测试生产环境。
 | 原文链接：http://wiki.d65un2.asia/arts/600685.Doc

原标题：踩坑：幂等键生成逻辑错误造成重复业务
简介：前端组件库按需加载性能优化，配置组件库按需引入，避免引入全部组件，减少打包产物体积。
 | 原文链接：http://wiki.d65un2.asia/arts/733175.Doc

原标题：实践：分布式事务本地模拟验证实践
简介：golang 定时任务任务持久化存储，定时任务持久化到数据库，服务重启任务不丢失，动态管理任务。
 | 原文链接：http://wiki.d65un2.asia/arts/317464.Doc

原标题：golang etcd 配置中心简单使用
简介：nodejs 脚手架工具开发完整教程，从零开发 Node 命令行脚手架，实现项目模板生成，理解 CLI 开发。
 | 原文链接：http://wiki.d65un2.asia/arts/030095.Doc

原标题：Git 分支管理多人协作实战教程
简介：golang time.After 内存泄漏场景，for 循环使用 time.After 会创建大量 timer，造成内存泄漏。
 | 原文链接：http://wiki.d65un2.asia/arts/603060.Doc

原标题：golang 系统设计滑动窗口限流代码示例
简介：golang go 爬虫 robots 协议遵守，解析 robots.txt 规则，控制爬虫抓取范围，合规采集网页数据。
 | 原文链接：http://wiki.d65un2.asia/arts/883704.Doc

原标题：复盘总结：数据库迁移升级风险评估清单
简介：GitHub 项目提交推送完整流程讲解，从仓库初始化到提交推送远程仓库，梳理全流程细节，避开新手高频错误。
 | 原文链接：http://wiki.d65un2.asia/arts/663875.Doc

原标题：golang 系统设计开源项目 release 发布流程
简介：GET POST 接口请求参数处理，讲解两种请求方式参数传递区别，演示参数接收、解析、校验，适配不同接口调用场景。
 | 原文链接：http://wiki.d65un2.asia/arts/370396.Doc

原标题：Practice：实现熔断降级组件简单原型代码
简介：缓存过期策略优化防业务故障，合理设置缓存过期策略，规避集中过期，减少缓存失效带来业务抖动。
 | 原文链接：http://wiki.d65un2.asia/arts/154778.Doc

原标题：架构笔记：多数据源架构设计事务处理难点
简介：GraphQL 接口查询优化实操，体验 GraphQL 查询方式，按需获取字段，减少冗余数据传输，优化接口请求效率。
 | 原文链接：http://wiki.d65un2.asia/arts/075337.Doc

原标题：运维笔记：系统内核参数调优生产服务器
简介：开发测试生产多环境配置区分，讲解三套环境配置分离思路，配置文件隔离，防止开发配置泄露到生产环境。
 | 原文链接：http://wiki.d65un2.asia/arts/923266.Doc

原标题：入门实践：简单错误码设计与使用规范
简介：配置外部化线上部署防错误，把配置从代码剥离，外部传入配置，修改配置不需要重新打包构建。
 | 原文链接：http://wiki.d65un2.asia/arts/100101.Doc

原标题：复盘总结：缓存改造业务落地踩坑复盘
简介：golang goroutine 泄露检测告警实现，监控 goroutine 数量，突增触发告警，提早发现协程泄露。
 | 原文链接：http://wiki.d65un2.asia/arts/614372.Doc

原标题：排错：静态资源404，打包路径配置错误
简介：golang 图片处理 go 图片裁剪压缩，golang 图像处理库，图片缩放裁剪水印，服务端图片处理。
 | 原文链接：http://wiki.d65un2.asia/arts/271612.Doc

原标题：接口签名验签完整安全方案
简介：golang 大内存分配 GC 抖动规避，避免瞬时大量对象创建，分批处理，防止 GC 抖动业务抖动。
 | 原文链接：http://wiki.d65un2.asia/arts/977463.Doc

原标题：golang 系统设计延迟队列业务实现
简介：golang http MaxHeaderBytes 限制请求头，设置 http 最大请求头大小，防止超大 header 攻击。
 | 原文链接：http://wiki.d65un2.asia/arts/471761.Doc

原标题：静态站点自动部署发布方案
简介：golang go 整洁架构代码组织实践，整洁架构依赖向内，解耦业务逻辑与外部基础设施。
 | 原文链接：http://wiki.d65un2.asia/arts/884841.Doc

原标题：golang 项目 go mod 依赖管理
简介：golang go 容器 heap 堆实现优先队列，实现 heap 接口，构建优先队列，任务优先级调度。
 | 原文链接：http://wiki.d65un2.asia/arts/898123.Doc

原标题：golang 系统设计 http 接口基准测试实操示例
简介：Nginx 丢失请求头配置修正，修复 Nginx 代理转发丢失请求头配置，保证上游服务拿到完整请求头信息。
 | 原文链接：http://wiki.d65un2.asia/arts/180995.Doc

原标题：Hands‑on：简易ID生成雪花算法完整实现
简介：golang kitex 中间件与元数据传递，kitex 自定义中间件，透传 traceId 鉴权元数据，统一处理请求。
 | 原文链接：http://wiki.d65un2.asia/arts/226846.Doc

四、架构设计｜Architecture
原标题：Redis 分布式锁高并发安全实现
简介：golang docker 镜像构建最佳实践，Go 项目 Docker 镜像构建最佳实践，减小镜像体积，安全构建。
 | 原文链接：http://wiki.d65un2.asia/arts/062210.Doc

原标题：静态博客部署 GitHub Pages 教程
简介：新手快速上手 Git 版本控制实操指南，讲解 Git 基础概念与常用命令，结合实操案例，帮助零基础用户掌握版本控制核心能力。
 | 原文链接：http://wiki.d65un2.asia/arts/088327.Doc

原标题：踩坑记录：CPU亲和配置不合理多核心负载不均
简介：CORS 跨域问题多种解决方案，对比 CORS、代理等不同跨域方案优缺点，根据业务场景选择合适的跨域处理方式。
 | 原文链接：http://wiki.d65un2.asia/arts/569172.Doc

原标题：golang 表单文件大小限制配置
简介：golang icmp ping 程序实现，go 实现 ping 工具发送 icmp 报文，检测网络连通性。
 | 原文链接：http://wiki.d65un2.asia/arts/305070.Doc

原标题：多套环境灵活切换配置方案
简介：golang proto 可选字段处理方案，protobuf 可选字段正确判断，区分未赋值与零值，业务逻辑不出现偏差。
 | 原文链接：http://wiki.d65un2.asia/arts/766761.Doc

原标题：AI‑Dev：AI辅助编码高效使用提示词技巧
简介：golang clickhouse go 客户端数据写入，clickhouse‑go 客户端写入查询，海量时序数据分析业务。
 | 原文链接：http://wiki.d65un2.asia/arts/406116.Doc

原标题：Performance：数据库大表优化，冷热数据分离
简介：程序性能指标 CPU 内存监控，讲解基础性能指标含义，简单实现监控采集，初步定位程序运行性能瓶颈。
 | 原文链接：http://wiki.d65un2.asia/arts/429805.Doc

原标题：效率笔记：GitWorkflow团队协作规范模板
简介：golang channel 通道并发处理，讲解 Channel 用法，协程之间通过通道传递数据，做并发同步控制。
 | 原文链接：http://wiki.d65un2.asia/arts/821709.Doc

原标题：monorepo 项目多包管理最佳实践
简介：golang 静态编译缩小镜像体积，Go 程序静态编译，不依赖系统库，产出单二进制文件，缩小镜像。
 | 原文链接：http://wiki.d65un2.asia/arts/937509.Doc

原标题：防火墙 IP 白名单回调接口放行
简介：golang json omitempty 零值坑，omitempty 会忽略零值，区分业务是否需要输出零值字段。
 | 原文链接：http://wiki.d65un2.asia/arts/111425.Doc

原标题：全量回归测试提升代码质量
简介：RPC 接口字段增减兼容处理，RPC 接口新增删除字段做好向前兼容，老版本服务不会解析报错崩溃。
 | 原文链接：http://wiki.d65un2.asia/arts/043692.Doc

原标题：golang pprof 线上采集性能数据
简介：golang mysql 长连接检测保活设置，配置 mysql 连接保活检测，剔除失效连接，避免拿到断开无效数据库连接。
 | 原文链接：http://wiki.d65un2.asia/arts/525775.Doc

原标题：踩坑记录：端口被占用导致服务启动失败
简介：golang grpc protobuf 开发实操，Go gRPC 开发，编写 Protobuf 定义，服务端客户端完整示例。
 | 原文链接：http://wiki.d65un2.asia/arts/871858.Doc

原标题：golang k8s 监控 prometheus 部署
简介：golang cpu pprof 性能分析实操，使用 pprof 采集 CPU 性能数据，定位 CPU 高占用函数，做性能优化。
 | 原文链接：http://wiki.d65un2.asia/arts/426036.Doc

原标题：Nginx 丢失请求头配置修正
简介：Docker 网络模式容器互通设置，选择合适 Docker 网络模式，实现容器之间网络互相访问通信。
 | 原文链接：http://wiki.d65un2.asia/arts/933867.Doc

原标题：golang 系统设计配置回滚版本历史记录实现
简介：golang go json 序列化自定义字段，json 标签控制字段名称、忽略字段、omitempty 空值忽略。
 | 原文链接：http://wiki.d65un2.asia/arts/990989.Doc

原标题：性能复盘：锁粒度太大，拆分细粒度锁优化
简介：多操作系统开发兼容处理，解决不同系统路径、换行符、权限差异，保证项目跨平台正常运行。
 | 原文链接：http://wiki.d65un2.asia/arts/189811.Doc

原标题：golang 系统设计开源版本发布 changelog 维护
简介：golang sync.Map 高并发 map 使用场景，sync.Map 适用场景，读写实操，对比普通 map 加锁性能差异。
 | 原文链接：http://wiki.d65un2.asia/arts/229068.Doc

?
