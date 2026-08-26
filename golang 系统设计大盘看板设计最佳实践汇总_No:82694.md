最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计大盘看板设计最佳实践汇总
简介：前端 pdf 预览渲染方案对比，对比前端 PDF 预览库，分析性能、兼容性，给出业务选型参考。
 | 原文链接：http://wiki.weiz0k.asia/arts/115179.Doc

原标题：golang 系统设计性能瓶颈定位完整方法论
简介：golang time duration 解析时间字符串，time.ParseDuration 解析 1h30m 时间间隔字符串。
 | 原文链接：http://wiki.weiz0k.asia/arts/292204.Doc

原标题：golang mysql limit 大分页优化
简介：golang redis scan 遍历 key 避免阻塞，使用 scan 迭代遍历 redis 键，不用 keys 命令，防止阻塞 redis 服务。
 | 原文链接：http://wiki.weiz0k.asia/arts/647177.Doc

原标题：预编译 SQL 防注入实现
简介：golang 限制 multipart 内存大小，设置 MaxMemory，大文件写入磁盘临时文件防止内存暴涨。
 | 原文链接：http://wiki.weiz0k.asia/arts/012022.Doc

原标题：golang redis 热点 key 业务规避
简介：golang sync/atomic 原子操作使用注意，理解原子操作内存顺序，规避原子操作错误使用带来 bug。
 | 原文链接：http://wiki.weiz0k.asia/arts/944924.Doc

原标题：前端打包分包加载提速方案
简介：CI 持续集成自动构建流程，讲解 CI 基础概念，配置流水线实现代码提交后自动构建、测试，提升交付自动化。
 | 原文链接：http://wiki.weiz0k.asia/arts/556817.Doc

原标题：golang k8s 命名空间资源隔离方案
简介：golang https 客户端跳过证书校验，开发测试环境跳过 tls 证书校验，仅用于内网测试禁止生产使用。
 | 原文链接：http://wiki.weiz0k.asia/arts/144221.Doc

原标题：Troubleshoot：跨库关联查询，性能急剧恶化
简介：golang mysql 事务回滚异常处理，Go MySQL 事务异常捕获，正确回滚事务，保证异常场景数据回滚。
 | 原文链接：http://wiki.weiz0k.asia/arts/376836.Doc

原标题：端口占用访问失败排查方案
简介：git cherry‑pick 规范操作防 bug，规范 cherry‑pick 使用流程，处理冲突，避免错误引入不兼容代码。
 | 原文链接：http://wiki.weiz0k.asia/arts/299491.Doc

原标题：实战项目：本地搭建Prometheus监控完整demo
简介：golang html 模板防 xss 自动转义，理解 go html/template 自动转义，防止 XSS 攻击，处理不需要转义场景。
 | 原文链接：http://wiki.weiz0k.asia/arts/249109.Doc

原标题：golang gitlab ci 配置自动构建镜像
简介：CI 流水线构建失败日志排查，阅读 CI 流水线输出日志，定位构建脚本、依赖、环境导致流水线失败问题。
 | 原文链接：http://wiki.weiz0k.asia/arts/078468.Doc

原标题：golang 系统设计灰度发布流量切分实现
简介：golang net.Conn 包装自定义连接，包装 net.Conn，统计读写字节，日志打印，超时控制。
 | 原文链接：http://wiki.weiz0k.asia/arts/296995.Doc

原标题：golang 系统设计分布式事务业务选型决策思路
简介：golang go 程序运行时动态修改配置，运行时热加载配置结构体，原子更新保证并发读取安全。
 | 原文链接：http://wiki.weiz0k.asia/arts/963388.Doc

原标题：GET POST 接口请求参数处理
简介：pnpm 包管理工具实战避坑指南，使用 pnpm 管理项目依赖，梳理常见坑点，充分利用 pnpm 优势。
 | 原文链接：http://wiki.weiz0k.asia/arts/363289.Doc

原标题：golang 系统设计内部服务契约测试简单思路
简介：golang tcp_NODELAY 关闭延迟发送，设置 tcp_NODELAY，关闭 Nagle 算法，降低小包请求延迟。
 | 原文链接：http://wiki.weiz0k.asia/arts/156103.Doc

原标题：golang 系统设计压测指标确定与分析
简介：golang select 随机分支执行特性，多个 channel 就绪 select 随机选择，理解 select 行为特性。
 | 原文链接：http://wiki.weiz0k.asia/arts/048652.Doc

原标题：golang 系统设计压力测试性能测试执行流程
简介：golang minio 私有对象存储开发，minio s3 对象存储，bucket 管理，文件上传下载权限设置。
 | 原文链接：http://wiki.weiz0k.asia/arts/789784.Doc

原标题：golang 配置文件多环境加载
简介：nodejs 集群模式多核利用实现，使用 cluster 集群模式，充分利用服务器多核 CPU，提升服务处理能力。
 | 原文链接：http://wiki.weiz0k.asia/arts/733546.Doc

原标题：开发复盘：分布式会话共享多种方案实践
简介：golang context.WithValue 传递元数据，WithValue 只传 traceId 鉴权元数据，不要传业务大对象。
 | 原文链接：http://wiki.weiz0k.asia/arts/905213.Doc

原标题：DNS 解析异常第三方调用故障
简介：golang strings 常用函数业务实战，字符串分割替换包含判断前缀后缀，掌握 strings 包高频函数。
 | 原文链接：http://wiki.weiz0k.asia/arts/594226.Doc

原标题：golang csv 读写批量数据处理
简介：开源项目本地运行排错完整清单，汇总开源项目拉取后运行失败各类问题，给出排查思路，快速解决本地启动异常。
 | 原文链接：http://wiki.weiz0k.asia/arts/780905.Doc

原标题：安全实践：请求输入校验防御恶意参数
简介：nodejs 信号处理优雅关闭服务，监听系统信号，执行资源清理，实现 Node 服务优雅停机，拒绝粗暴杀死进程。
 | 原文链接：http://wiki.weiz0k.asia/arts/335798.Doc

原标题：golang github actions 发布 release 包
简介：静态网页 HTML CSS 快速入门实战，通过简单页面案例讲解标签、样式布局，从零编写页面，理解网页基础渲染原理。
 | 原文链接：http://wiki.weiz0k.asia/arts/109550.Doc

原标题：Practice：实现多数据源动态切换组件实践
简介：golang 协程数量监控统计方案，统计运行中 goroutine 数量，监控协程泄露，协程数量异常及时告警。
 | 原文链接：http://wiki.weiz0k.asia/arts/258158.Doc

原标题：DNS 解析异常第三方调用故障
简介：系统文件描述符上限调大，调高操作系统文件描述符上限，解决高并发场景打开文件报错。
 | 原文链接：http://wiki.weiz0k.asia/arts/151858.Doc

原标题：浏览器缓存强制刷新方案
简介：程序日志分级输出规范实践，区分日志等级，规范日志打印内容，合理输出日志，方便线上问题排查定位。
 | 原文链接：http://wiki.weiz0k.asia/arts/466926.Doc

原标题：Hands‑on：代码生成器，一键生成CRUD模板
简介：前端骨架屏提升页面体验，实现页面骨架屏，数据未加载完成展示占位，优化页面白屏感知体验。
 | 原文链接：http://wiki.weiz0k.asia/arts/978174.Doc

原标题：golang websocket 消息广播实现
简介：缓存穿透防护保护数据库，实现缓存穿透防护手段，拦截不存在的数据查询，避免请求直接打穿数据库。
 | 原文链接：http://wiki.weiz0k.asia/arts/154695.Doc

原标题：优化实践：序列化框架性能对比选型实践
简介：golang 简单爬虫请求防封禁，简易 Go 爬虫实现，增加请求间隔、UA 伪装，规避被目标站点封禁 IP。
 | 原文链接：http://wiki.weiz0k.asia/arts/592892.Doc

原标题：nodejs 项目 pm2 部署运维指南
简介：golang GC 频繁 STW 停顿优化，减少小对象分配，调整 GOGC，降低 GC 停顿对接口延迟影响。
 | 原文链接：http://wiki.weiz0k.asia/arts/448481.Doc

原标题：设计思考：系统限流熔断降级完整防护体系
简介：golang testify testify 断言库使用，testify assert require 断言，简化单元测试断言代码。
 | 原文链接：http://wiki.weiz0k.asia/arts/919621.Doc

原标题：大文件导出内存溢出防护
简介：golang channel 关闭规则与坑点，关闭已经关闭 channel 会 panic，判断 channel 是否关闭正确写法。
 | 原文链接：http://wiki.weiz0k.asia/arts/188713.Doc

原标题：设计实践：如何设计可扩展业务数据库表结构
简介：golang errgroup 协程组错误处理，errgroup 捕获协程错误，context 取消剩余协程，简化并发任务。
 | 原文链接：http://wiki.weiz0k.asia/arts/974145.Doc

原标题：前端骨架屏提升页面体验
简介：golang 分布式锁防死锁实现要点，锁超时、续期、锁持有者校验，避免锁死锁，保障分布式锁可靠性。
 | 原文链接：http://wiki.weiz0k.asia/arts/535300.Doc

原标题：golang 协程泄露问题排查方法
简介：线上接口超时故障排查思路，从网络、数据库、代码逻辑逐层排查接口超时，定位慢请求根因。
 | 原文链接：http://wiki.weiz0k.asia/arts/801262.Doc

原标题：golang docker 私有仓库搭建使用
简介：golang 开发环境快速搭建指南，快速完成 Golang 开发环境配置，工具链安装，环境变量设置，准备开发。
 | 原文链接：http://wiki.weiz0k.asia/arts/737432.Doc

原标题：安全复盘：环境变量密钥泄露风险与防护
简介：golang time 时间比较 Before After Equal，时间比较不要直接减，使用内置方法判断时间先后。
 | 原文链接：http://wiki.weiz0k.asia/arts/972114.Doc

原标题：golang 系统设计分库分表本地测试调试技巧
简介：golang 灰度发布流量权重路由实现，根据权重切分流量，部分流量访问新版本服务，实现灰度发布。
 | 原文链接：http://wiki.weiz0k.asia/arts/460711.Doc

原标题：方案对比：几种任务队列架构选型优缺点
简介：前端静态缓存更新生效处理，修改静态资源版本标识，处理浏览器强缓存，让更新资源生效。
 | 原文链接：http://wiki.weiz0k.asia/arts/828637.Doc

原标题：golang 参数校验业务接口处理
简介：golang go 整洁架构代码组织实践，整洁架构依赖向内，解耦业务逻辑与外部基础设施。
 | 原文链接：http://wiki.weiz0k.asia/arts/600636.Doc


二、踩坑排错｜Troubleshooting
原标题：坑点：gitpull冲突处理不当造成代码丢失
简介：golang consul 服务发现简单示例，对接 Consul 实现服务注册发现，微服务实例自动感知。
 | 原文链接：http://wiki.weiz0k.asia/arts/415041.Doc

原标题：踩坑：批量MQ消费失败直接无限重试消息爆炸
简介：golang 协程泄露问题排查方法，识别 Go 协程泄露现象，分析泄露场景，给出排查定位协程泄露手段。
 | 原文链接：http://wiki.weiz0k.asia/arts/418350.Doc

原标题：golang 系统设计数据库版本迁移回滚方案
简介：MySQL 慢查询索引优化实战，抓取慢查询 SQL，分析执行计划，新增或者调整索引，提升 SQL 执行速度。
 | 原文链接：http://wiki.weiz0k.asia/arts/716779.Doc

原标题：Architecture：CI/CD流水线架构完整设计思考
简介：nodejs 全局异常捕获进程防护，捕获未捕获异常与 Promise 拒绝，尽量保护进程不因为异常直接退出。
 | 原文链接：http://wiki.weiz0k.asia/arts/085830.Doc

原标题：记一次分库分表路由计算错误数据写入错误分片
简介：全局本地依赖隔离冲突规避，区分全局依赖与项目本地依赖，隔离环境，防止全局包干扰项目运行。
 | 原文链接：http://wiki.weiz0k.asia/arts/590416.Doc

原标题：RPC 报文大小上限调优大请求
简介：golang grpc 客户端流上传数据，客户端流式请求，客户端分批上传数据到服务端，适合大文件传输。
 | 原文链接：http://wiki.weiz0k.asia/arts/267581.Doc

原标题：golang redis lua 脚本开发调试
简介：golang grafana 面板 go 业务指标可视化，prometheus 指标对接 grafana，配置监控面板可视化业务状态。
 | 原文链接：http://wiki.weiz0k.asia/arts/997218.Doc

原标题：简易日志收集集中管理方案
简介：golang 时间轮算法实现延时调度，手写简易时间轮，高并发大量延时任务，降低轮询 CPU 消耗。
 | 原文链接：http://wiki.weiz0k.asia/arts/635700.Doc

原标题：golang 信号捕获程序退出处理
简介：golang cgroup 读取容器资源限制，go 程序读取 cgroup，获取容器 cpu 内存限额，适配容器环境。
 | 原文链接：http://wiki.weiz0k.asia/arts/537069.Doc

原标题：开发复盘：超时参数统一治理线上服务实践
简介：golang redis 过期时间处理技巧，设置 key 过期，监控过期事件，基于过期特性实现业务缓存逻辑。
 | 原文链接：http://wiki.weiz0k.asia/arts/415707.Doc

原标题：复盘总结：线上故障完整复盘报告模板示例
简介：golang 日志脱敏敏感字段过滤，日志打印自动脱敏敏感字段，避免日志输出手机号身份证泄露隐私。
 | 原文链接：http://wiki.weiz0k.asia/arts/677526.Doc

原标题：Cookie Session 会话状态管理
简介：golang 环境变量读取与类型转换，读取系统环境变量，做类型转换默认值处理，适配多环境部署。
 | 原文链接：http://wiki.weiz0k.asia/arts/604001.Doc

原标题：Hands‑on：简易网关路由转发组件开发
简介：golang go test 单元测试命令参数详解，gotest 参数覆盖率，指定测试用例，跳过测试，单元测试命令实操。
 | 原文链接：http://wiki.weiz0k.asia/arts/906469.Doc

原标题：架构笔记：业务系统反模式架构踩坑总结
简介：golang 分布式追踪全链路日志打印，日志打印 traceId，各个服务日志可串联，排查跨服务调用问题。
 | 原文链接：http://wiki.weiz0k.asia/arts/556363.Doc

原标题：golang 系统设计监控告警体系搭建思路
简介：代理 HTTPS 证书访问异常处理，配置代理根证书，解决代理环境 HTTPS 证书校验失败无法访问外网。
 | 原文链接：http://wiki.weiz0k.asia/arts/238499.Doc

原标题：golang 系统设计混沌测试简单场景模拟实现
简介：golang base64 编码解码实操，Go Base64 编码解码示例，处理业务场景 Base64 格式数据转换。
 | 原文链接：http://wiki.weiz0k.asia/arts/637983.Doc

原标题：简易日志收集集中管理方案
简介：golang mysql 慢查询日志程序采集解析，程序读取解析 mysql 慢查询日志，统计慢 SQL 做监控告警。
 | 原文链接：http://wiki.weiz0k.asia/arts/851169.Doc

原标题：架构复盘：业务系统中如何合理使用分库分表
简介：golang mysql 慢查询日志程序采集解析，程序读取解析 mysql 慢查询日志，统计慢 SQL 做监控告警。
 | 原文链接：http://wiki.weiz0k.asia/arts/634244.Doc

原标题：安全实践：生产环境禁止开启debug调试模式
简介：Nginx 静态代理负载均衡全套配置，一套 Nginx 配置示例，覆盖静态资源、反向代理、负载均衡场景。
 | 原文链接：http://wiki.weiz0k.asia/arts/771042.Doc

原标题：开发复盘：超时参数统一治理线上服务实践
简介：golang 日志脱敏敏感字段过滤，日志打印自动脱敏敏感字段，避免日志输出手机号身份证泄露隐私。
 | 原文链接：http://wiki.weiz0k.asia/arts/415109.Doc

原标题：golang docker 镜像构建最佳实践
简介：golang go 输入数据校验防御，所有外部入参严格校验长度格式，防止恶意输入造成业务异常。
 | 原文链接：http://wiki.weiz0k.asia/arts/504769.Doc

原标题：golang 系统设计 graphql 接口优缺点梳理
简介：golang 日志级别动态调整热更新，不用重启程序动态修改日志输出级别，线上调试排查问题十分方便。
 | 原文链接：http://wiki.weiz0k.asia/arts/828187.Doc

原标题：golang 内存缓存简单实现方案
简介：golang redis pipeline 与 txpipeline 区别，区分普通管道与事务管道，根据业务场景选择合适批量执行方案。
 | 原文链接：http://wiki.weiz0k.asia/arts/655033.Doc

原标题：golang 静态文件服务搭建教程
简介：golang netlink 系统信息获取，netlink 获取系统网络信息，网卡地址，内核网络状态读取。
 | 原文链接：http://wiki.weiz0k.asia/arts/996694.Doc

原标题：golang 系统设计 grpc proto 接口设计原则
简介：golang ctx 传递规则不要存结构体，context 作为函数参数传递，禁止放入结构体字段存储。
 | 原文链接：http://wiki.weiz0k.asia/arts/185806.Doc

原标题：nodejs 读取大文件 csv 处理方案
简介：golang url 参数编码处理方案，Go URL 参数编码解码，处理特殊字符，避免 URL 参数错乱。
 | 原文链接：http://wiki.weiz0k.asia/arts/360104.Doc

原标题：golang 结构体深拷贝几种实现
简介：golang testify mock 模拟接口，mock 接口生成 mock 对象，单元测试模拟外部依赖行为。
 | 原文链接：http://wiki.weiz0k.asia/arts/997540.Doc

原标题：golang 系统设计磁盘满故障应急处理步骤
简介：JSON XML 数据解析处理示例，演示两种格式数据解析与序列化，增加异常捕获，处理格式错乱导致解析失败。
 | 原文链接：http://wiki.weiz0k.asia/arts/054172.Doc

原标题：多线程线程安全脏数据规避
简介：nodejs http 服务性能调优实战，调优 Node HTTP 服务内核参数，连接复用，提升接口并发处理能力。
 | 原文链接：http://wiki.weiz0k.asia/arts/090822.Doc

原标题：HelloDocker：编写你的第一个Dockerfile
简介：golang 数据库连接耗尽排查思路，监控连接池状态，定位连接未归还，解决连接耗尽报错。
 | 原文链接：http://wiki.weiz0k.asia/arts/418450.Doc

原标题：golang 项目目录分层规范设计
简介：前端打包产物体积压缩优化，多手段压缩前端打包产物，移除无用代码，压缩资源，提升页面加载速度。
 | 原文链接：http://wiki.weiz0k.asia/arts/715103.Doc

原标题：架构复盘：消息队列在业务系统中边界与最佳实践
简介：Git commit 钩子提交规范校验，配置 Git 提交钩子，提交代码自动校验提交信息格式，规范提交记录。
 | 原文链接：http://wiki.weiz0k.asia/arts/331026.Doc

原标题：golang kafka offset 提交策略
简介：WSL 文件权限访问异常修复，处理 WSL 环境文件权限错乱，调整权限配置，实现文件正常读写访问。
 | 原文链接：http://wiki.weiz0k.asia/arts/603944.Doc

原标题：排错：前端缓存304异常更新不及时
简介：golang atomic.Value 存储任意类型数据，atomic.Value 安全存储读取任意类型，配置热更新常用。
 | 原文链接：http://wiki.weiz0k.asia/arts/182799.Doc

原标题：golang 系统设计第三方接口 mock 单元测试
简介：前端水印防信息泄露实现，实现网页水印功能，页面叠加用户信息水印，防止页面截图信息外泄。
 | 原文链接：http://wiki.weiz0k.asia/arts/823543.Doc

原标题：golang 系统设计大表结构变更不停机方案
简介：golang smtp 邮件发送完整示例，调用 smtp 服务发送文本与 html 格式邮件，实现邮件通知能力。
 | 原文链接：http://wiki.weiz0k.asia/arts/682684.Doc

原标题：踩坑记录：浮点精度错误造成业务计算错误
简介：golang 简单爬虫请求防封禁，简易 Go 爬虫实现，增加请求间隔、UA 伪装，规避被目标站点封禁 IP。
 | 原文链接：http://wiki.weiz0k.asia/arts/471828.Doc

原标题：golang 系统设计大文件上传架构
简介：编译打包产物依赖分析解读，分析打包之后产物组成，理清运行依赖文件，排查打包后缺失文件问题。
 | 原文链接：http://wiki.weiz0k.asia/arts/186521.Doc

原标题：请求重试组件退避策略实现
简介：golang json 解析未知动态 json 结构，解析到 map [string] any 处理未知 json，动态读取字段。
 | 原文链接：http://wiki.weiz0k.asia/arts/340312.Doc

原标题：Hands‑on：静态资源CDN缓存控制头配置实践
简介：golang go 服务日志输出 journald，systemd journald 接收程序 stdout 日志，统一管理服务日志。
 | 原文链接：http://wiki.weiz0k.asia/arts/204051.Doc

三、实战开发｜Practice
原标题：排错：CI缓存策略错误，每次全量重新构建
简介：golang 高并发下锁优化减少竞争，减小锁粒度，读写锁替换互斥锁，无锁编程降低锁竞争开销。
 | 原文链接：http://wiki.weiz0k.asia/arts/437786.Doc

原标题：性能笔记：磁盘IO过高业务优化手段
简介：限流规则误拦截正常请求修复，修正限流规则阈值，避免合法用户被限流拦截，兼顾防护与可用性。
 | 原文链接：http://wiki.weiz0k.asia/arts/384452.Doc

原标题：前端权限路由动态生成实现
简介：依赖安装失败全方位排错，从网络、镜像源、权限、版本多角度，定位依赖安装失败，给出对应修复手段。
 | 原文链接：http://wiki.weiz0k.asia/arts/893373.Doc

原标题：无用对象回收抑制内存上涨
简介：看懂报错日志快速定位问题，讲解日志阅读方法，解析堆栈信息含义，学会从报错信息中定位代码出错位置。
 | 原文链接：http://wiki.weiz0k.asia/arts/940085.Doc

原标题：缓存过期策略优化防业务故障
简介：前端错误监控上报系统搭建，搭建前端错误监控，捕获页面 JS 错误，上报后端，快速发现线上页面 bug。
 | 原文链接：http://wiki.weiz0k.asia/arts/451779.Doc

原标题：避坑：Nginx配置错误导致请求丢失Header
简介：golang 字符串处理常用技巧汇总，字符串拼接、分割、替换、类型转换实操，规避字符串高频错误。
 | 原文链接：http://wiki.weiz0k.asia/arts/277462.Doc

原标题：Practice：实现接口签名、验签完整示例代码
简介：对象存储上传下载权限实操，演示对象存储文件上传、下载、访问权限设置，适配业务文件存储场景。
 | 原文链接：http://wiki.weiz0k.asia/arts/575939.Doc

原标题：HelloGitHubPages：部署你的第一个静态博客
简介：golang tcp 四次挥手 go 程序行为，理解 tcp 四次挥手，处理连接关闭、重置、RST 包异常场景。
 | 原文链接：http://wiki.weiz0k.asia/arts/558184.Doc

原标题：Issue：日志疯狂打日志快速占满磁盘空间
简介：golang go 模板缓存预编译模板，预编译 html 模板，程序启动加载，避免每次请求解析模板损耗性能。
 | 原文链接：http://wiki.weiz0k.asia/arts/086396.Doc

原标题：浮点计算精度错误处理方案
简介：golang fasthttp 服务开发完整示例，fasthttp 搭建 http 服务，路由、参数读取、响应返回完整业务。
 | 原文链接：http://wiki.weiz0k.asia/arts/846735.Doc

原标题：部署复盘：数据库主从备份恢复演练实践
简介：golang grpc 负载均衡客户端实现，grpc 客户端负载均衡，轮询随机权重，分发请求到多个服务实例。
 | 原文链接：http://wiki.weiz0k.asia/arts/972081.Doc

原标题：简易网关请求路由过滤模拟
简介：HTTPS 证书过期更新操作，检测 HTTPS 证书到期，更新证书文件，恢复 HTTPS 服务正常访问。
 | 原文链接：http://wiki.weiz0k.asia/arts/606771.Doc

原标题：调优方案：Docker容器内核参数性能调优
简介：golang base64 编码解码实操，Go Base64 编码解码示例，处理业务场景 Base64 格式数据转换。
 | 原文链接：http://wiki.weiz0k.asia/arts/360697.Doc

原标题：调优方案：服务实例扩容，水平扩展性能
简介：CI 构建缓存加速编译速度，开启 CI 流水线依赖缓存，复用上一次构建依赖包，缩短流水线构建耗时。
 | 原文链接：http://wiki.weiz0k.asia/arts/330714.Doc

原标题：AI实践：大模型生成测试用例实践与校验
简介：OAuth2 第三方登录服务搭建，搭建 OAuth2 服务，支持第三方账号登录，实现授权登录能力。
 | 原文链接：http://wiki.weiz0k.asia/arts/599483.Doc

原标题：快速入门ORM，实现简单数据库增删改查
简介：golang nil channel 阻塞特性，nil channel 读写永久阻塞，理解 nil channel 行为做逻辑控制。
 | 原文链接：http://wiki.weiz0k.asia/arts/306401.Doc

原标题：本地简易配置中心动态管理
简介：golang mqtt 客户端 go 开发物联网，paho.mqtt.golang 实现 mqtt 客户端，物联网设备消息收发。
 | 原文链接：http://wiki.weiz0k.asia/arts/926789.Doc

原标题：实战项目：本地模拟磁盘IO高负载观察服务行为
简介：golang 日志输出 stdout 标准输出规范，容器环境日志输出到 stdout，由容器平台统一采集日志文件。
 | 原文链接：http://wiki.weiz0k.asia/arts/926096.Doc

原标题：死信队列处理消息阻塞业务
简介：golang excel 生成导出高性能方案，excelize 流式生成 excel，百万行数据导出，规避内存溢出。
 | 原文链接：http://wiki.weiz0k.asia/arts/637038.Doc

原标题：架构复盘：数据库主从架构设计与延迟应对方案
简介：接口请求重试容错机制实现，封装请求重试逻辑，遇到临时网络故障自动重试，提升第三方调用稳定性。
 | 原文链接：http://wiki.weiz0k.asia/arts/884838.Doc

原标题：Practice：模拟数据库故障验证降级逻辑实践
简介：golang 性能压测 wr 工具实操指南，wr 压测工具对 Go 接口压测，观察 QPS 延迟，定位接口性能瓶颈。
 | 原文链接：http://wiki.weiz0k.asia/arts/929124.Doc

原标题：golang 系统设计开源 issue 处理回复沟通技巧
简介：配置外部化线上部署防错误，把配置从代码剥离，外部传入配置，修改配置不需要重新打包构建。
 | 原文链接：http://wiki.weiz0k.asia/arts/457168.Doc

原标题：golang grpc protobuf 开发实操
简介：golang goroutine 泄露检测告警实现，监控 goroutine 数量，突增触发告警，提早发现协程泄露。
 | 原文链接：http://wiki.weiz0k.asia/arts/907998.Doc

原标题：golang 系统设计内存瓶颈定位优化思路
简介：短信服务封装失败自动重试，封装短信发送组件，处理发送失败自动重试，兼容多短信服务商。
 | 原文链接：http://wiki.weiz0k.asia/arts/839462.Doc

原标题：golang url 参数编码处理方案
简介：分布式 ID 生成器高并发实现，实现高性能分布式 ID 生成器，适配高并发业务，生成全局唯一 ID。
 | 原文链接：http://wiki.weiz0k.asia/arts/632654.Doc

原标题：golang 系统设计技术方案文档模板参考
简介：golang pdf 生成 go 服务端生成 pdf，服务端动态生成 pdf 报表文件，直接输出下载给到前端。
 | 原文链接：http://wiki.weiz0k.asia/arts/043255.Doc

原标题：设计思考：业务系统中什么时候不要用微服务
简介：golang http client 连接池调优，调优 Go HTTP Client 连接池参数，复用 TCP 连接，减少连接创建开销。
 | 原文链接：http://wiki.weiz0k.asia/arts/823914.Doc

原标题：golang 系统设计压测指标 qps rt 错误率讲解
简介：golang alertmanager 告警配置实践，alertmanager 配置告警路由，告警发送邮件钉钉，异常及时通知运维。
 | 原文链接：http://wiki.weiz0k.asia/arts/867289.Doc

原标题：golang redis zset 延时队列实现
简介：golang kafka 同步异步消费对比，对比 Kafka 同步消费异步消费，分析优缺点，业务选型参考。
 | 原文链接：http://wiki.weiz0k.asia/arts/457202.Doc

原标题：golang 系统设计 ci 流水线安全管控思路
简介：golang yaml 解析配置加载实操，Go 解析 YAML 配置文件，读取配置参数，驱动业务运行。
 | 原文链接：http://wiki.weiz0k.asia/arts/604302.Doc

原标题：ServiceWorker 缓存页面更新清理
简介：nodejs 事件循环机制完整讲解，拆解 Node.js 事件循环各个阶段，理解异步回调执行顺序。
 | 原文链接：http://wiki.weiz0k.asia/arts/931889.Doc

原标题：golang redis lua 脚本原子操作
简介：数值类型溢出错乱问题修复，选择合适数值存储类型，处理数值溢出，避免数据存储错乱结果异常。
 | 原文链接：http://wiki.weiz0k.asia/arts/334924.Doc

原标题：复盘总结：线上故障完整复盘报告模板示例
简介：golang go 网络编程 net 包基础，net 包 tcp udp socket 编程，监听接收连接，读写数据。
 | 原文链接：http://wiki.weiz0k.asia/arts/411398.Doc

原标题：实战项目：GitSubmodule管理多仓库实践
简介：nestjs 框架模块化项目搭建，从零搭建 NestJS 项目，模块化拆分业务，搭建规范后端项目骨架。
 | 原文链接：http://wiki.weiz0k.asia/arts/600665.Doc

原标题：golang mysql innodb 事务隔离级别
简介：golang go‑zero 中间件鉴权限流，go‑zero 自定义中间件，实现鉴权、限流、日志打印通用能力。
 | 原文链接：http://wiki.weiz0k.asia/arts/526907.Doc

原标题：golang 系统设计 go benchmark 性能测试实操
简介：golang 处理连接被重置 reset 错误，识别 connection reset by peer，对端关闭连接异常处理逻辑。
 | 原文链接：http://wiki.weiz0k.asia/arts/712841.Doc

原标题：调优方案：静态资源缓存头Cache‑Control优化
简介：golang netlink 系统信息获取，netlink 获取系统网络信息，网卡地址，内核网络状态读取。
 | 原文链接：http://wiki.weiz0k.asia/arts/012028.Doc

原标题：运维笔记：系统文件句柄数调整生产配置
简介：golang 时间戳秒毫秒纳秒转换，Unix UnixMilli UnixNano 互相转换，区分单位避免时间逻辑 bug。
 | 原文链接：http://wiki.weiz0k.asia/arts/863281.Doc

原标题：hosts 配置本地回环访问修复
简介：golang 内存 dump 线上堆快照采集，线上生成内存 dump 文件，线下分析，定位内存泄漏问题。
 | 原文链接：http://wiki.weiz0k.asia/arts/666662.Doc

原标题：项目实践：多租户数据隔离三种方案实操对比
简介：golang 消息队列中间件选型对比，kafka redis‑stream rabbitmq，对比吞吐量可靠性选型参考。
 | 原文链接：http://wiki.weiz0k.asia/arts/627309.Doc

四、架构设计｜Architecture
原标题：设计思考：业务系统如何设计优雅失败架构
简介：golang go 值传递引用传递理解，go 全部为值传递，指针本质拷贝指针值，理清参数传递行为。
 | 原文链接：http://wiki.weiz0k.asia/arts/367263.Doc

原标题：静态站点自动部署发布方案
简介：golang aes cbc gcm 模式加密对比，AES‑CBC AES‑GCM 模式加密解密，理解两种模式差异选型。
 | 原文链接：http://wiki.weiz0k.asia/arts/720228.Doc

原标题：golang redis zset 延时队列实现
简介：golang sort 搜索查找切片元素，sort.Search 二分查找有序切片，快速定位元素索引位置。
 | 原文链接：http://wiki.weiz0k.asia/arts/026103.Doc

原标题：golang 系统设计测试覆盖率目标合理设定思路
简介：大事务拆分回滚日志暴涨解决，拆分大型数据库事务，减少回滚日志生成量，避免磁盘被回滚日志占满。
 | 原文链接：http://wiki.weiz0k.asia/arts/700268.Doc

原标题：部署复盘：蓝绿发布实现零停机业务更新
简介：golang make new 关键字使用区别，分清 new 与 make 适用类型，正确初始化切片 map 通道，杜绝 nil 引发 panic。
 | 原文链接：http://wiki.weiz0k.asia/arts/480239.Doc

原标题：快速入门OpenAPI文档生成基础实践
简介：全局异常处理器接口返回统一，接入全局异常捕获，拦截业务全部异常，对外输出统一格式返回值。
 | 原文链接：http://wiki.weiz0k.asia/arts/678833.Doc

原标题：方案设计：多租户系统架构三种实现模式对比
简介：golang go 程序敏感信息禁止打印日志，密钥密码禁止输出日志，防止敏感信息日志泄露。
 | 原文链接：http://wiki.weiz0k.asia/arts/758806.Doc

原标题：golang 系统设计 changelog 变更日志维护
简介：Cookie 跨环境登录配置调整，调整 Cookie 域、Secure 属性，适配开发测试生产环境，修复登录失效。
 | 原文链接：http://wiki.weiz0k.asia/arts/974105.Doc

原标题：HelloGitWorkflow：理解简单主干开发流程
简介：业务接口幂等完整落地案例，完整业务场景幂等落地示例，覆盖表单提交、回调、重试各类场景。
 | 原文链接：http://wiki.weiz0k.asia/arts/017117.Doc

原标题：坑点：gitsubmodule子模块更新失败踩坑
简介：内存溢出问题现象识别排查，识别内存溢出现象，梳理排查方向，定位内存持续上涨引发服务崩溃问题。
 | 原文链接：http://wiki.weiz0k.asia/arts/766853.Doc

原标题：MySQL 慢查询索引优化实战
简介：本地数据库开发环境搭建指南，讲解数据库安装配置、账号权限设置、连接测试，快速搭建用于开发调试的数据库实例。
 | 原文链接：http://wiki.weiz0k.asia/arts/524476.Doc

原标题：ORM 隐式慢查询问题规避
简介：服务健康检查监控接口开发，开发健康检查接口，反馈服务运行状态，供编排工具监控服务存活状态。
 | 原文链接：http://wiki.weiz0k.asia/arts/043294.Doc

原标题：系统字符集统一乱码修复
简介：golang go 优雅处理信号丢失场景，处理信号丢失、信号被忽略，保障程序可以正常接收终止信号。
 | 原文链接：http://wiki.weiz0k.asia/arts/634747.Doc

原标题：golang 容器健康检查接口开发
简介：golang sql 注入风险规避要点，参数化查询杜绝 sql 注入，禁止字符串拼接 SQL 语句执行。
 | 原文链接：http://wiki.weiz0k.asia/arts/162540.Doc

原标题：Docker 容器入门镜像实操教程
简介：golang kafka 同步异步消费对比，对比 Kafka 同步消费异步消费，分析优缺点，业务选型参考。
 | 原文链接：http://wiki.weiz0k.asia/arts/160136.Doc

原标题：golang etcd 配置中心简单使用
简介：golang http3 quic 客户端服务端示例，go 实现 http3 quic 服务端客户端，体验 quic 协议低延迟特性。
 | 原文链接：http://wiki.weiz0k.asia/arts/825242.Doc

原标题：nestjs 框架模块化项目搭建
简介：慢查询分析索引调优数据库实战，抓取慢查询，分析执行计划，优化索引，解决数据库慢查询拖慢业务。
 | 原文链接：http://wiki.weiz0k.asia/arts/427943.Doc

原标题：跨域偶现失败配置修复
简介：内存广播本地进程消息通知，实现进程内内存消息广播，进程内部模块之间事件通知解耦。
 | 原文链接：http://wiki.weiz0k.asia/arts/220527.Doc

?
