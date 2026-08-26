最新前沿技术资讯

一、入门教程｜Getting Started
原标题：Practice：实现接口签名、验签完整示例代码
简介：golang 漏桶算法实现接口限流，漏桶算法控制请求流出速率，平滑突发流量，削平流量峰值。
 | 原文链接：http://book.xbl63z.asia/blog/335303.Doc

原标题：前端打包分包加载提速方案
简介：CI 流水线超时时间延长配置，调大 CI 任务超时阈值，解决构建任务耗时较长被流水线强制终止。
 | 原文链接：http://book.xbl63z.asia/blog/756598.Doc

原标题：golang 系统设计用户签到统计方案
简介：批量操作分批处理防止 OOM，大批量数据处理不一次性加载全部数据，分批循环处理，避免内存溢出。
 | 原文链接：http://book.xbl63z.asia/blog/012205.Doc

原标题：入门实践：简单重试逻辑封装实现
简介：布隆过滤器数据高效去重实现，实现布隆过滤器组件，用于海量数据去重，节省大量内存空间。
 | 原文链接：http://book.xbl63z.asia/blog/898835.Doc

原标题：踩坑：数据库连接未关闭，连接池泄露
简介：golang 分布式唯一 id 多种方案对比，雪花、redis、uuid 对比各方案优缺点，指导业务选型使用。
 | 原文链接：http://book.xbl63z.asia/blog/900110.Doc

原标题：移动端适配 rem vw 方案对比
简介：golang 分表跨表 join 查询处理方案，分表后跨分片关联查询解决方案，业务层聚合代替数据库 join。
 | 原文链接：http://book.xbl63z.asia/blog/550968.Doc

原标题：部署实践：内网开发环境代理配置实践
简介：ServiceWorker 缓存页面更新清理，处理 ServiceWorker 缓存，实现页面新版本更新，用户可以加载最新页面。
 | 原文链接：http://book.xbl63z.asia/blog/782001.Doc

原标题：性能复盘：慢SQL定位、分析、改写完整案例
简介：golang sort 切片排序自定义 less，sort.Slice 切片快速排序，自定义 less 函数实现业务排序。
 | 原文链接：http://book.xbl63z.asia/blog/077008.Doc

原标题：golang 定时任务 cron 使用指南
简介：业务幂等键设计防重复逻辑，讲解幂等键设计思路，选择合适业务字段作为幂等标识，实现可靠防重复。
 | 原文链接：http://book.xbl63z.asia/blog/562411.Doc

原标题：golang base64 编码解码实操
简介：golang 分布式锁防死锁实现要点，锁超时、续期、锁持有者校验，避免锁死锁，保障分布式锁可靠性。
 | 原文链接：http://book.xbl63z.asia/blog/969560.Doc

原标题：运维笔记：磁盘inode耗尽故障排查处理
简介：golang snowflake 时钟回拨解决方案，雪花算法处理时钟回拨，防止生成重复 ID，保证 ID 全局唯一。
 | 原文链接：http://book.xbl63z.asia/blog/458633.Doc

原标题：Nginx 请求头大小上限调整
简介：端口占用访问失败排查方案，讲解端口占用排查命令，定位占用进程，释放端口，解决服务启动端口被占用报错。
 | 原文链接：http://book.xbl63z.asia/blog/892503.Doc

原标题：架构笔记：批量任务系统架构防重复、断点续跑
简介：golang json 解析未知动态 json 结构，解析到 map [string] any 处理未知 json，动态读取字段。
 | 原文链接：http://book.xbl63z.asia/blog/348448.Doc

原标题：Practice：实现多级缓存本地缓存+Redis实践
简介：golang 重试退避机制代码实现，Go 实现请求重试与指数退避，处理临时故障，提升调用稳定性。
 | 原文链接：http://book.xbl63z.asia/blog/820644.Doc

原标题：避坑：请求未设置read超时无限挂起连接
简介：golang 分库分表简单路由实现，简易分表路由逻辑实现，根据分片 key 计算分片位置，数据路由写入。
 | 原文链接：http://book.xbl63z.asia/blog/178409.Doc

原标题：golang k8s liveness readiness 探针
简介：golang 容器信号转发处理问题修复，docker/k8s 正确转发 SIGTERM 信号，保证 go 程序收到信号优雅退出。
 | 原文链接：http://book.xbl63z.asia/blog/663062.Doc

原标题：跨域偶现失败配置修复
简介：golang go 爬虫 html 解析 goquery，goquery 解析 html 文档，css 选择器提取网页内容，实现网页数据抓取。
 | 原文链接：http://book.xbl63z.asia/blog/202937.Doc

原标题：踩坑记录：浮点精度错误造成业务计算错误
简介：静态博客部署 GitHub Pages 教程，将静态博客项目部署至 GitHub Pages，完成线上访问，快速搭建个人技术博客站点。
 | 原文链接：http://book.xbl63z.asia/blog/989176.Doc

原标题：golang 分布式锁 redis 实现
简介：react 状态管理方案选型对比，对比 Redux、Zustand 等 React 状态管理库，分析适用业务场景辅助选型。
 | 原文链接：http://book.xbl63z.asia/blog/087094.Doc

原标题：golang es 分词器选型业务适配
简介：内网测试服务搭建团队调试，配置本地服务内网可访问，团队成员能够访问调试，方便前后端联调与内部演示。
 | 原文链接：http://book.xbl63z.asia/blog/706527.Doc

原标题：实践：实现Redis分布式锁完整可运行代码
简介：golang 内存碎片问题识别与规避，大量小对象频繁分配产生内存碎片，通过对象池减少碎片。
 | 原文链接：http://book.xbl63z.asia/blog/552297.Doc

原标题：golang 系统设计热点数据缓存处理
简介：Nginx 反向代理路由配置实战，配置 Nginx 反向代理，实现请求转发、路由分发，掌握 Nginx 基础配置能力。
 | 原文链接：http://book.xbl63z.asia/blog/381960.Doc

原标题：nodejs 接口限流防刷代码实现
简介：golang 工具函数库封装思路，Go 通用工具库封装思路，错误处理、类型转换，业务项目复用工具代码。
 | 原文链接：http://book.xbl63z.asia/blog/102029.Doc

原标题：DevOps：制品仓库管理二进制产物版本
简介：防火墙 IP 白名单回调接口放行，配置防火墙白名单，放行第三方回调服务器 IP，接收回调请求正常。
 | 原文链接：http://book.xbl63z.asia/blog/522213.Doc

原标题：坑点：gitsubmodule子模块更新失败踩坑
简介：包管理器依赖冲突解决方案，分析依赖冲突产生根源，提供版本调整、锁定依赖等手段，解决项目依赖报错问题。
 | 原文链接：http://book.xbl63z.asia/blog/159171.Doc

原标题：golang 系统设计限流熔断降级组合使用
简介：布隆过滤器误判问题修正，调整布隆过滤器参数，降低误判概率，保证业务去重逻辑准确。
 | 原文链接：http://book.xbl63z.asia/blog/595117.Doc

原标题：Performance：数据库大表优化，冷热数据分离
简介：JWT 工具封装令牌刷新过期，封装 JWT 工具类，实现令牌生成、校验、过期刷新整套令牌管理逻辑。
 | 原文链接：http://book.xbl63z.asia/blog/290404.Doc

原标题：接口签名验签完整安全方案
简介：golang tcp 连接泄露排查定位，netstat 查看连接状态，找出未正常关闭连接，定位连接泄漏代码。
 | 原文链接：http://book.xbl63z.asia/blog/529032.Doc

原标题：golang 系统设计告警规则阈值设置方法论
简介：TLS 版本兼容 HTTPS 握手失败，兼容老旧 TLS 协议版本，修复部分客户端 HTTPS 握手失败无法访问。
 | 原文链接：http://book.xbl63z.asia/blog/015616.Doc

原标题：包管理器依赖冲突解决方案
简介：手写简易 ORM 理解对象映射，手写极简 ORM 示例，理解对象与数据库表字段映射底层原理。
 | 原文链接：http://book.xbl63z.asia/blog/962113.Doc

原标题：零基础理解跨域问题产生原因与基础方案
简介：线程调度优化减少上下文切换，优化线程数量，减少线程频繁切换，降低 CPU 上下文切换开销。
 | 原文链接：http://book.xbl63z.asia/blog/829004.Doc

原标题：golang excel 简单读写操作示例
简介：接口签名验签完整安全方案，一套完整接口签名方案，包含签名生成、请求携带、服务端验签校验。
 | 原文链接：http://book.xbl63z.asia/blog/488768.Doc

原标题：坑点：Git工作区换行符CRLF/LF跨平台坑
简介：golang go 容器 heap 堆实现优先队列，实现 heap 接口，构建优先队列，任务优先级调度。
 | 原文链接：http://book.xbl63z.asia/blog/378649.Doc

原标题：golang 系统设计 tcp 粘包拆包处理方案实现
简介：Redis 大 key 拆分集群卡顿解决，拆分 Redis 超大 Key，避免大 key 操作造成 Redis 集群卡顿阻塞。
 | 原文链接：http://book.xbl63z.asia/blog/412111.Doc

原标题：开发复盘：大JSON解析分批处理避免内存溢出
简介：浏览器缓存强制刷新方案，设置 HTTP 缓存头，处理浏览器缓存旧静态资源，让用户加载更新后的页面。
 | 原文链接：http://book.xbl63z.asia/blog/675703.Doc

原标题：golang 系统设计告警分级 p0‑p3 定义处理流程
简介：golang sort 切片排序自定义 less，sort.Slice 切片快速排序，自定义 less 函数实现业务排序。
 | 原文链接：http://book.xbl63z.asia/blog/462821.Doc

原标题：实战：Docker资源监控查看容器状态实操
简介：golang go 错误包装 fmt.Errorf % w，使用 % w 包装错误，支持 errors.Is errors.As 判断错误类型。
 | 原文链接：http://book.xbl63z.asia/blog/797026.Doc

原标题：Practice：实现文件监控自动重启开发服务工具
简介：golang gorm 软删除实现逻辑，Gorm 开启软删除，删除数据仅标记，数据保留可恢复，满足业务数据留存。
 | 原文链接：http://book.xbl63z.asia/blog/967244.Doc

原标题：实战：对象存储断点续传下载实践
简介：全局时间标准统一逻辑错乱修复，全服务统一使用同一时间标准，不要混用本地时间 UTC，修复时间逻辑 bug。
 | 原文链接：http://book.xbl63z.asia/blog/560040.Doc

原标题：golang 协程 panic 捕获防止崩溃
简介：前端虚拟列表大数据渲染优化，实现虚拟滚动列表，只渲染可视区域 DOM，上万条数据页面流畅渲染。
 | 原文链接：http://book.xbl63z.asia/blog/085048.Doc


二、踩坑排错｜Troubleshooting
原标题：新手避坑：第一次提交GitHub项目完整流程
简介：golang redis hash 结构业务实战，使用 Redis Hash 存储对象数据，适合对象字段频繁更新业务场景。
 | 原文链接：http://book.xbl63z.asia/blog/846341.Doc

原标题：架构复盘：RPC框架架构超时重试设计要点
简介：golang 系统资源限制读取 cpu 内存，读取系统容器 cpu 内存限制，程序适配容器资源配额做业务调优。
 | 原文链接：http://book.xbl63z.asia/blog/379522.Doc

原标题：线上接口超时故障排查思路
简介：golang go 网络编程 net 包基础，net 包 tcp udp socket 编程，监听接收连接，读写数据。
 | 原文链接：http://book.xbl63z.asia/blog/894609.Doc

原标题：快速入门ORM，实现简单数据库增删改查
简介：golang net.Listener 包装自定义监听器，包装 Listener 做连接计数、连接拦截，扩展网络能力。
 | 原文链接：http://book.xbl63z.asia/blog/852107.Doc

原标题：golang go test 覆盖率统计实操
简介：golang crypto 密码学最佳实践，go crypto 包加密签名，规避不安全算法，使用安全密码套件。
 | 原文链接：http://book.xbl63z.asia/blog/699907.Doc

原标题：golang 系统设计技术文档编写最佳实践
简介：golang 定时任务任务持久化存储，定时任务持久化到数据库，服务重启任务不丢失，动态管理任务。
 | 原文链接：http://book.xbl63z.asia/blog/891494.Doc

原标题：避坑：Spring事务传播行为理解错误事务失效
简介：服务健康检查监控接口开发，开发健康检查接口，反馈服务运行状态，供编排工具监控服务存活状态。
 | 原文链接：http://book.xbl63z.asia/blog/808814.Doc

原标题：运维笔记：服务器日志轮转logrotate配置
简介：golang go 输入数据校验防御，所有外部入参严格校验长度格式，防止恶意输入造成业务异常。
 | 原文链接：http://book.xbl63z.asia/blog/394677.Doc

原标题：pnpm 包管理工具实战避坑指南
简介：golang go 值传递引用传递理解，go 全部为值传递，指针本质拷贝指针值，理清参数传递行为。
 | 原文链接：http://book.xbl63z.asia/blog/056580.Doc

原标题：golang kafka 死信队列业务落地
简介：golang 单元测试 mock http 请求，mock HTTP 外部接口，单元测试不依赖外部网络，保证用例稳定运行。
 | 原文链接：http://book.xbl63z.asia/blog/157680.Doc

原标题：端口占用访问失败排查方案
简介：ServiceWorker 缓存页面更新清理，处理 ServiceWorker 缓存，实现页面新版本更新，用户可以加载最新页面。
 | 原文链接：http://book.xbl63z.asia/blog/873820.Doc

原标题：GC 垃圾回收优化降低 CPU 占用
简介：golang go 随机数安全与非安全，math/rand 伪随机与 crypto/rand 密码学安全随机，区分业务场景。
 | 原文链接：http://book.xbl63z.asia/blog/316452.Doc

原标题：开发复盘：导出大文件避免内存溢出实现方案
简介：golang jwt 鉴权中间件完整示例，Gin JWT 鉴权中间件，令牌校验，解析用户信息，接口鉴权拦截。
 | 原文链接：http://book.xbl63z.asia/blog/999286.Doc

原标题：内网 DNS 不稳定随机报错排查
简介：golang 雪花 id 重复问题排查，排查雪花算法 ID 重复问题，时钟回拨、机器 ID 冲突，给出修复方案。
 | 原文链接：http://book.xbl63z.asia/blog/969853.Doc

原标题：golang 系统设计接口不兼容平滑迁移方案
简介：golang go 死锁检测工具，静态检查、运行检测，发现 channel 锁导致死锁问题。
 | 原文链接：http://book.xbl63z.asia/blog/887369.Doc

原标题：安全组端口开放网络访问
简介：golang gorm select 指定查询字段，指定查询字段，避免查询全部字段，减少数据传输，提升查询性能。
 | 原文链接：http://book.xbl63z.asia/blog/230835.Doc

原标题：golang 协程泄露问题排查方法
简介：golang rsa 公钥加密私钥解密，rsa 非对称加密，大文件分块加密，处理非对称加密长度限制。
 | 原文链接：http://book.xbl63z.asia/blog/098453.Doc

原标题：排错：前端sourcemap错误线上无法定位报错
简介：日志驱动异常日志不输出修复，排查日志驱动配置，修复日志写入配置，恢复程序正常日志输出。
 | 原文链接：http://book.xbl63z.asia/blog/402986.Doc

原标题：golang 系统设计全局异常处理器实现
简介：版本升级服务启动失败处理，版本更新之后服务无法启动，对比新旧版本配置、依赖差异，完成故障修复。
 | 原文链接：http://book.xbl63z.asia/blog/600350.Doc

原标题：AI实践：大模型生成代码后审查与重构实践
简介：golang bcrypt 密码哈希加密存储，bcrypt 做用户密码哈希，加盐存储密码，保障用户密码安全。
 | 原文链接：http://book.xbl63z.asia/blog/324479.Doc

原标题：TLS 版本兼容 HTTPS 握手失败
简介：golang defer 执行顺序与坑点，defer 后进先出，循环内部 defer 陷阱，资源释放正确写法。
 | 原文链接：http://book.xbl63z.asia/blog/883232.Doc

原标题：golang 系统设计压测指标确定与分析
简介：SourceMap 生成线上报错定位，项目打包生成 SourceMap 文件，线上报错可以还原源码，快速定位报错位置。
 | 原文链接：http://book.xbl63z.asia/blog/147218.Doc

原标题：Troubleshooting：K8sPodOOMKilled完整排查流程
简介：golang prometheus 指标埋点开发，业务埋点计数器、仪表盘、直方图，对接 prometheus 采集监控指标。
 | 原文链接：http://book.xbl63z.asia/blog/911548.Doc

原标题：golang docker 容器资源限制设置
简介：文件锁正确使用避免死锁，合理使用文件锁，控制多进程访问同一个文件，规避文件锁死锁现象。
 | 原文链接：http://book.xbl63z.asia/blog/782106.Doc

原标题：golang 系统设计参数校验统一处理方案
简介：golang tar gz 压缩解压处理，tar.gz 归档压缩解压，服务端日志备份、文件打包场景使用。
 | 原文链接：http://book.xbl63z.asia/blog/824081.Doc

原标题：Security：文件路径穿越漏洞完整防护
简介：rebase 操作防止代码丢失，讲解 rebase 风险点，操作前做好备份，规避错误操作造成代码提交丢失。
 | 原文链接：http://book.xbl63z.asia/blog/017526.Doc

原标题：文件编码统一随机乱码修复
简介：golang gorm select 指定查询字段，指定查询字段，避免查询全部字段，减少数据传输，提升查询性能。
 | 原文链接：http://book.xbl63z.asia/blog/445684.Doc

原标题：效率笔记：VSCode插件集合后端前端开发效率
简介：golang bcrypt 密码哈希加密存储，bcrypt 做用户密码哈希，加盐存储密码，保障用户密码安全。
 | 原文链接：http://book.xbl63z.asia/blog/988005.Doc

原标题：Debug：静态资源缓存策略错误，用户看不到更新
简介：golang redis hash 结构业务实战，使用 Redis Hash 存储对象数据，适合对象字段频繁更新业务场景。
 | 原文链接：http://book.xbl63z.asia/blog/172669.Doc

原标题：golang 容器健康检查接口开发
简介：golang go time 时区数据库内置，go 内置时区数据库，不用系统时区文件，容器时区不依赖系统。
 | 原文链接：http://book.xbl63z.asia/blog/372410.Doc

原标题：golang 系统设计分库分表中间件思路
简介：线程调度优化减少上下文切换，优化线程数量，减少线程频繁切换，降低 CPU 上下文切换开销。
 | 原文链接：http://book.xbl63z.asia/blog/637217.Doc

原标题：配置与镜像分离防止信息泄露
简介：golang kafka 消费者组重平衡避坑，规避消费者组频繁 rebalance，减少消费抖动，保障消息消费稳定性。
 | 原文链接：http://book.xbl63z.asia/blog/583149.Doc

原标题：golang 系统设计接口幂等架构设计
简介：WebSocket 断线重连稳定优化，增加 WebSocket 断线自动重连逻辑，处理网络抖动，维持长连接稳定。
 | 原文链接：http://book.xbl63z.asia/blog/894121.Doc

原标题：golang 系统设计 ide 配置 go 开发效率提升技巧
简介：nodejs 多进程任务分发处理，多进程拆分处理 CPU 密集任务，主进程分发任务，利用多核提升处理速度。
 | 原文链接：http://book.xbl63z.asia/blog/916397.Doc

原标题：轻量 API 后端接口服务快速开发
简介：前端下载导出文件功能实现，前端实现文件流下载导出，处理异常，适配浏览器不同下载行为。
 | 原文链接：http://book.xbl63z.asia/blog/531106.Doc

原标题：安全实践：生产环境禁止开启debug调试模式
简介：golang 命令行参数解析开发，解析命令行入参，开发自定义 CLI 程序，读取启动参数配置服务。
 | 原文链接：http://book.xbl63z.asia/blog/965633.Doc

原标题：golang 系统设计压测工具 vegeta 使用示例
简介：golang aes cbc gcm 模式加密对比，AES‑CBC AES‑GCM 模式加密解密，理解两种模式差异选型。
 | 原文链接：http://book.xbl63z.asia/blog/293588.Doc

原标题：性能复盘：锁粒度太大，拆分细粒度锁优化
简介：css 变量主题切换方案实现，使用 CSS 变量实现网页主题切换，多套主题样式快速切换无需大量 CSS。
 | 原文链接：http://book.xbl63z.asia/blog/056367.Doc

原标题：运维笔记：磁盘inode耗尽故障排查处理
简介：golang os.Exit 退出程序注意 defer 不执行，os.Exit 会直接退出，不会执行 defer，优雅退出不要直接 os.Exit。
 | 原文链接：http://book.xbl63z.asia/blog/557833.Doc

原标题：站内邮件消息通知功能开发
简介：golang cgo 内存管理 C 与 Go 内存，区分 Go 内存 C 堆内存，防止 cgo 内存泄漏，正确释放 C 内存。
 | 原文链接：http://book.xbl63z.asia/blog/231219.Doc

三、实战开发｜Practice
原标题：golang mysql 主从同步延迟兼容
简介：golang http 重定向策略自定义，CheckRedirect 自定义重定向逻辑，限制重定向次数，防止死循环。
 | 原文链接：http://book.xbl63z.asia/blog/990483.Doc

原标题：golang 系统设计告警风暴抑制合并降噪方案
简介：内网 DNS 不稳定随机报错排查，定位内网 DNS 抖动问题，配置备选 DNS，解决偶现域名解析失败。
 | 原文链接：http://book.xbl63z.asia/blog/552040.Doc

原标题：golang 系统设计唯一索引业务使用场景
简介：程序预加载加快服务启动速度，把高频使用资源提前预加载，减少请求阶段初始化，加快服务启动。
 | 原文链接：http://book.xbl63z.asia/blog/644502.Doc

原标题：golang 系统设计线上日志快速检索技巧
简介：golang 滑动窗口限流算法 go 实现，滑动窗口限流，解决固定窗口临界流量突增漏洞，限流更精准。
 | 原文链接：http://book.xbl63z.asia/blog/773314.Doc

原标题：Issue：容器日志驱动配置错误日志全部丢失
简介：golang 项目 makefile 脚本编写，编写 Makefile 脚本，封装编译、测试、构建命令，简化项目操作。
 | 原文链接：http://book.xbl63z.asia/blog/973164.Doc

原标题：Nginx 缓冲区调优大文件上传
简介：golang time duration 解析时间字符串，time.ParseDuration 解析 1h30m 时间间隔字符串。
 | 原文链接：http://book.xbl63z.asia/blog/986273.Doc

原标题：性能复盘：锁粒度太大，拆分细粒度锁优化
简介：批量数据处理脚本编写技巧，编写脚本批量处理大量业务数据，循环处理、分批执行，提升数据处理效率。
 | 原文链接：http://book.xbl63z.asia/blog/590170.Doc

原标题：百万数据 Excel 导出内存优化
简介：golang grpc 错误状态码标准化，grpc 标准化错误返回，定义业务错误码，客户端解析处理业务异常。
 | 原文链接：http://book.xbl63z.asia/blog/905010.Doc

原标题：golang 系统设计定时任务失败重试告警实现
简介：JWT 工具封装令牌刷新过期，封装 JWT 工具类，实现令牌生成、校验、过期刷新整套令牌管理逻辑。
 | 原文链接：http://book.xbl63z.asia/blog/554133.Doc

原标题：性能笔记：磁盘IO过高业务优化手段
简介：Git 误提交撤销回退实操教程，演示多种撤销提交方式，区分已经推送远程和本地未提交场景，处理误提交代码。
 | 原文链接：http://book.xbl63z.asia/blog/009839.Doc

原标题：快速入门异步编程基础模型
简介：golang 内存 pprof 定位内存泄漏，pprof 分析内存快照，定位内存泄露对象，解决 Go 程序内存持续上涨。
 | 原文链接：http://book.xbl63z.asia/blog/030725.Doc

原标题：AI实践：大模型生成测试用例实践与校验
简介：golang grpc 客户端拦截器封装，grpc 客户端拦截器实现请求统一签名、重试、链路信息透传。
 | 原文链接：http://book.xbl63z.asia/blog/420987.Doc

原标题：golang 系统设计链路追踪核心概念 trace span 讲解
简介：跨域偶现失败配置修复，解决跨域问题时而复现时而正常，定位配置漏配、请求头异常等隐性问题。
 | 原文链接：http://book.xbl63z.asia/blog/883064.Doc

原标题：HelloShell：入门常用shell脚本编写
简介：golang http 服务性能优化调参，调优 Go HTTP 服务参数，调整连接池，提升服务并发吞吐能力。
 | 原文链接：http://book.xbl63z.asia/blog/070682.Doc

原标题：避坑：请求未设置read超时无限挂起连接
简介：golang runtime.Gosched 主动让出调度，长计算循环主动 Gosched，让出调度权，防止其他协程饥饿。
 | 原文链接：http://book.xbl63z.asia/blog/566323.Doc

原标题：golang 系统设计指标聚合计算存储选型对比
简介：磁盘 inode 耗尽文件创建失败，排查磁盘 inode 占用，清理大量小文件，恢复文件创建能力。
 | 原文链接：http://book.xbl63z.asia/blog/606219.Doc

原标题：开发记录：数据库悲观锁乐观锁业务场景实践
简介：golang go get 升级降级依赖版本，go get 指定版本升级降级依赖包，管理第三方库版本。
 | 原文链接：http://book.xbl63z.asia/blog/351287.Doc

原标题：golang mysql 防止 sql 注入实践
简介：golang go1.18 + 泛型基础实操，go 泛型基础语法，泛型函数泛型类型，实现通用工具函数。
 | 原文链接：http://book.xbl63z.asia/blog/928574.Doc

原标题：ORM 框架数据库增删改查实操
简介：golang smtp 邮件发送完整示例，调用 smtp 服务发送文本与 html 格式邮件，实现邮件通知能力。
 | 原文链接：http://book.xbl63z.asia/blog/450792.Doc

原标题：Debug：异步任务堆积，服务响应越来越慢
简介：golang go‑zero api 接口开发与路由，go‑zero 编写 api 定义文件，生成代码开发 http 接口。
 | 原文链接：http://book.xbl63z.asia/blog/032943.Doc

原标题：golang redis 地理位置 geo 使用
简介：Git 代码冲突正确处理方式，讲解冲突产生场景，演示冲突文件修改，正确合并代码，防止代码丢失。
 | 原文链接：http://book.xbl63z.asia/blog/294500.Doc

原标题：Issue复现：内存泄漏定位完整复盘记录
简介：golang crypto 密码学最佳实践，go crypto 包加密签名，规避不安全算法，使用安全密码套件。
 | 原文链接：http://book.xbl63z.asia/blog/197970.Doc

原标题：快速入门GraphQL基础查询语法示例
简介：golang 协程泄露问题排查方法，识别 Go 协程泄露现象，分析泄露场景，给出排查定位协程泄露手段。
 | 原文链接：http://book.xbl63z.asia/blog/741639.Doc

原标题：golang 接口请求日志记录中间件
简介：eslint prettier 代码规范落地，配置 eslint 与 prettier，做代码检查格式化，统一前端团队代码风格。
 | 原文链接：http://book.xbl63z.asia/blog/411721.Doc

原标题：golang gorm 批量插入性能调优
简介：开发环境变量配置全平台教程，区分 Windows、macOS、Linux 系统，讲解环境变量配置、加载优先级与常见失效原因。
 | 原文链接：http://book.xbl63z.asia/blog/740023.Doc

原标题：golang etcd watch 监听配置变更
简介：golang go mod vendor 本地依赖导出，导出 vendor 目录，离线环境编译项目，无需访问外网拉依赖。
 | 原文链接：http://book.xbl63z.asia/blog/854437.Doc

原标题：部署复盘：GitHubActions完整自动化配置
简介：golang systemd 配置 go 服务部署，编写 systemd unit 文件管理 go 服务，开机自启、崩溃自动重启。
 | 原文链接：http://book.xbl63z.asia/blog/891848.Doc

原标题：golang k8s 持久化 pv pvc 使用实操
简介：Git 混乱提交历史清理方法，针对杂乱的提交记录，使用 Git 工具整理，清理无效提交，还原整洁版本历史。
 | 原文链接：http://book.xbl63z.asia/blog/293315.Doc

原标题：部署实践：DockerCompose管理多服务环境
简介：golang rate 令牌桶限流器源码理解，拆解令牌桶限流核心逻辑，理解令牌生成消耗，掌握限流底层原理。
 | 原文链接：http://book.xbl63z.asia/blog/567596.Doc

原标题：排错：DockerCompose依赖顺序启动顺序坑
简介：限流窗口绕过漏洞修复方案，修复限流时间窗口漏洞，避免攻击者绕过限流规则，保障接口防护有效。
 | 原文链接：http://book.xbl63z.asia/blog/402622.Doc

原标题：golang dockerfile 多阶段构建详解
简介：golang net/http 超时全套配置，完整配置 Go HTTP 服务读写空闲超时，全方位防止请求挂住。
 | 原文链接：http://book.xbl63z.asia/blog/076379.Doc

原标题：热更新开发环境配置教程
简介：golang go 模块迁移从 GOPATH 到 GoMod，老项目从 GOPATH 迁移 go mod，解决依赖管理混乱问题。
 | 原文链接：http://book.xbl63z.asia/blog/160443.Doc

原标题：OpenSource：开源项目贡献者协作流程规范
简介：后端分页查询逻辑代码实现，编写后端分页接口，处理页码、每页条数参数，优化大数据量查询返回结果。
 | 原文链接：http://book.xbl63z.asia/blog/922243.Doc

原标题：golang 系统设计大文件上传架构
简介：golang wasm 浏览器 js 交互，go wasm 与 js 互相调用，浏览器端 go 程序操作 dom 调用 js 函数。
 | 原文链接：http://book.xbl63z.asia/blog/852894.Doc

原标题：性能复盘：系统上下文切换过高性能下降调优
简介：前端 pdf 预览渲染方案对比，对比前端 PDF 预览库，分析性能、兼容性，给出业务选型参考。
 | 原文链接：http://book.xbl63z.asia/blog/349287.Doc

原标题：golang 接口返回统一封装工具
简介：分布式锁失效问题排查修复，分析分布式锁失效场景，修复锁超时、续期问题，保证锁逻辑可靠。
 | 原文链接：http://book.xbl63z.asia/blog/239140.Doc

原标题：开发记录：跨域中间件完整配置与边界处理
简介：容器资源限制防止宿主机过载，设置容器 CPU 内存资源上限，避免单个容器耗尽宿主机全部硬件资源。
 | 原文链接：http://book.xbl63z.asia/blog/524100.Doc

原标题：golang docker 部署 mongodb 开发环境
简介：分页逻辑错误数据漏查修复，修复分页查询逻辑漏洞，解决分页漏数据、重复返回数据等业务问题。
 | 原文链接：http://book.xbl63z.asia/blog/278554.Doc

原标题：golang 数据库批量更新性能优化
简介：golang base64 编码解码实操，Go Base64 编码解码示例，处理业务场景 Base64 格式数据转换。
 | 原文链接：http://book.xbl63z.asia/blog/780918.Doc

原标题：新手教程：本地项目初始化gitignore配置
简介：CI/CD 流水线自动构建部署落地，搭建完整 CI/CD 流水线，代码提交自动构建、测试、部署到目标环境。
 | 原文链接：http://book.xbl63z.asia/blog/853698.Doc

四、架构设计｜Architecture
原标题：golang 系统设计 e2e 端到端测试简单落地思路
简介：nodejs 跨域中间件配置细节，Express 跨域中间件配置细节，处理预检请求，修复偶现跨域失效。
 | 原文链接：http://book.xbl63z.asia/blog/587336.Doc

原标题：部署实践：HTTPS证书自动续期配置实践
简介：golang fasthttp 服务开发完整示例，fasthttp 搭建 http 服务，路由、参数读取、响应返回完整业务。
 | 原文链接：http://book.xbl63z.asia/blog/153314.Doc

原标题：前后端交互跨域问题完整处理
简介：golang 数据库连接池参数调优详解，最大连接空闲连接最大生命周期，结合业务合理配置避免资源浪费。
 | 原文链接：http://book.xbl63z.asia/blog/190876.Doc

原标题：Debug：DNS缓存TTL设置不当服务切换无法生效
简介：golang go 服务蓝绿发布实践思路，蓝绿两套实例，流量一键切换，回滚快速降低发布风险。
 | 原文链接：http://book.xbl63z.asia/blog/342681.Doc

原标题：golang redis 大 key 识别处理方案
简介：golang base64 编码解码实操，Go Base64 编码解码示例，处理业务场景 Base64 格式数据转换。
 | 原文链接：http://book.xbl63z.asia/blog/743022.Doc

原标题：nodejs 内存溢出问题排查修复
简介：golang go 运行时获取编译信息，程序内部读取编译时间 git 版本，接口输出程序版本信息。
 | 原文链接：http://book.xbl63z.asia/blog/294803.Doc

原标题：实战项目：搭建私有Docker镜像仓库本地实践
简介：静态资源 404 路径打包修复，修复打包后静态资源访问 404，调整资源输出路径，保证资源正常加载。
 | 原文链接：http://book.xbl63z.asia/blog/615370.Doc

原标题：Issue：文件句柄耗尽，服务缓慢卡死复盘
简介：golang bytes.Buffer 字节缓冲区使用，bytes.Buffer 字节内存缓冲区，拼接字节，避免频繁内存分配。
 | 原文链接：http://book.xbl63z.asia/blog/076688.Doc

原标题：Docker 容器网络不通排查
简介：GraphQL 接口查询优化实操，体验 GraphQL 查询方式，按需获取字段，减少冗余数据传输，优化接口请求效率。
 | 原文链接：http://book.xbl63z.asia/blog/421104.Doc

原标题：golang 参数校验业务接口处理
简介：nodejs 进程间通信 IPC 实操，演示 Node.js 主进程子进程 IPC 通信，进程之间传递消息数据。
 | 原文链接：http://book.xbl63z.asia/blog/595203.Doc

原标题：golang 系统设计海量数据分页查询
简介：nodejs 读取大文件 csv 处理方案，Node 流式读取超大 CSV 文件，逐行解析，避免一次性加载全部文件。
 | 原文链接：http://book.xbl63z.asia/blog/420910.Doc

原标题：golang 系统设计埋点数据上报方案
简介：序列化版本不一致解析失败，保证序列化对象版本对齐，修复版本不匹配导致对象反序列化失败。
 | 原文链接：http://book.xbl63z.asia/blog/186084.Doc

原标题：Debug：表单提交特殊字符造成接口解析失败
简介：开源源码阅读拆解学习思路，分享阅读大型开源项目方法，从入口文件逐层拆解模块，降低源码学习门槛。
 | 原文链接：http://book.xbl63z.asia/blog/979247.Doc

原标题：golang 系统设计 http3 quic 简单原理了解
简介：golang go 爬虫异步并发抓取，协程池控制并发抓取网页，多协程采集，提升爬虫采集速度。
 | 原文链接：http://book.xbl63z.asia/blog/373466.Doc

原标题：golang 系统设计对象池复用减少内存分配
简介：golang cobra 命令行参数配置绑定，cobra 绑定配置文件环境变量命令行参数，多源配置合并。
 | 原文链接：http://book.xbl63z.asia/blog/850178.Doc

原标题：golang 系统设计定时任务分片执行分布式思路
简介：golang time.Ticker 泄漏常见场景，忘记 Stop Ticker，导致协程泄漏，定时器资源无法释放。
 | 原文链接：http://book.xbl63z.asia/blog/181233.Doc

原标题：手写简易 RPC 服务通信原型
简介：golang go test 单元测试命令参数详解，gotest 参数覆盖率，指定测试用例，跳过测试，单元测试命令实操。
 | 原文链接：http://book.xbl63z.asia/blog/424210.Doc

原标题：Issue：系统fd快速上涨进程慢慢卡死
简介：限流规则误拦截正常请求修复，修正限流规则阈值，避免合法用户被限流拦截，兼顾防护与可用性。
 | 原文链接：http://book.xbl63z.asia/blog/621728.Doc

?
