最新前沿技术资讯

一、入门教程｜Getting Started
原标题：快速入门gRPC基础概念与简单示例
简介：golang 路径处理 filepath 包规范写法，使用 filepath 处理路径拼接分割，自动适配操作系统路径分隔符。
 | 原文链接：http://book.cotmkf.asia/blog/677181.Doc

原标题：数据库连接及时关闭连接泄漏
简介：golang 容器信号转发处理问题修复，docker/k8s 正确转发 SIGTERM 信号，保证 go 程序收到信号优雅退出。
 | 原文链接：http://book.cotmkf.asia/blog/005148.Doc

原标题：golang 系统设计 webhook 回调处理架构
简介：分布式 ID 生成器高并发实现，实现高性能分布式 ID 生成器，适配高并发业务，生成全局唯一 ID。
 | 原文链接：http://book.cotmkf.asia/blog/801045.Doc

原标题：手写简易 RPC 服务通信原型
简介：对象存储上传下载权限实操，演示对象存储文件上传、下载、访问权限设置，适配业务文件存储场景。
 | 原文链接：http://book.cotmkf.asia/blog/459151.Doc

原标题：记一次字符集编码不一致乱码问题全排查
简介：日志输出规范防止磁盘爆满，控制日志输出量，配置日志切割轮转，避免日志文件无限增长占满磁盘。
 | 原文链接：http://book.cotmkf.asia/blog/556010.Doc

原标题：限流规则误拦截正常请求修复
简介：golang json omitempty 零值坑，omitempty 会忽略零值，区分业务是否需要输出零值字段。
 | 原文链接：http://book.cotmkf.asia/blog/188027.Doc

原标题：复盘总结：微服务改造踩坑经验总结记录
简介：golang systemd 配置 go 服务部署，编写 systemd unit 文件管理 go 服务，开机自启、崩溃自动重启。
 | 原文链接：http://book.cotmkf.asia/blog/425194.Doc

原标题：golang 信号量控制并发数量
简介：磁盘 inode 耗尽文件创建失败，排查磁盘 inode 占用，清理大量小文件，恢复文件创建能力。
 | 原文链接：http://book.cotmkf.asia/blog/747331.Doc

原标题：Practice：实现熔断降级组件简单原型代码
简介：golang crypto 密码学最佳实践，go crypto 包加密签名，规避不安全算法，使用安全密码套件。
 | 原文链接：http://book.cotmkf.asia/blog/673527.Doc

原标题：新手参与开源社区贡献指南
简介：内存泄漏定位分析完整流程，分享内存泄漏排查步骤，定位没有释放的对象，解决内存持续上涨问题。
 | 原文链接：http://book.cotmkf.asia/blog/988079.Doc

原标题：golang 系统设计灰度发布实现思路
简介：nodejs http 服务性能调优实战，调优 Node HTTP 服务内核参数，连接复用，提升接口并发处理能力。
 | 原文链接：http://book.cotmkf.asia/blog/449203.Doc

原标题：Performance：数据库分表解决单表过大性能衰减
简介：数据库死锁成因规避方案，讲解数据库死锁产生条件，给出业务层面规避手段，减少死锁事件发生。
 | 原文链接：http://book.cotmkf.asia/blog/908105.Doc

原标题：golang ci 流水线制品仓库上传下载
简介：接口限流逻辑简单模拟实现，编写简易限流逻辑，限制接口访问频次，保护服务，避免短时间大量请求压垮系统。
 | 原文链接：http://book.cotmkf.asia/blog/120219.Doc

原标题：golang 信号捕获程序退出处理
简介：OpenAPI 自动接口文档生成，集成 OpenAPI 工具，自动扫描代码生成接口文档，减少文档维护成本。
 | 原文链接：http://book.cotmkf.asia/blog/048134.Doc

原标题：优化实践：读写分离分担主库查询压力
简介：golang go 程序守护进程实现思路，go 程序不做 daemon 化，依靠 systemd pm2 k8s 实现进程守护。
 | 原文链接：http://book.cotmkf.asia/blog/645007.Doc

原标题：性能复盘：消息队列大量小消息性能问题优化
简介：消息队列重复消费业务处理，实现消息消费幂等，处理重复投递消息，保证多次消费业务结果一致。
 | 原文链接：http://book.cotmkf.asia/blog/161371.Doc

原标题：golang 系统设计内部服务契约测试简单思路
简介：golang dns 自定义解析器实现，自定义 dns 解析，指定 dns 服务器，控制域名解析逻辑，适配内网环境。
 | 原文链接：http://book.cotmkf.asia/blog/741007.Doc

原标题：golang minio 预签名 url 临时访问
简介：Redis 分布式锁高并发安全实现，基于 Redis 实现分布式锁，处理锁过期、续期，保障集群并发安全。
 | 原文链接：http://book.cotmkf.asia/blog/975211.Doc

原标题：部署实践：Nginx反向代理传递真实客户端IP
简介：GraphQL 接口查询优化实操，体验 GraphQL 查询方式，按需获取字段，减少冗余数据传输，优化接口请求效率。
 | 原文链接：http://book.cotmkf.asia/blog/837333.Doc

原标题：调优方案：前端静态资源打包性能体积优化
简介：golang csv 读写批量数据处理，Go 读写 CSV 文件，批量导入导出业务数据，处理 CSV 格式解析。
 | 原文链接：http://book.cotmkf.asia/blog/886034.Doc

原标题：golang 系统设计最小权限原则落地实践
简介：限流窗口绕过漏洞修复方案，修复限流时间窗口漏洞，避免攻击者绕过限流规则，保障接口防护有效。
 | 原文链接：http://book.cotmkf.asia/blog/296844.Doc

原标题：HelloShell：入门常用shell脚本编写
简介：express 中间件开发业务实践，开发 Express 自定义中间件，拦截请求，实现鉴权、日志记录等通用逻辑。
 | 原文链接：http://book.cotmkf.asia/blog/567493.Doc

原标题：nodejs 信号处理优雅关闭服务
简介：golang gin 获取客户端真实 IP，多层代理场景正确拿到用户真实访问 IP，避免拿到网关代理内网地址。
 | 原文链接：http://book.cotmkf.asia/blog/497699.Doc

原标题：新手指南：读懂项目构建脚本作用
简介：Cookie 跨环境登录配置调整，调整 Cookie 域、Secure 属性，适配开发测试生产环境，修复登录失效。
 | 原文链接：http://book.cotmkf.asia/blog/011871.Doc

原标题：CLI 批量处理工具文件操作开发
简介：Redis 热点 key 拆分降低集群压力，拆分访问量极高的热点 Key，分散请求压力，避免 Redis 节点压力过高。
 | 原文链接：http://book.cotmkf.asia/blog/124182.Doc

原标题：vite 项目配置与构建提速技巧
简介：golang go 输入数据校验防御，所有外部入参严格校验长度格式，防止恶意输入造成业务异常。
 | 原文链接：http://book.cotmkf.asia/blog/523461.Doc

原标题：坑点：Git仓库过大，clone速度极慢解决方案
简介：golang go 调度器 GMP 模型通俗讲解，拆解 GMP 模型，理解 goroutine M P 调度原理，看懂调度状态。
 | 原文链接：http://book.cotmkf.asia/blog/084977.Doc

原标题：golang 系统设计 tcp 三次握手四次挥手梳理
简介：手写简易 MQ 理解消息存储消费，手写极简消息队列 Demo，理解消息存储、投递、消费完整流程。
 | 原文链接：http://book.cotmkf.asia/blog/890499.Doc

原标题：golang 系统设计日志系统架构思路
简介：golang select 随机分支执行特性，多个 channel 就绪 select 随机选择，理解 select 行为特性。
 | 原文链接：http://book.cotmkf.asia/blog/075276.Doc

原标题：golang 系统设计内存复用 sync.pool 使用
简介：golang 分表跨表 join 查询处理方案，分表后跨分片关联查询解决方案，业务层聚合代替数据库 join。
 | 原文链接：http://book.cotmkf.asia/blog/504017.Doc

原标题：golang 系统设计延迟队列业务实现
简介：程序预加载加快服务启动速度，把高频使用资源提前预加载，减少请求阶段初始化，加快服务启动。
 | 原文链接：http://book.cotmkf.asia/blog/756061.Doc

原标题：ORM 框架数据库增删改查实操
简介：golang grpc 客户端拦截器封装，grpc 客户端拦截器实现请求统一签名、重试、链路信息透传。
 | 原文链接：http://book.cotmkf.asia/blog/771338.Doc

原标题：排错：容器OOM被杀死，日志看不到任何输出
简介：文件描述符优化进程卡死修复，及时关闭文件句柄，控制打开文件数量，解决文件句柄耗尽进程卡死。
 | 原文链接：http://book.cotmkf.asia/blog/053991.Doc

原标题：实践：API错误统一捕获与告警通知实践
简介：golang go 调度器 GMP 模型通俗讲解，拆解 GMP 模型，理解 goroutine M P 调度原理，看懂调度状态。
 | 原文链接：http://book.cotmkf.asia/blog/677324.Doc

原标题：安全实践：最小权限原则数据库账号管控
简介：nodejs 定时任务生产环境避坑，Node 定时任务线上踩坑汇总，集群重复执行、任务阻塞等问题解决方案。
 | 原文链接：http://book.cotmkf.asia/blog/799172.Doc

原标题：golang 系统设计限流熔断降级组合使用
简介：golang jaeger 链路追踪部署对接，jaeger 接收 opentelemetry 链路数据，可视化完整调用链路。
 | 原文链接：http://book.cotmkf.asia/blog/578764.Doc

原标题：实战项目：WSL开发环境完整配置实操
简介：golang benchmark 减少测试干扰，benchmark 执行循环 b.N，避免循环内部做非被测逻辑干扰结果。
 | 原文链接：http://book.cotmkf.asia/blog/048210.Doc

原标题：设计思考：分布式ID系统架构选型对比
简介：golang redis stream 消息队列实战，redis stream 实现可靠消息队列，消费组、ack 确认，消息不丢失。
 | 原文链接：http://book.cotmkf.asia/blog/089688.Doc

原标题：Troubleshooting：Redis大key引发集群卡顿
简介：看懂报错日志快速定位问题，讲解日志阅读方法，解析堆栈信息含义，学会从报错信息中定位代码出错位置。
 | 原文链接：http://book.cotmkf.asia/blog/693989.Doc

原标题：线程调度优化减少上下文切换
简介：golang 信号量控制并发数量，使用信号量控制并发，限制同时执行任务数量，保护下游资源。
 | 原文链接：http://book.cotmkf.asia/blog/412786.Doc


二、踩坑排错｜Troubleshooting
原标题：排错：HTTPS证书过期导致接口调用失败
简介：golang interface 接口使用避坑，interface 判 nil 坑点，理解接口底层结构，避免判空逻辑失效。
 | 原文链接：http://book.cotmkf.asia/blog/676309.Doc

原标题：golang 错误包装 errors.wrap 用法
简介：golang 空接口 interface {} 类型处理，interface {} 存储任意类型，类型转换，处理泛型之前通用数据。
 | 原文链接：http://book.cotmkf.asia/blog/231640.Doc

原标题：golang 系统设计分布式任务调度
简介：环境变量不生效问题修复，排查环境变量加载顺序、作用域问题，修复环境变量读取不到的异常。
 | 原文链接：http://book.cotmkf.asia/blog/350639.Doc

原标题：优化实践：LRU本地缓存优化热点访问性能
简介：golang os 文件目录操作大全，文件创建删除重命名，目录遍历，文件信息读取，完成各类文件系统操作。
 | 原文链接：http://book.cotmkf.asia/blog/291090.Doc

原标题：架构复盘：多实例部署业务状态无状态改造
简介：golang 日志输出 stdout 标准输出规范，容器环境日志输出到 stdout，由容器平台统一采集日志文件。
 | 原文链接：http://book.cotmkf.asia/blog/719153.Doc

原标题：实战项目：实现分布式任务调度最小原型
简介：golang 容器健康检查接口开发，Go 开发 HTTP 健康接口，供容器编排工具探测实例存活状态。
 | 原文链接：http://book.cotmkf.asia/blog/277372.Doc

原标题：性能笔记：磁盘IO过高业务优化手段
简介：golang strings.Builder 字符串高效拼接，strings.Builder 做字符串拼接，比 += 性能更高，减少内存拷贝。
 | 原文链接：http://book.cotmkf.asia/blog/742191.Doc

原标题：golang k8s 镜像拉取密钥配置
简介：golang go 锁竞争导致 CPU 飙升，识别锁竞争场景，减少锁粒度，优化并发逻辑降低 CPU 开销。
 | 原文链接：http://book.cotmkf.asia/blog/641305.Doc

原标题：开发生产环境资源路径统一
简介：golang go 网络编程 net 包基础，net 包 tcp udp socket 编程，监听接收连接，读写数据。
 | 原文链接：http://book.cotmkf.asia/blog/045858.Doc

原标题：从零编写简易 CLI 命令行工具
简介：golang go 零停机升级实践要点，socket 继承，流量无损，旧连接处理完毕后旧进程退出。
 | 原文链接：http://book.cotmkf.asia/blog/633128.Doc

原标题：踩坑：幂等键生成逻辑错误造成重复业务
简介：简易网关请求路由过滤模拟，模拟网关基础能力，实现请求路由转发、简单过滤，理解网关核心工作逻辑。
 | 原文链接：http://book.cotmkf.asia/blog/781012.Doc

原标题：golang 系统设计配置本地缓存降级策略方案
简介：golang 系统 IO 阻塞 goroutine 场景，理解系统调用阻塞 M，P 会调度其他 M，掌握 go 调度行为。
 | 原文链接：http://book.cotmkf.asia/blog/602488.Doc

原标题：Debug：时间回拨，定时任务调度逻辑错乱
简介：golang context.WithCancel 手动取消上下文，WithCancel 生成可取消 ctx，手动调用 cancel 触发取消。
 | 原文链接：http://book.cotmkf.asia/blog/019814.Doc

原标题：DevOps：多阶段构建Dockerfile最佳实践
简介：golang bufio.Scanner 缓冲区调大，Scanner 默认缓冲区大小不够，读取超长行需要扩大缓冲区。
 | 原文链接：http://book.cotmkf.asia/blog/020035.Doc

原标题：golang 系统设计依赖版本升级风险评估
简介：golang os 文件目录操作大全，文件创建删除重命名，目录遍历，文件信息读取，完成各类文件系统操作。
 | 原文链接：http://book.cotmkf.asia/blog/042955.Doc

原标题：golang 系统设计网关灰度流量切分简单方案
简介：axios 二次封装请求拦截处理，对 axios 做二次封装，统一请求拦截响应拦截，处理错误、token 自动刷新。
 | 原文链接：http://book.cotmkf.asia/blog/088079.Doc

原标题：开发复盘：内存缓存LRU淘汰策略实现实践
简介：golang 容器内读取 k8s 配置 configmap，程序读取 k8s configmap 配置，配置与镜像分离便于运维。
 | 原文链接：http://book.cotmkf.asia/blog/042237.Doc

原标题：OpenAPI 自动接口文档生成
简介：golang go 并发模式 errgroup 使用，errgroup 结合 context，协程组，任意协程出错整体取消任务。
 | 原文链接：http://book.cotmkf.asia/blog/984623.Doc

原标题：运维笔记：服务器Swap分区调优生产实践
简介：golang panic 崩溃日志完整收集，捕获所有 panic，打印堆栈，记录日志，方便定位崩溃根源。
 | 原文链接：http://book.cotmkf.asia/blog/649598.Doc

原标题：Hands‑on：编写shell健康检查自动重启脚本
简介：golang http client Transport 参数调优，Transport 最大连接空闲连接，TLS 配置，http 客户端调优。
 | 原文链接：http://book.cotmkf.asia/blog/520763.Doc

原标题：golang github actions 缓存依赖提速
简介：golang os 环境变量读取设置，os.Getenv os.Setenv os.Unsetenv 读写环境变量，环境变量多值处理。
 | 原文链接：http://book.cotmkf.asia/blog/030434.Doc

原标题：DevOps：环境配置管理区分开发测试生产
简介：配置外部化线上部署防错误，把配置从代码剥离，外部传入配置，修改配置不需要重新打包构建。
 | 原文链接：http://book.cotmkf.asia/blog/487993.Doc

原标题：Debug：Websocket频繁断开重连根因分析
简介：golang uuid 生成多种版本实现，生成 uuid v1 v4，生成唯一标识，业务用于单据编号场景。
 | 原文链接：http://book.cotmkf.asia/blog/350977.Doc

原标题：golang 系统设计锁优化减少竞争提升吞吐
简介：golang hystrix 模式简易熔断实现，简易熔断组件，错误率达到阈值触发熔断，快速失败保护下游。
 | 原文链接：http://book.cotmkf.asia/blog/967473.Doc

原标题：架构笔记：WebSocket大规模连接服务架构
简介：缓存过期打散防止缓存雪崩，对缓存过期时间增加随机偏移，避免大量缓存同时失效引发缓存雪崩。
 | 原文链接：http://book.cotmkf.asia/blog/067188.Doc

原标题：Troubleshooting：依赖安装失败完整排查清单
简介：golang rate 令牌桶限流器源码理解，拆解令牌桶限流核心逻辑，理解令牌生成消耗，掌握限流底层原理。
 | 原文链接：http://book.cotmkf.asia/blog/999557.Doc

原标题：golang url 参数编码处理方案
简介：golang http 重定向策略自定义，CheckRedirect 自定义重定向逻辑，限制重定向次数，防止死循环。
 | 原文链接：http://book.cotmkf.asia/blog/130663.Doc

原标题：golang 系统设计滑动窗口限流代码示例
简介：请求工具封装统一异常处理，对网络请求做二次封装，统一捕获各类请求异常，标准化接口返回格式。
 | 原文链接：http://book.cotmkf.asia/blog/022667.Doc

原标题：Architecture：静态配置与动态配置架构分离
简介：CI 流水线超时时间延长配置，调大 CI 任务超时阈值，解决构建任务耗时较长被流水线强制终止。
 | 原文链接：http://book.cotmkf.asia/blog/673753.Doc

原标题：项目实践：幂等表实现接口幂等业务实践
简介：golang gin 参数绑定 query form json，掌握 Gin 多种参数绑定方式，适配不同请求格式参数读取。
 | 原文链接：http://book.cotmkf.asia/blog/857399.Doc

原标题：golang 系统设计配置多环境隔离方案落地
简介：静态资源 404 路径打包修复，修复打包后静态资源访问 404，调整资源输出路径，保证资源正常加载。
 | 原文链接：http://book.cotmkf.asia/blog/493446.Doc

原标题：golang 系统设计内部服务 mock 集成测试方案
简介：代理 HTTPS 证书访问异常处理，配置代理根证书，解决代理环境 HTTPS 证书校验失败无法访问外网。
 | 原文链接：http://book.cotmkf.asia/blog/523737.Doc

原标题：API 大版本不兼容平滑迁移
简介：服务启动依赖顺序配置正确，配置服务启动依赖关系，保证依赖服务就绪之后再启动当前业务服务。
 | 原文链接：http://book.cotmkf.asia/blog/938151.Doc

原标题：golang gitlab ci 配置自动构建镜像
简介：golang go 程序容器资源 requests limits，设置容器 cpu 内存配额，防止实例抢占集群资源，稳定调度。
 | 原文链接：http://book.cotmkf.asia/blog/127528.Doc

原标题：方案设计：高可用Redis集群架构选型对比
简介：日志驱动异常日志不输出修复，排查日志驱动配置，修复日志写入配置，恢复程序正常日志输出。
 | 原文链接：http://book.cotmkf.asia/blog/822657.Doc

原标题：避坑：ORM框架隐式查询产生大量慢SQL
简介：golang 分表跨表 join 查询处理方案，分表后跨分片关联查询解决方案，业务层聚合代替数据库 join。
 | 原文链接：http://book.cotmkf.asia/blog/305416.Doc

原标题：golang 系统设计单元测试 mock 外部依赖技巧
简介：版本升级服务启动失败处理，版本更新之后服务无法启动，对比新旧版本配置、依赖差异，完成故障修复。
 | 原文链接：http://book.cotmkf.asia/blog/564241.Doc

原标题：ServiceWorker 缓存页面更新清理
简介：golang go 爬虫 robots 协议遵守，解析 robots.txt 规则，控制爬虫抓取范围，合规采集网页数据。
 | 原文链接：http://book.cotmkf.asia/blog/529680.Doc

原标题：架构笔记：分库分表中间件选型业务约束
简介：单元测试用例编写入门实操，讲解测试用例设计思路，演示基础单元测试代码，提升代码健壮性，提前发现逻辑 bug。
 | 原文链接：http://book.cotmkf.asia/blog/396559.Doc

原标题：避坑：版本升级之后项目直接无法启动
简介：Nginx 透传真实客户端 IP 配置，配置 Nginx 把真实客户端 IP 传递后端服务，后端拿到访问者真实 IP。
 | 原文链接：http://book.cotmkf.asia/blog/422219.Doc

三、实战开发｜Practice
原标题：实战：Redis管道批量操作性能优化实践
简介：正则表达式优化 CPU 占满问题，优化正则表达式写法，避免回溯，防止正则运算 CPU 占用 100%。
 | 原文链接：http://book.cotmkf.asia/blog/889097.Doc

原标题：效率笔记：gitlog高效查询历史提交技巧
简介：golang proto 默认值坑点梳理，梳理 Protobuf 默认值坑，零值字段区分未赋值，避免业务逻辑错误。
 | 原文链接：http://book.cotmkf.asia/blog/235943.Doc

原标题：线上故障：慢查询拖垮整个数据库服务
简介：golang grpc 客户端拦截器封装，grpc 客户端拦截器实现请求统一签名、重试、链路信息透传。
 | 原文链接：http://book.cotmkf.asia/blog/241732.Doc

原标题：架构复盘：RPC框架架构超时重试设计要点
简介：序列化版本不一致解析失败，保证序列化对象版本对齐，修复版本不匹配导致对象反序列化失败。
 | 原文链接：http://book.cotmkf.asia/blog/266914.Doc

原标题：golang k8s ingress‑nginx 配置 ssl 证书
简介：轻量 API 后端接口服务快速开发，快速搭建简易 API 服务，实现基础接口能力，快速支撑小型业务需求。
 | 原文链接：http://book.cotmkf.asia/blog/836304.Doc

原标题：golang 系统设计开发环境本地调试最佳实践
简介：WebSocket 双向通信 demo 开发，搭建简易 WebSocket 服务，实现客户端服务端双向消息推送，理解实时通信原理。
 | 原文链接：http://book.cotmkf.asia/blog/900302.Doc

原标题：实战项目：容器健康探针配置完整实践示例
简介：全平台系统环境变量配置，汇总多操作系统环境变量配置方法，统一项目读取逻辑，适配不同运行平台。
 | 原文链接：http://book.cotmkf.asia/blog/770608.Doc

原标题：运维笔记：系统内核参数调优生产服务器
简介：接口限流逻辑简单模拟实现，编写简易限流逻辑，限制接口访问频次，保护服务，避免短时间大量请求压垮系统。
 | 原文链接：http://book.cotmkf.asia/blog/120509.Doc

原标题：极简 API 网关路由转发实现
简介：内网 DNS 不稳定随机报错排查，定位内网 DNS 抖动问题，配置备选 DNS，解决偶现域名解析失败。
 | 原文链接：http://book.cotmkf.asia/blog/222556.Doc

原标题：排错：静态资源404，打包路径配置错误
简介：golang html 模板渲染简单示例，Go HTML 模板渲染，服务端渲染页面，填充数据输出 HTML 页面。
 | 原文链接：http://book.cotmkf.asia/blog/683381.Doc

原标题：踩坑：环境变量未生效导致线上配置错乱
简介：golang json omitempty 零值坑，omitempty 会忽略零值，区分业务是否需要输出零值字段。
 | 原文链接：http://book.cotmkf.asia/blog/775247.Doc

原标题：Practice：模拟磁盘满，验证服务降级表现
简介：golang os.Exit 退出程序注意 defer 不执行，os.Exit 会直接退出，不会执行 defer，优雅退出不要直接 os.Exit。
 | 原文链接：http://book.cotmkf.asia/blog/423617.Doc

原标题：golang 系统设计 vscode go 插件调试配置实操
简介：Git 误提交撤销回退实操教程，演示多种撤销提交方式，区分已经推送远程和本地未提交场景，处理误提交代码。
 | 原文链接：http://book.cotmkf.asia/blog/743023.Doc

原标题：golang etcd 配置中心简单使用
简介：golang kafka 消费者位移管理，理解 kafka offset，手动提交位移，保证消息消费至少一次语义。
 | 原文链接：http://book.cotmkf.asia/blog/015155.Doc

原标题：YAML 配置文件语法快速上手
简介：golang websocket 服务端开发，Go 实现 WebSocket 服务端，处理连接、消息收发，实现长连接服务。
 | 原文链接：http://book.cotmkf.asia/blog/415407.Doc

原标题：线上异常：布隆过滤器误判造成业务逻辑异常
简介：nodejs 脚手架工具开发完整教程，从零开发 Node 命令行脚手架，实现项目模板生成，理解 CLI 开发。
 | 原文链接：http://book.cotmkf.asia/blog/963359.Doc

原标题：避坑：ORM框架隐式查询产生大量慢SQL
简介：golang go‑zero 监控指标埋点，go‑zero 内置 metrics 监控，上报业务指标对接监控平台。
 | 原文链接：http://book.cotmkf.asia/blog/455513.Doc

原标题：新手参与开源社区贡献指南
简介：golang 响应 body 流式返回大数据，http 流式输出数据，边生成边返回，无需在内存组装完整返回结果。
 | 原文链接：http://book.cotmkf.asia/blog/563987.Doc

原标题：图片上传预览格式大小处理
简介：本地运行正常线上报错排查，对比本地与线上环境差异，从配置、系统版本、文件权限定位线上独有的 bug。
 | 原文链接：http://book.cotmkf.asia/blog/306691.Doc

原标题：快速上手单元测试，写出第一个测试用例
简介：golang race 检测器性能开销，race 检测器有性能损耗，只用于测试环境，禁止生产开启 race。
 | 原文链接：http://book.cotmkf.asia/blog/673314.Doc

原标题：Practice：数据库分表简单实现方案与代码示例
简介：短信服务封装失败自动重试，封装短信发送组件，处理发送失败自动重试，兼容多短信服务商。
 | 原文链接：http://book.cotmkf.asia/blog/369246.Doc

原标题：快速入门对象存储基础使用场景
简介：golang go 模板缓存预编译模板，预编译 html 模板，程序启动加载，避免每次请求解析模板损耗性能。
 | 原文链接：http://book.cotmkf.asia/blog/567004.Doc

原标题：WSL 文件权限访问异常修复
简介：文件批量导入导出功能实现，开发批量导入导出接口，处理大量文件数据，完成业务数据批量迁移与导出。
 | 原文链接：http://book.cotmkf.asia/blog/071472.Doc

原标题：golang 系统设计压测工具 vegeta 使用示例
简介：golang go 爬虫代理池轮换使用，http 代理池轮换，请求自动切换代理 IP，突破访问限制。
 | 原文链接：http://book.cotmkf.asia/blog/939936.Doc

原标题：golang 系统设计全局异常处理器实现
简介：golang lru 缓存淘汰算法编写，手写 LRU 缓存淘汰算法，实现本地缓存，淘汰最久未使用数据。
 | 原文链接：http://book.cotmkf.asia/blog/154780.Doc

原标题：内网 DNS 不稳定随机报错排查
简介：SourceMap 生成线上报错定位，项目打包生成 SourceMap 文件，线上报错可以还原源码，快速定位报错位置。
 | 原文链接：http://book.cotmkf.asia/blog/082871.Doc

原标题：坑点：软链接权限问题容器读取文件失败
简介：golang go 并发模式 or‑channel 信号合并，合并多个 done 信号，任意一个完成触发退出逻辑。
 | 原文链接：http://book.cotmkf.asia/blog/926959.Doc

原标题：golang k8s 节点污点容忍度配置
简介：nodejs 单元测试 jest 实操教程，Jest 单元测试实操，编写测试用例，mock 依赖，验证业务逻辑正确性。
 | 原文链接：http://book.cotmkf.asia/blog/522151.Doc

原标题：golang k8s pod 优雅关闭流程讲解
简介：golang 单元测试 table‑driven，表格驱动单元测试写法，批量输入多组测试用例，简化单元测试代码。
 | 原文链接：http://book.cotmkf.asia/blog/663480.Doc

原标题：数据库读写分离性能优化
简介：Shell 脚本自动化命令编写，讲解 Shell 基础语法，编写自动化脚本，完成批量执行、文件处理，解放重复手工操作。
 | 原文链接：http://book.cotmkf.asia/blog/052515.Doc

原标题：Issue复现：内存泄漏定位完整复盘记录
简介：golang 内存 pprof 定位内存泄漏，pprof 分析内存快照，定位内存泄露对象，解决 Go 程序内存持续上涨。
 | 原文链接：http://book.cotmkf.asia/blog/020199.Doc

原标题：golang 系统设计 protobuf oneof 类型业务场景
简介：环境变量不生效问题修复，排查环境变量加载顺序、作用域问题，修复环境变量读取不到的异常。
 | 原文链接：http://book.cotmkf.asia/blog/360842.Doc

原标题：golang 系统设计配置中心核心能力梳理讲解
简介：golang time.Ticker 泄漏常见场景，忘记 Stop Ticker，导致协程泄漏，定时器资源无法释放。
 | 原文链接：http://book.cotmkf.asia/blog/940710.Doc

原标题：golang es 查询语句 DSL 实操
简介：golang jwt 鉴权中间件完整示例，Gin JWT 鉴权中间件，令牌校验，解析用户信息，接口鉴权拦截。
 | 原文链接：http://book.cotmkf.asia/blog/746958.Doc

原标题：golang k8s cronjob 定时任务配置
简介：GC 垃圾回收优化降低 CPU 占用，调整 GC 参数，优化对象创建销毁，降低垃圾回收带来 CPU 开销。
 | 原文链接：http://book.cotmkf.asia/blog/155340.Doc

原标题：golang 系统设计接口频率限制业务落地
简介：golang os 环境变量读取设置，os.Getenv os.Setenv os.Unsetenv 读写环境变量，环境变量多值处理。
 | 原文链接：http://book.cotmkf.asia/blog/700646.Doc

原标题：快速上手简单性能监控指标查看
简介：Git 误删提交代码恢复找回，使用 Git reflog 工具找回被误删除提交记录，恢复误删除代码。
 | 原文链接：http://book.cotmkf.asia/blog/349691.Doc

原标题：Debug：并发场景下数据覆盖丢失问题定位
简介：重复提交幂等防护再次讲解，梳理前端重复点击、网络重试场景，落地接口幂等，杜绝重复业务。
 | 原文链接：http://book.cotmkf.asia/blog/975705.Doc

原标题：Troubleshooting：K8sPodOOMKilled完整排查流程
简介：golang gorm 子查询嵌套查询写法，Gorm 实现子查询、嵌套查询，复杂条件查询简化代码编写。
 | 原文链接：http://book.cotmkf.asia/blog/885288.Doc

原标题：Security：密码存储哈希加盐最佳实践
简介：golang goroutine 泄露常见场景汇总，channel 阻塞、context 忘记取消，导致协程无法退出发生泄露。
 | 原文链接：http://book.cotmkf.asia/blog/427728.Doc

四、架构设计｜Architecture
原标题：布隆过滤器误判问题修正
简介：静态网页 HTML CSS 快速入门实战，通过简单页面案例讲解标签、样式布局，从零编写页面，理解网页基础渲染原理。
 | 原文链接：http://book.cotmkf.asia/blog/683262.Doc

原标题：HelloGitHubPages：部署你的第一个静态博客
简介：golang 优雅处理 http 重定向逻辑，自定义控制 http 重定向跳转次数，防止无限重定向死循环。
 | 原文链接：http://book.cotmkf.asia/blog/699493.Doc

原标题：网络读取超时设置连接挂起防护
简介：golang go mod graph 可视化依赖图，可视化 go 依赖关系，直观看到包之间依赖，定位冲突。
 | 原文链接：http://book.cotmkf.asia/blog/320466.Doc

原标题：golang 系统设计网关 ssl 证书配置更新实操
简介：golang 集成测试测试数据库回滚，集成测试结束自动回滚数据库，不污染测试环境数据。
 | 原文链接：http://book.cotmkf.asia/blog/424241.Doc

原标题：golang 系统设计回调签名校验防伪造实现
简介：golang go 版本管理 go install 安装工具，go install 安装指定版本 go 工具，管理本地 go 工具版本。
 | 原文链接：http://book.cotmkf.asia/blog/340744.Doc

原标题：多操作系统开发兼容处理
简介：golang excel 大文件读取流式解析，流式读取大 excel 文件，逐行解析数据，不加载全部内容进内存。
 | 原文链接：http://book.cotmkf.asia/blog/453549.Doc

原标题：请求重试组件退避策略实现
简介：前端打包分包加载提速方案，前端打包做代码分包，拆分大 bundle，页面按需加载，提升首屏加载速度。
 | 原文链接：http://book.cotmkf.asia/blog/228542.Doc

原标题：Practice：实现定时任务动态启停管理接口
简介：游标分页大数据查询性能提升，使用游标分页替代偏移分页，解决大数据 offset 分页性能越来越差问题。
 | 原文链接：http://book.cotmkf.asia/blog/188227.Doc

原标题：优化实践：LRU本地缓存优化热点访问性能
简介：golang nil channel 阻塞特性，nil channel 读写永久阻塞，理解 nil channel 行为做逻辑控制。
 | 原文链接：http://book.cotmkf.asia/blog/619813.Doc

原标题：golang redis 过期策略内存淘汰
简介：vite 插件开发自定义构建逻辑，开发自定义 vite 插件，介入构建生命周期，实现项目个性化构建逻辑。
 | 原文链接：http://book.cotmkf.asia/blog/425550.Doc

原标题：nestjs 框架模块化项目搭建
简介：Docker 网络模式容器互通设置，选择合适 Docker 网络模式，实现容器之间网络互相访问通信。
 | 原文链接：http://book.cotmkf.asia/blog/358783.Doc

原标题：golang 系统设计压测工具 vegeta 使用示例
简介：golang tcp keepalive 参数程序配置，go 程序设置 tcp keepalive，操作系统 tcp 保活参数，清理僵死连接。
 | 原文链接：http://book.cotmkf.asia/blog/891857.Doc

原标题：设计思考：API网关和BFF职责边界划分
简介：模拟登录鉴权权限判断示例，实现简易登录流程，会话状态维护，完成接口权限校验，理解身份鉴权基础逻辑。
 | 原文链接：http://book.cotmkf.asia/blog/482961.Doc

原标题：golang 系统设计序列化性能选型对比
简介：golang fasthttp 高性能 http 库使用，fasthttp 高性能 http 实现，适合超高 QPS 场景，对比 net/http 差异。
 | 原文链接：http://book.cotmkf.asia/blog/954553.Doc

原标题：golang jwt 过期刷新 token 实现
简介：golang net/http/httptest 服务端模拟，httptest.NewRecorder 记录 handler 响应，校验返回状态码 body。
 | 原文链接：http://book.cotmkf.asia/blog/079362.Doc

原标题：GitHub Markdown 文档语法汇总
简介：golang go mod vendor 本地依赖导出，导出 vendor 目录，离线环境编译项目，无需访问外网拉依赖。
 | 原文链接：http://book.cotmkf.asia/blog/198856.Doc

原标题：踩坑：幂等键生成逻辑错误造成重复业务
简介：golang go 排序 sort 包自定义排序，sort 包实现自定义排序逻辑，对切片按业务规则排序。
 | 原文链接：http://book.cotmkf.asia/blog/026983.Doc

原标题：方案设计：批量大数据导出系统架构拆解
简介：golang grpc 重试机制客户端配置，grpc 客户端配置重试策略，临时故障自动重试，提升调用稳定性。
 | 原文链接：http://book.cotmkf.asia/blog/227588.Doc

?
