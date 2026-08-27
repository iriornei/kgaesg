最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计 p0 故障复盘方法论讲解
简介：golang go select 多路等待 channel，select 等待多个 channel，default 非阻塞，超时等待 channel。
 | 原文链接：http://book.lzrbpa.asia/blog/1545407.sHtMl

原标题：Practice：批量异步任务处理系统设计实现
简介：并发数据覆盖加锁安全处理，多线程并发修改同一数据，增加锁机制，防止并发覆盖丢失更新数据。
 | 原文链接：http://book.lzrbpa.asia/blog/5465203.sHtMl

原标题：golang 系统设计 issue 模板 bug 反馈模板
简介：golang slice 切片底层原理与坑点，切片扩容、截取、底层数组共享，规避切片修改互相影响数据。
 | 原文链接：http://book.lzrbpa.asia/blog/4486899.sHtMl

原标题：golang k8s pod 优雅关闭流程讲解
简介：golang 进程信号捕获 SIGUSR 自定义信号，捕获用户自定义信号，实现线上不重启触发调试、日志切换。
 | 原文链接：http://book.lzrbpa.asia/blog/4506839.sHtMl

原标题：数据库排序规则统一结果一致
简介：数据库连接及时关闭连接泄漏，确保数据库连接使用完毕释放归还连接池，杜绝连接泄漏耗尽连接。
 | 原文链接：http://book.lzrbpa.asia/blog/6627395.sHtMl

原标题：golang 优雅停机服务关闭实现
简介：golang gorm 软删除实现逻辑，Gorm 开启软删除，删除数据仅标记，数据保留可恢复，满足业务数据留存。
 | 原文链接：http://book.lzrbpa.asia/blog/3126464.sHtMl

原标题：golang http grpc 全链路埋点示例
简介：golang docker 镜像构建最佳实践，Go 项目 Docker 镜像构建最佳实践，减小镜像体积，安全构建。
 | 原文链接：http://book.lzrbpa.asia/blog/8986577.sHtMl

原标题：golang csv 读写批量数据处理
简介：golang 数据库分表策略按时间分片，按时间维度分表，历史数据拆分，单表数据量控制保证查询性能。
 | 原文链接：http://book.lzrbpa.asia/blog/9299926.sHtMl

原标题：架构复盘：消息队列在业务系统中边界与最佳实践
简介：golang jaeger 链路追踪部署对接，jaeger 接收 opentelemetry 链路数据，可视化完整调用链路。
 | 原文链接：http://book.lzrbpa.asia/blog/7805796.sHtMl

原标题：golang 系统设计令牌桶漏桶算法对比
简介：提交第一个开源 PR 完整流程，Fork 项目、修改代码、提交 Pull Request，讲解 PR 规范，提升合并通过率。
 | 原文链接：http://book.lzrbpa.asia/blog/9096846.sHtMl

原标题：Performance：避免内存拷贝，大对象处理优化
简介：CDN 缓存刷新获取最新静态资源，调用 CDN 刷新接口，清除节点旧缓存，用户访问到更新后的静态文件。
 | 原文链接：http://book.lzrbpa.asia/blog/9316791.sHtMl

原标题：API 大版本不兼容平滑迁移
简介：golang redis 客户端业务使用，Go Redis 客户端对接，实现缓存、计数器，适配各类 Redis 业务场景。
 | 原文链接：http://book.lzrbpa.asia/blog/3743203.sHtMl

原标题：Practice：模拟缓存雪崩缓存击穿验证防护策略
简介：golang gitlab ci go 项目流水线编写，gitlab ci 流水线执行单元测试、静态检查、构建推送镜像。
 | 原文链接：http://book.lzrbpa.asia/blog/1792728.sHtMl

原标题：方案设计：多租户系统架构三种实现模式对比
简介：golang 字符串处理常用技巧汇总，字符串拼接、分割、替换、类型转换实操，规避字符串高频错误。
 | 原文链接：http://book.lzrbpa.asia/blog/1831168.sHtMl

原标题：OOMKilled 容器被杀完整排查
简介：序列化版本不一致解析失败，保证序列化对象版本对齐，修复版本不匹配导致对象反序列化失败。
 | 原文链接：http://book.lzrbpa.asia/blog/5651680.sHtMl

原标题：Performance：JSON序列化性能优化实践
简介：接口压测定位系统性能瓶颈，使用压测工具对接口施压，观察指标，定位系统性能瓶颈点。
 | 原文链接：http://book.lzrbpa.asia/blog/4507566.sHtMl

原标题：实战：基于内存实现简单消息广播组件
简介：golang go math 大数高精度计算，math/big 处理超大整数、高精度浮点数，金额大数运算。
 | 原文链接：http://book.lzrbpa.asia/blog/6407223.sHtMl

原标题：坑点：环境配置写死代码，上线忘记修改
简介：缓存穿透防护保护数据库，实现缓存穿透防护手段，拦截不存在的数据查询，避免请求直接打穿数据库。
 | 原文链接：http://book.lzrbpa.asia/blog/0256568.sHtMl

原标题：安全笔记：文件下载接口路径校验安全
简介：golang 参数校验业务接口处理，Go 接口入参参数校验，拦截非法入参，减少业务层参数判断代码。
 | 原文链接：http://book.lzrbpa.asia/blog/2583278.sHtMl

原标题：golang 系统设计 io 瓶颈磁盘网络优化实践
简介：golang grpc 客户端流上传数据，客户端流式请求，客户端分批上传数据到服务端，适合大文件传输。
 | 原文链接：http://book.lzrbpa.asia/blog/5385680.sHtMl

原标题：golang 系统设计密码存储哈希加盐实现
简介：短信服务封装失败自动重试，封装短信发送组件，处理发送失败自动重试，兼容多短信服务商。
 | 原文链接：http://book.lzrbpa.asia/blog/3474536.sHtMl

原标题：前端图片懒加载性能优化
简介：移动端适配 rem vw 方案对比，对比 rem 与 vw 移动端适配方案，分析优缺点，给出选型建议。
 | 原文链接：http://book.lzrbpa.asia/blog/6530270.sHtMl

原标题：线上故障：Redis内存淘汰策略错误数据丢失
简介：golang ioutil 已废弃替换方案，ioutil 废弃之后替换为 os io 包函数，更新旧项目代码。
 | 原文链接：http://book.lzrbpa.asia/blog/3544843.sHtMl

原标题：批量数据处理脚本编写技巧
简介：golang go embed 嵌入静态资源文件，使用 go embed 把静态文件编译进二进制，单文件部署携带静态资源。
 | 原文链接：http://book.lzrbpa.asia/blog/9302398.sHtMl

原标题：golang ci 流水线单元测试集成测试
简介：golang grpc 错误状态码标准化，grpc 标准化错误返回，定义业务错误码，客户端解析处理业务异常。
 | 原文链接：http://book.lzrbpa.asia/blog/3850517.sHtMl

原标题：Debug：DNS缓存TTL设置不当服务切换无法生效
简介：golang aes 对称加密解密示例，AES 对称加密解密实现，业务敏感数据加密存储传输。
 | 原文链接：http://book.lzrbpa.asia/blog/6007204.sHtMl

原标题：设计思考：防雪崩，系统过载保护架构设计
简介：golang kitex 中间件与元数据传递，kitex 自定义中间件，透传 traceId 鉴权元数据，统一处理请求。
 | 原文链接：http://book.lzrbpa.asia/blog/3387705.sHtMl

原标题：零基础理解进程、线程基础概念区别
简介：golang atomic 原子操作整数，atomic 加减比较交换，无锁更新整型变量，简单计数器场景。
 | 原文链接：http://book.lzrbpa.asia/blog/9710707.sHtMl

原标题：golang 系统设计告警分级 p0‑p3 定义处理流程
简介：数据库分表存储大表优化方案，对超大数据表做分表，拆分数据，降低单表数据量提升查询性能。
 | 原文链接：http://book.lzrbpa.asia/blog/5303910.sHtMl

原标题：golang kafka 消息顺序性保证方案
简介：安全组端口开放网络访问，调整服务器安全组规则，开放业务需要端口，恢复外部网络访问服务。
 | 原文链接：http://book.lzrbpa.asia/blog/0354766.sHtMl

原标题：性能笔记：布隆过滤器减少无效数据库查询
简介：golang go 程序抢占调度理解，理解 go 抢占式调度原理，长循环阻塞调度，造成协程调度延迟。
 | 原文链接：http://book.lzrbpa.asia/blog/7890036.sHtMl

原标题：Hands‑on：简易跨进程通信demo开发实践
简介：项目构建脚本编译打包解析，解读项目构建脚本，理清编译、压缩、资源复制流程，理解打包后产物如何生成。
 | 原文链接：http://book.lzrbpa.asia/blog/3570840.sHtMl

原标题：ORM 框架数据库增删改查实操
简介：golang sync.WaitGroup 协程等待控制，WaitGroup 控制一组协程等待全部执行完成，完成批量协程任务调度。
 | 原文链接：http://book.lzrbpa.asia/blog/3414165.sHtMl

原标题：golang 系统设计序列化性能选型对比
简介：极简方式搭建个人技术文档站点，使用轻量化工具快速部署文档站点，支持 markdown 编写，实现知识沉淀与对外分享。
 | 原文链接：http://book.lzrbpa.asia/blog/6457355.sHtMl

原标题：排错：内网域名解析不稳定导致服务随机报错
简介：文件锁正确使用避免死锁，合理使用文件锁，控制多进程访问同一个文件，规避文件锁死锁现象。
 | 原文链接：http://book.lzrbpa.asia/blog/7400060.sHtMl

原标题：MySQL 慢查询索引优化实战
简介：前端骨架屏提升页面体验，实现页面骨架屏，数据未加载完成展示占位，优化页面白屏感知体验。
 | 原文链接：http://book.lzrbpa.asia/blog/3045133.sHtMl

原标题：开发记录：文件锁实现多进程互斥实践
简介：golang influxdb 时序数据库读写操作，influxdb 存储时序指标，业务指标监控数据存取。
 | 原文链接：http://book.lzrbpa.asia/blog/9273293.sHtMl

原标题：架构笔记：冷热数据分离架构设计与迁移
简介：golang tcp 四次挥手 go 程序行为，理解 tcp 四次挥手，处理连接关闭、重置、RST 包异常场景。
 | 原文链接：http://book.lzrbpa.asia/blog/5130653.sHtMl

原标题：Issue：连接池参数不合理，大量连接被耗尽
简介：开源项目本地运行排错完整清单，汇总开源项目拉取后运行失败各类问题，给出排查思路，快速解决本地启动异常。
 | 原文链接：http://book.lzrbpa.asia/blog/6913821.sHtMl

原标题：Security：反序列化漏洞风险识别与规避
简介：golang defer 执行顺序与坑点，defer 后进先出，循环内部 defer 陷阱，资源释放正确写法。
 | 原文链接：http://book.lzrbpa.asia/blog/8414056.sHtMl


二、踩坑排错｜Troubleshooting
原标题：缓存过期策略优化防业务故障
简介：golang sync.Mutex 互斥锁正确模式，互斥锁 defer Unlock，锁粒度控制，避免锁范围过大。
 | 原文链接：http://book.lzrbpa.asia/blog/4156624.sHtMl

原标题：golang 系统设计 changelog 变更日志维护
简介：数据库主从延迟业务兼容处理，业务适配主从复制延迟，避免读取从库拿到还未同步完成旧数据。
 | 原文链接：http://book.lzrbpa.asia/blog/4423666.sHtMl

原标题：项目实践：OpenTelemetry链路追踪本地部署实践
简介：golang sort 切片排序自定义 less，sort.Slice 切片快速排序，自定义 less 函数实现业务排序。
 | 原文链接：http://book.lzrbpa.asia/blog/9706929.sHtMl

原标题：golang gorm 预加载关联查询优化
简介：golang go 容器 heap 堆实现优先队列，实现 heap 接口，构建优先队列，任务优先级调度。
 | 原文链接：http://book.lzrbpa.asia/blog/8318290.sHtMl

原标题：nodejs http 服务性能调优实战
简介：golang context.WithValue 传递元数据，WithValue 只传 traceId 鉴权元数据，不要传业务大对象。
 | 原文链接：http://book.lzrbpa.asia/blog/6784108.sHtMl

原标题：golang 系统设计 jwt 安全使用避坑要点
简介：golang jwt 令牌刷新逻辑实现，实现 JWT 双令牌机制，access 短期有效 refresh 刷新令牌，实现无感续期登录。
 | 原文链接：http://book.lzrbpa.asia/blog/4538073.sHtMl

原标题：Nginx 反向代理路由配置实战
简介：GET POST 接口请求参数处理，讲解两种请求方式参数传递区别，演示参数接收、解析、校验，适配不同接口调用场景。
 | 原文链接：http://book.lzrbpa.asia/blog/1503544.sHtMl

原标题：运维笔记：系统内核参数调优生产服务器
简介：golang httptest 模拟外部 http 服务，httptest.NewServer 模拟第三方 http 服务，单元测试 mock 外部接口。
 | 原文链接：http://book.lzrbpa.asia/blog/1027795.sHtMl

原标题：实战：数据库索引设计，复合索引最佳实践
简介：网关超时时间调优后端等待，调大网关向后端转发请求超时时间，给后端业务充足处理时间。
 | 原文链接：http://book.lzrbpa.asia/blog/5159412.sHtMl

原标题：golang 系统设计 pr 评审合并完整流程
简介：golang sync.Mutex 互斥锁正确模式，互斥锁 defer Unlock，锁粒度控制，避免锁范围过大。
 | 原文链接：http://book.lzrbpa.asia/blog/7574874.sHtMl

原标题：排错：CI缓存策略错误，每次全量重新构建
简介：golang 数据库连接池参数调优详解，最大连接空闲连接最大生命周期，结合业务合理配置避免资源浪费。
 | 原文链接：http://book.lzrbpa.asia/blog/7671971.sHtMl

原标题：开发复盘：大列表内存分批读取避免OOM实践
简介：OOMKilled 容器被杀完整排查，排查容器被 OOM 终止完整流程，区分程序内存泄露和容器内存限制过小。
 | 原文链接：http://book.lzrbpa.asia/blog/1108088.sHtMl

原标题：golang 系统设计内部服务调用超时设置要点
简介：Git 子模块更新代码不全修复，正确更新 Git 子模块，拉取子模块完整代码，解决子模块目录为空问题。
 | 原文链接：http://book.lzrbpa.asia/blog/4254348.sHtMl

原标题：golang 系统设计死信队列 dlq 业务落地完整流程
简介：golang benchmark 参数‑bench‑mem 统计内存分配，benchmark 开启内存统计，观察内存分配次数大小。
 | 原文链接：http://book.lzrbpa.asia/blog/3730809.sHtMl

原标题：新手向：Mac/Windows开发环境差异踩坑
简介：golang testify testify 断言库使用，testify assert require 断言，简化单元测试断言代码。
 | 原文链接：http://book.lzrbpa.asia/blog/6424491.sHtMl

原标题：Troubleshooting：k8s镜像拉取失败镜像仓库网络问题
简介：golang 探测文件真实内容类型，读取文件头部字节判断真实文件格式，规避后缀伪造。
 | 原文链接：http://book.lzrbpa.asia/blog/4335859.sHtMl

原标题：前端防抖节流高频事件处理
简介：golang 信号量控制并发数量，使用信号量控制并发，限制同时执行任务数量，保护下游资源。
 | 原文链接：http://book.lzrbpa.asia/blog/2684385.sHtMl

原标题：Redis 分布式锁高并发安全实现
简介：golang sync.Mutex 互斥锁正确模式，互斥锁 defer Unlock，锁粒度控制，避免锁范围过大。
 | 原文链接：http://book.lzrbpa.asia/blog/4501689.sHtMl

原标题：方案对比：缓存更新策略Cache‑Aside读写模式
简介：golang 优雅处理 http 重定向逻辑，自定义控制 http 重定向跳转次数，防止无限重定向死循环。
 | 原文链接：http://book.lzrbpa.asia/blog/5906803.sHtMl

原标题：golang 系统设计 protobuf json 性能对比
简介：golang excel 生成导出高性能方案，excelize 流式生成 excel，百万行数据导出，规避内存溢出。
 | 原文链接：http://book.lzrbpa.asia/blog/0683381.sHtMl

原标题：部署复盘：容器OOM问题完整排查流程
简介：程序预加载加快服务启动速度，把高频使用资源提前预加载，减少请求阶段初始化，加快服务启动。
 | 原文链接：http://book.lzrbpa.asia/blog/7175574.sHtMl

原标题：文件编码统一随机乱码修复
简介：CORS 跨域问题多种解决方案，对比 CORS、代理等不同跨域方案优缺点，根据业务场景选择合适的跨域处理方式。
 | 原文链接：http://book.lzrbpa.asia/blog/9414675.sHtMl

原标题：golang toml 配置文件解析教程
简介：golang 分表跨表 join 查询处理方案，分表后跨分片关联查询解决方案，业务层聚合代替数据库 join。
 | 原文链接：http://book.lzrbpa.asia/blog/7194861.sHtMl

原标题：记一次字符集编码不一致乱码问题全排查
简介：golang https 客户端跳过证书校验，开发测试环境跳过 tls 证书校验，仅用于内网测试禁止生产使用。
 | 原文链接：http://book.lzrbpa.asia/blog/9035232.sHtMl

原标题：新手教程：本地项目初始化gitignore配置
简介：golang go regexp 正则预编译，regexp.MustCompile 预编译正则，不要循环内部编译正则，节省 CPU。
 | 原文链接：http://book.lzrbpa.asia/blog/5698041.sHtMl

原标题：golang k8s ingress‑nginx 配置 ssl 证书
简介：golang channel 作为函数参数方向，声明 channel 入参方向，只读 channel 只写 channel 提升代码约束。
 | 原文链接：http://book.lzrbpa.asia/blog/9787617.sHtMl

原标题：golang 系统设计 traceId 全链路透传完整方案
简介：golang 后端节点健康检查机制实现，定时探测后端节点状态，自动剔除故障节点，保障转发可用。
 | 原文链接：http://book.lzrbpa.asia/blog/6168361.sHtMl

原标题：golang elasticsearch 索引设计思路
简介：golang 路径处理 filepath 包规范写法，使用 filepath 处理路径拼接分割，自动适配操作系统路径分隔符。
 | 原文链接：http://book.lzrbpa.asia/blog/8241724.sHtMl

原标题：golang redis 分布式锁 redisson 思路
简介：golang channel 通道并发处理，讲解 Channel 用法，协程之间通过通道传递数据，做并发同步控制。
 | 原文链接：http://book.lzrbpa.asia/blog/4111311.sHtMl

原标题：Hands‑on：简易ID生成雪花算法完整实现
简介：golang k8s secret 敏感配置加载，加载 k8s secret 存储密钥密码，敏感信息不存放配置文件。
 | 原文链接：http://book.lzrbpa.asia/blog/5655451.sHtMl

原标题：golang redis 五种数据结构实战
简介：API 大版本不兼容平滑迁移，API 版本迭代不兼容旧接口，设计平滑迁移方案，逐步完成版本切换。
 | 原文链接：http://book.lzrbpa.asia/blog/5949882.sHtMl

原标题：Practice：实现批量任务失败断点续跑实践
简介：golang grafana 面板 go 业务指标可视化，prometheus 指标对接 grafana，配置监控面板可视化业务状态。
 | 原文链接：http://book.lzrbpa.asia/blog/8246231.sHtMl

原标题：golang 系统设计监控缺失指标补全完整流程
简介：golang http 文件下载断点续传服务，服务端实现断点续传，支持大文件分段下载，提升大文件下载稳定性。
 | 原文链接：http://book.lzrbpa.asia/blog/8792404.sHtMl

原标题：避坑：Nginx配置错误导致请求丢失Header
简介：golang errors.Is errors.As 错误判断，判断是否为指定错误类型，提取自定义错误信息，错误处理进阶。
 | 原文链接：http://book.lzrbpa.asia/blog/8505237.sHtMl

原标题：golang 分布式锁 redis 实现
简介：golang hertz 反向代理与负载均衡，hertz 实现反向代理，内置负载均衡，快速搭建网关类服务。
 | 原文链接：http://book.lzrbpa.asia/blog/7814197.sHtMl

原标题：golang channel 通道并发处理
简介：数据库分表存储大表优化方案，对超大数据表做分表，拆分数据，降低单表数据量提升查询性能。
 | 原文链接：http://book.lzrbpa.asia/blog/2595849.sHtMl

原标题：golang 系统设计接口向前兼容改造实操
简介：git rebase 整理提交历史实操，使用 rebase 整理杂乱提交记录，将多条提交合并，保持 git 提交历史干净线性。
 | 原文链接：http://book.lzrbpa.asia/blog/0461863.sHtMl

原标题：golang 系统设计 json 解析性能优化实操
简介：golang http client 全局变量复用，http Client 不要每次请求新建，复用 Transport 提升性能。
 | 原文链接：http://book.lzrbpa.asia/blog/6752649.sHtMl

原标题：golang redis 分布式锁 redisson 思路
简介：CLI 工具进度条交互效果开发，在命令行工具增加进度条展示，直观反馈任务执行进度，优化命令行体验。
 | 原文链接：http://book.lzrbpa.asia/blog/9354460.sHtMl

原标题：实战：Nginx负载均衡多种策略配置实践
简介：golang 容器内读取 k8s 配置 configmap，程序读取 k8s configmap 配置，配置与镜像分离便于运维。
 | 原文链接：http://book.lzrbpa.asia/blog/6647817.sHtMl

三、实战开发｜Practice
原标题：布隆过滤器误判问题修正
简介：golang 性能压测 wr 工具实操指南，wr 压测工具对 Go 接口压测，观察 QPS 延迟，定位接口性能瓶颈。
 | 原文链接：http://book.lzrbpa.asia/blog/0140264.sHtMl

原标题：golang mysql 分表自增 id 方案
简介：接口签名验签完整安全方案，一套完整接口签名方案，包含签名生成、请求携带、服务端验签校验。
 | 原文链接：http://book.lzrbpa.asia/blog/8849991.sHtMl

原标题：GC 垃圾回收优化降低 CPU 占用
简介：golang 日志输出 stdout 标准输出规范，容器环境日志输出到 stdout，由容器平台统一采集日志文件。
 | 原文链接：http://book.lzrbpa.asia/blog/2187434.sHtMl

原标题：性能调优：MySQL查询性能优化实战清单
简介：golang 数据库 ORM 框架选型对比，gorm xorm sqlx 对比各 ORM 优缺点，根据业务场景选型。
 | 原文链接：http://book.lzrbpa.asia/blog/3491807.sHtMl

原标题：golang es 索引生命周期管理思路
简介：golang gorm select 指定查询字段，指定查询字段，避免查询全部字段，减少数据传输，提升查询性能。
 | 原文链接：http://book.lzrbpa.asia/blog/5930991.sHtMl

原标题：react hooks 常见陷阱避坑指南
简介：开发环境变量配置全平台教程，区分 Windows、macOS、Linux 系统，讲解环境变量配置、加载优先级与常见失效原因。
 | 原文链接：http://book.lzrbpa.asia/blog/2565389.sHtMl

原标题：新手指南：本地多版本环境共存配置
简介：内网测试服务搭建团队调试，配置本地服务内网可访问，团队成员能够访问调试，方便前后端联调与内部演示。
 | 原文链接：http://book.lzrbpa.asia/blog/0237406.sHtMl

原标题：golang 单例模式实现几种方式
简介：golang redis 锁超时业务处理，Redis 分布式锁超时问题处理，锁续期逻辑，防止业务未完成锁提前释放。
 | 原文链接：http://book.lzrbpa.asia/blog/3884614.sHtMl

原标题：golang 系统设计容器健康检查设计思路
简介：golang httptest 模拟外部 http 服务，httptest.NewServer 模拟第三方 http 服务，单元测试 mock 外部接口。
 | 原文链接：http://book.lzrbpa.asia/blog/0698898.sHtMl

原标题：线上接口超时故障排查思路
简介：数据库索引重建提升查询速度，针对碎片化索引，重建数据库索引，恢复 SQL 查询执行性能。
 | 原文链接：http://book.lzrbpa.asia/blog/5971217.sHtMl

原标题：golang zap 日志按日期切割方案
简介：缓存穿透击穿雪崩全套防护，完整梳理缓存三大问题，落地全套防护策略，保障缓存层稳定运行。
 | 原文链接：http://book.lzrbpa.asia/blog/4847160.sHtMl

原标题：golang 系统设计缓存预热缓存降级实现
简介：golang 自定义 pprof 扩展业务指标，扩展 pprof，输出业务自定义指标，结合性能数据分析业务状态。
 | 原文链接：http://book.lzrbpa.asia/blog/1905987.sHtMl

原标题：golang 系统设计开源项目 issue pr 模板编写
简介：gitignore 文件编写过滤规则，讲解 gitignore 语法，编写过滤配置，忽略缓存、编译产物、密钥文件，保持仓库整洁。
 | 原文链接：http://book.lzrbpa.asia/blog/1572674.sHtMl

原标题：golang 灰度权重流量分发简单实现
简介：配置外部化线上部署防错误，把配置从代码剥离，外部传入配置，修改配置不需要重新打包构建。
 | 原文链接：http://book.lzrbpa.asia/blog/0504557.sHtMl

原标题：golang 项目环境变量加载方案
简介：分布式 ID 生成器高并发实现，实现高性能分布式 ID 生成器，适配高并发业务，生成全局唯一 ID。
 | 原文链接：http://book.lzrbpa.asia/blog/0325136.sHtMl

原标题：golang 分布式锁 redis 实现
简介：golang go 锁竞争导致 CPU 飙升，识别锁竞争场景，减少锁粒度，优化并发逻辑降低 CPU 开销。
 | 原文链接：http://book.lzrbpa.asia/blog/8240655.sHtMl

原标题：webpack chunk 分包策略详解
简介：golang go yaml 解析自定义类型，yaml 自定义序列化，时间、特殊类型自定义解析逻辑。
 | 原文链接：http://book.lzrbpa.asia/blog/5486919.sHtMl

原标题：golang docker compose 完整语法
简介：golang sqlx 原生 SQL 代码简化，sqlx 简化原生 SQL 结果映射结构体，兼顾性能与开发效率。
 | 原文链接：http://book.lzrbpa.asia/blog/5214687.sHtMl

原标题：Security：限流防爬虫防恶意攻击防护体系
简介：WebSocket 聊天室实时通讯开发，基于 WebSocket 搭建简易聊天室，实现多人消息广播实时聊天效果。
 | 原文链接：http://book.lzrbpa.asia/blog/3874590.sHtMl

原标题：提交第一个开源 PR 完整流程
简介：golang netlink 系统信息获取，netlink 获取系统网络信息，网卡地址，内核网络状态读取。
 | 原文链接：http://book.lzrbpa.asia/blog/3380539.sHtMl

原标题：git stash 代码暂存切换分支
简介：WebSocket 双向通信 demo 开发，搭建简易 WebSocket 服务，实现客户端服务端双向消息推送，理解实时通信原理。
 | 原文链接：http://book.lzrbpa.asia/blog/8577928.sHtMl

原标题：Docker 容器时区错误修复方案
简介：golang viper 多源配置管理实操，viper 读取配置文件环境变量命令行参数，多源配置优先级管理。
 | 原文链接：http://book.lzrbpa.asia/blog/0534968.sHtMl

原标题：架构复盘：服务优雅停机架构设计资源释放
简介：golang loki 日志收集 go 服务集成，日志输出适配 loki，标签携带 traceId，日志集中检索排查问题。
 | 原文链接：http://book.lzrbpa.asia/blog/1986010.sHtMl

原标题：Architecture：灰度、蓝绿、金丝雀发布架构对比
简介：全局异常处理器接口返回统一，接入全局异常捕获，拦截业务全部异常，对外输出统一格式返回值。
 | 原文链接：http://book.lzrbpa.asia/blog/5679865.sHtMl

原标题：golang 系统设计 vscode go 插件调试配置实操
简介：golang redis zset 实现延时任务队列，zset 存储任务到期时间，轮询到期任务执行，简易延迟队列。
 | 原文链接：http://book.lzrbpa.asia/blog/3035490.sHtMl

原标题：golang etcd 租约 lease 过期机制
简介：跨平台 uniapp 多端开发实操，uniapp 开发一套代码，编译多端，梳理多端差异处理与适配技巧。
 | 原文链接：http://book.lzrbpa.asia/blog/2697725.sHtMl

原标题：golang 分布式上下文传递方案
简介：golang grpc 服务端流推送数据，服务端流式响应，服务端持续向客户端推送多条响应消息。
 | 原文链接：http://book.lzrbpa.asia/blog/8597160.sHtMl

原标题：CLI 工具进度条交互效果开发
简介：golang 文件句柄耗尽排查处理，统计进程打开文件句柄，找到未关闭文件，修复句柄泄漏问题。
 | 原文链接：http://book.lzrbpa.asia/blog/0867267.sHtMl

原标题：实战项目：多实例部署会话一致性验证实践
简介：golang goreleaser 自动版本发布打包，goreleaser 自动化打包发布，生成多平台二进制归档文件。
 | 原文链接：http://book.lzrbpa.asia/blog/1024211.sHtMl

原标题：业务接口幂等完整落地案例
简介：golang go‑zero 配置中心热更新，go‑zero 对接 etcd 配置中心，配置热更新无需重启服务。
 | 原文链接：http://book.lzrbpa.asia/blog/7130547.sHtMl

原标题：性能调优：MySQL查询性能优化实战清单
简介：golang 压缩 zip 文件生成解压，golang 实现 zip 压缩打包，解压 zip 归档文件，处理批量文件归档。
 | 原文链接：http://book.lzrbpa.asia/blog/4347620.sHtMl

原标题：GET POST 接口请求参数处理
简介：服务器时钟同步任务错乱修复，配置服务器 NTP 时间同步，保证集群所有机器时间保持一致。
 | 原文链接：http://book.lzrbpa.asia/blog/4274582.sHtMl

原标题：Practice：实现请求ID透传全链路日志实践
简介：golang 配置热更新不重启服务，实现配置热加载，监听配置变更，更新内存配置，无需重启服务实例。
 | 原文链接：http://book.lzrbpa.asia/blog/9474335.sHtMl

原标题：golang 系统设计单元测试 mock 外部依赖技巧
简介：golang channel 作为函数参数方向，声明 channel 入参方向，只读 channel 只写 channel 提升代码约束。
 | 原文链接：http://book.lzrbpa.asia/blog/1132396.sHtMl

原标题：Performance：数据库大表优化，冷热数据分离
简介：golang bufio.Scanner 按行读取大文件，Scanner 逐行读取文本文件，处理超大日志 csv。
 | 原文链接：http://book.lzrbpa.asia/blog/9362532.sHtMl

原标题：Practice：批量异步任务处理系统设计实现
简介：HTTP 状态码请求头完整梳理，汇总常用 HTTP 状态码与请求头含义，帮助快速看懂网络请求，排查接口通信问题。
 | 原文链接：http://book.lzrbpa.asia/blog/0835037.sHtMl

原标题：实践：前后端时间格式统一规范落地实践
简介：站内邮件消息通知功能开发，实现站内消息、邮件通知推送，业务事件触发通知，提醒用户业务状态变更。
 | 原文链接：http://book.lzrbpa.asia/blog/9664815.sHtMl

原标题：Practice：模拟热点key，验证缓存防护策略
简介：golang 半关闭 tcp 连接 shutdown，tcp 连接 shutdown 半关闭，单向关闭读或者写，理解 tcp 关闭流程。
 | 原文链接：http://book.lzrbpa.asia/blog/7194124.sHtMl

原标题：设计思考：业务埋点架构日志埋点设计原则
简介：WSL 内存上限限制防止资源耗尽，修改 WSL 内存上限配置，避免 WSL 占用主机大量内存资源。
 | 原文链接：http://book.lzrbpa.asia/blog/9137791.sHtMl

原标题：golang 接口返回统一封装工具
简介：批量异步处理系统业务落地，构建批量异步处理系统，把耗时业务异步化，提升接口响应速度。
 | 原文链接：http://book.lzrbpa.asia/blog/6410276.sHtMl

四、架构设计｜Architecture
原标题：包管理器依赖缓存清理
简介：golang make new 关键字使用区别，分清 new 与 make 适用类型，正确初始化切片 map 通道，杜绝 nil 引发 panic。
 | 原文链接：http://book.lzrbpa.asia/blog/9687563.sHtMl

原标题：golang 系统设计数据库表设计通用规范模板
简介：缓存穿透防护保护数据库，实现缓存穿透防护手段，拦截不存在的数据查询，避免请求直接打穿数据库。
 | 原文链接：http://book.lzrbpa.asia/blog/8387800.sHtMl

原标题：golang 时间时区处理避坑指南
简介：rebase 操作防止代码丢失，讲解 rebase 风险点，操作前做好备份，规避错误操作造成代码提交丢失。
 | 原文链接：http://book.lzrbpa.asia/blog/7918076.sHtMl

原标题：Practice：实现简单信号处理优雅停机实践
简介：golang 图片处理 go 图片裁剪压缩，golang 图像处理库，图片缩放裁剪水印，服务端图片处理。
 | 原文链接：http://book.lzrbpa.asia/blog/0825249.sHtMl

原标题：golang 系统设计降级策略开关配置方案
简介：golang 漏桶算法实现接口限流，漏桶算法控制请求流出速率，平滑突发流量，削平流量峰值。
 | 原文链接：http://book.lzrbpa.asia/blog/7109722.sHtMl

原标题：golang 错误处理最佳实践汇总
简介：极简 API 网关路由转发实现，开发极简网关服务，完成请求路由转发，理解网关基础实现原理。
 | 原文链接：http://book.lzrbpa.asia/blog/8407863.sHtMl

原标题：golang 项目 docker compose 本地调试
简介：百万数据 Excel 导出内存优化，优化大 Excel 导出逻辑，流式输出，避免一次性加载全部数据造成 OOM。
 | 原文链接：http://book.lzrbpa.asia/blog/9497086.sHtMl

原标题：golang 系统设计分布式会话方案对比
简介：golang jwt 鉴权中间件完整示例，Gin JWT 鉴权中间件，令牌校验，解析用户信息，接口鉴权拦截。
 | 原文链接：http://book.lzrbpa.asia/blog/1951472.sHtMl

原标题：零基础理解会话、Cookie、Session基础
简介：golang 信号量 semaphore 并发限制，基于 semaphore 实现并发数量控制，保护数据库、第三方接口不被打满。
 | 原文链接：http://book.lzrbpa.asia/blog/4620979.sHtMl

原标题：Troubleshooting：数据库索引失效，查询性能暴跌
简介：golang kitex 字节微服务框架入门，kitex 开发 rpc 微服务，代码生成，服务注册发现完整流程。
 | 原文链接：http://book.lzrbpa.asia/blog/7272900.sHtMl

原标题：golang channel 通道并发处理
简介：JWT 令牌过期异常处理，捕获 JWT 过期、篡改异常，编写业务处理逻辑，引导用户重新获取令牌。
 | 原文链接：http://book.lzrbpa.asia/blog/9829587.sHtMl

原标题：GC 垃圾回收优化降低 CPU 占用
简介：Nginx 丢失请求头配置修正，修复 Nginx 代理转发丢失请求头配置，保证上游服务拿到完整请求头信息。
 | 原文链接：http://book.lzrbpa.asia/blog/3114803.sHtMl

原标题：golang 消息死信处理业务逻辑
简介：golang grpc 负载均衡客户端实现，grpc 客户端负载均衡，轮询随机权重，分发请求到多个服务实例。
 | 原文链接：http://book.lzrbpa.asia/blog/6592546.sHtMl

原标题：实践：灰度流量切分简易实现方案
简介：golang go 线上故障排查完整流程，CPU 高、内存上涨、接口超时、goroutine 泄露一套排查处理流程。
 | 原文链接：http://book.lzrbpa.asia/blog/3853909.sHtMl

原标题：golang 系统设计监控告警阈值设置思路
简介：pnpm 包管理工具实战避坑指南，使用 pnpm 管理项目依赖，梳理常见坑点，充分利用 pnpm 优势。
 | 原文链接：http://book.lzrbpa.asia/blog/9467083.sHtMl

原标题：部署实践：数据库迁移脚本版本管理实践
简介：OAuth2 第三方登录服务搭建，搭建 OAuth2 服务，支持第三方账号登录，实现授权登录能力。
 | 原文链接：http://book.lzrbpa.asia/blog/9335516.sHtMl

原标题：golang redis 网络超时参数调优
简介：golang context.Background 与 TODO 区别，Background 主流程根上下文，TODO 不确定用哪个上下文时使用。
 | 原文链接：http://book.lzrbpa.asia/blog/0570095.sHtMl

原标题：golang mysql 联合索引最左匹配
简介：golang 僵尸进程处理 go 程序，正确等待子进程退出，避免产生僵尸进程，占用系统进程表。
 | 原文链接：http://book.lzrbpa.asia/blog/6674011.sHtMl

?
