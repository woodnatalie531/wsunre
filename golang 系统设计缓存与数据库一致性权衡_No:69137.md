最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计缓存与数据库一致性权衡
简介：数据库主从延迟业务兼容处理，业务适配主从复制延迟，避免读取从库拿到还未同步完成旧数据。
 | 原文链接：www.blog.ltkbj.cn/Article/details/713411.sHtML

原标题：golang 配置热更新不重启服务
简介：golang http client 全局变量复用，http Client 不要每次请求新建，复用 Transport 提升性能。
 | 原文链接：www.blog.ltkbj.cn/Article/details/968123.sHtML

原标题：Practice：实现IP黑名单拦截中间件实践
简介：SDK 版本兼容线上崩溃修复，处理 SDK 版本升级之后线上崩溃，定位 API 变更，做版本兼容适配改造。
 | 原文链接：www.blog.ltkbj.cn/Article/details/168511.sHtML

原标题：开发记录：表单参数校验统一中间件实现
简介：golang atomic 原子操作整数，atomic 加减比较交换，无锁更新整型变量，简单计数器场景。
 | 原文链接：www.blog.ltkbj.cn/Article/details/440466.sHtML

原标题：golang proto 默认值坑点梳理
简介：代理 HTTPS 证书访问异常处理，配置代理根证书，解决代理环境 HTTPS 证书校验失败无法访问外网。
 | 原文链接：www.blog.ltkbj.cn/Article/details/524884.sHtML

原标题：运维笔记：系统文件句柄数调整生产配置
简介：golang grpc 拦截器开发鉴权日志，开发 grpc 服务端拦截器，统一做鉴权、日志打印、异常捕获处理。
 | 原文链接：www.blog.ltkbj.cn/Article/details/002537.sHtML

原标题：macOS 脚本执行权限开启
简介：大事务拆分回滚日志暴涨解决，拆分大型数据库事务，减少回滚日志生成量，避免磁盘被回滚日志占满。
 | 原文链接：www.blog.ltkbj.cn/Article/details/047378.sHtML

原标题：golang redis 缓存雪崩完整处理
简介：Git 标签版本标记发布管理，使用 Git 标签标记项目版本，打标签推送远程，用于版本发布、版本回溯。
 | 原文链接：www.blog.ltkbj.cn/Article/details/409885.sHtML

原标题：入门实践：实现简单文件读写功能
简介：golang nilnil interface 陷阱复现，interface 包含类型不为 nil 值为 nil，判 ==nil 返回 false 经典坑。
 | 原文链接：www.blog.ltkbj.cn/Article/details/524671.sHtML

原标题：HTTP 状态码请求头完整梳理
简介：golang jwt 鉴权中间件完整示例，Gin JWT 鉴权中间件，令牌校验，解析用户信息，接口鉴权拦截。
 | 原文链接：www.blog.ltkbj.cn/Article/details/898708.sHtML

原标题：golang 系统设计异步化改造业务流程思路
简介：CLI 工具进度条交互效果开发，在命令行工具增加进度条展示，直观反馈任务执行进度，优化命令行体验。
 | 原文链接：www.blog.ltkbj.cn/Article/details/827960.sHtML

原标题：日志驱动异常日志不输出修复
简介：golang html 模板防 xss 自动转义，理解 go html/template 自动转义，防止 XSS 攻击，处理不需要转义场景。
 | 原文链接：www.blog.ltkbj.cn/Article/details/746674.sHtML

原标题：golang 系统设计链路追踪核心概念 trace span 讲解
简介：golang go 零停机升级实践要点，socket 继承，流量无损，旧连接处理完毕后旧进程退出。
 | 原文链接：www.blog.ltkbj.cn/Article/details/386300.sHtML

原标题：设计思考：业务系统如何做故障隔离架构
简介：golang 系统调用跟踪 strace 排查 go 程序，strace 跟踪系统调用，定位文件网络 IO 慢的底层原因。
 | 原文链接：www.blog.ltkbj.cn/Article/details/361821.sHtML

原标题：5分钟快速搭建个人技术文档站点
简介：环境变量不生效问题修复，排查环境变量加载顺序、作用域问题，修复环境变量读取不到的异常。
 | 原文链接：www.blog.ltkbj.cn/Article/details/963916.sHtML

原标题：新手教程：Git撤销错误提交的几种常用方式
简介：后端分页查询逻辑代码实现，编写后端分页接口，处理页码、每页条数参数，优化大数据量查询返回结果。
 | 原文链接：www.blog.ltkbj.cn/Article/details/486640.sHtML

原标题：golang 项目 docker compose 本地调试
简介：项目脚手架模板生成工具，搭建项目模板脚手架，一键生成标准化项目骨架，减少重复初始化工作。
 | 原文链接：www.blog.ltkbj.cn/Article/details/025998.sHtML

原标题：踩坑记录：端口被占用导致服务启动失败
简介：golang go 线上故障排查完整流程，CPU 高、内存上涨、接口超时、goroutine 泄露一套排查处理流程。
 | 原文链接：www.blog.ltkbj.cn/Article/details/305518.sHtML

原标题：开发记录：跨域中间件完整配置与边界处理
简介：golang redis 过期键监听回调，监听 key 过期事件，过期触发业务逻辑，实现过期自动处理业务场景。
 | 原文链接：www.blog.ltkbj.cn/Article/details/746697.sHtML

原标题：踩坑记录：端口被占用导致服务启动失败
简介：golang 消息队列 kafka 消费开发，Go 开发 Kafka 消费程序，消费消息执行业务，理解 Kafka 消费逻辑。
 | 原文链接：www.blog.ltkbj.cn/Article/details/786996.sHtML

原标题：零基础理解HTTP常用请求头与状态码
简介：配置外部化线上部署防错误，把配置从代码剥离，外部传入配置，修改配置不需要重新打包构建。
 | 原文链接：www.blog.ltkbj.cn/Article/details/176255.sHtML

原标题：文件描述符优化进程卡死修复
简介：golang io.MultiReader MultiWriter 拼接流，多个 reader 拼接，多 writer 同时写入一份数据。
 | 原文链接：www.blog.ltkbj.cn/Article/details/776302.sHtML

原标题：golang 令牌桶限流中间件 gin
简介：依赖版本冲突兼容修复方案，定位依赖版本冲突根源，通过版本约束、替换包，解决版本不兼容运行报错。
 | 原文链接：www.blog.ltkbj.cn/Article/details/342926.sHtML

原标题：Hands‑on：简易配置中心本地原型实现
简介：golang 熔断降级简易组件开发，Go 简易熔断组件，下游故障触发熔断，保护上游服务不被拖垮。
 | 原文链接：www.blog.ltkbj.cn/Article/details/651888.sHtML

原标题：前端国际化多语言方案落地
简介：golang 表单文件大小限制配置，限制表单上传文件最大体积，拦截超大文件上传请求，保护服务。
 | 原文链接：www.blog.ltkbj.cn/Article/details/301204.sHtML

原标题：部署复盘：静态站点部署CDN完整流程
简介：nodejs 全局异常捕获进程防护，捕获未捕获异常与 Promise 拒绝，尽量保护进程不因为异常直接退出。
 | 原文链接：www.blog.ltkbj.cn/Article/details/961987.sHtML

原标题：部署复盘：GitHubActions完整自动化配置
简介：golang sync.Cond 条件变量使用，Cond 条件变量协程等待唤醒，复杂并发同步场景。
 | 原文链接：www.blog.ltkbj.cn/Article/details/318510.sHtML

原标题：内网 DNS 不稳定随机报错排查
简介：golang 延迟队列实现方案对比，时间轮、redis zset 实现延迟队列，处理延时执行业务。
 | 原文链接：www.blog.ltkbj.cn/Article/details/272990.sHtML

原标题：项目实践：多租户数据隔离三种方案实操对比
简介：golang go 排序 sort 包自定义排序，sort 包实现自定义排序逻辑，对切片按业务规则排序。
 | 原文链接：www.blog.ltkbj.cn/Article/details/043404.sHtML

原标题：记一次升级操作系统内核引发服务不稳定
简介：golang gorm 原生 SQL 执行处理，复杂场景执行原生 SQL，处理返回结果集，兼顾性能与灵活性。
 | 原文链接：www.blog.ltkbj.cn/Article/details/725456.sHtML

原标题：Git 误提交撤销回退实操教程
简介：数据库分表路由写入分片修正，修复分表路由逻辑，保证数据写入正确分片，不会出现数据丢失错乱。
 | 原文链接：www.blog.ltkbj.cn/Article/details/892813.sHtML

原标题：5分钟快速搭建个人技术文档站点
简介：编译打包产物依赖分析解读，分析打包之后产物组成，理清运行依赖文件，排查打包后缺失文件问题。
 | 原文链接：www.blog.ltkbj.cn/Article/details/446552.sHtML

原标题：Troubleshooting：k8s镜像拉取失败镜像仓库网络问题
简介：golang ioutil 已废弃替换方案，ioutil 废弃之后替换为 os io 包函数，更新旧项目代码。
 | 原文链接：www.blog.ltkbj.cn/Article/details/608367.sHtML

原标题：golang gorm 批量插入性能调优
简介：Cookie 跨环境登录配置调整，调整 Cookie 域、Secure 属性，适配开发测试生产环境，修复登录失效。
 | 原文链接：www.blog.ltkbj.cn/Article/details/527844.sHtML

原标题：golang 系统设计延迟消息实现几种方案对比
简介：golang rate 令牌桶限流器源码理解，拆解令牌桶限流核心逻辑，理解令牌生成消耗，掌握限流底层原理。
 | 原文链接：www.blog.ltkbj.cn/Article/details/530117.sHtML

原标题：架构复盘：系统扩容缩容架构无状态优先原则
简介：golang k8s go 服务 yaml 资源编写，k8s 部署 go 应用 deployment service，健康检查资源限制配置。
 | 原文链接：www.blog.ltkbj.cn/Article/details/520401.sHtML

原标题：开源实践：开源项目本地调试构建排坑经验
简介：GitHub Markdown 文档语法汇总，整理 Markdown 常用语法，编写仓库 README、文档，提升开源项目文档排版质量。
 | 原文链接：www.blog.ltkbj.cn/Article/details/898255.sHtML

原标题：快速入门OpenAPI文档生成基础实践
简介：golang uuid 生成多种版本实现，生成 uuid v1 v4，生成唯一标识，业务用于单据编号场景。
 | 原文链接：www.blog.ltkbj.cn/Article/details/665958.sHtML

原标题：实战项目：GitSubmodule管理多仓库实践
简介：安全组端口开放网络访问，调整服务器安全组规则，开放业务需要端口，恢复外部网络访问服务。
 | 原文链接：www.blog.ltkbj.cn/Article/details/718254.sHtML

原标题：方案对比：本地缓存vs分布式缓存架构取舍
简介：golang 时间轮算法实现延时调度，手写简易时间轮，高并发大量延时任务，降低轮询 CPU 消耗。
 | 原文链接：www.blog.ltkbj.cn/Article/details/189695.sHtML


二、踩坑排错｜Troubleshooting
原标题：项目实践：Docker镜像安全扫描本地实操
简介：golang 故障演练服务模拟超时报错，程序模拟接口超时、报错，做混沌测试验证熔断降级有效性。
 | 原文链接：www.blog.ltkbj.cn/Article/details/967103.sHtML

原标题：踩坑：大事务引发数据库连接池耗尽
简介：nodejs 内存溢出问题排查修复，Node.js 程序 OOM 排查流程，定位内存泄露，调整内存限制修复崩溃。
 | 原文链接：www.blog.ltkbj.cn/Article/details/704151.sHtML

原标题：Hands‑on：简易图片压缩处理服务demo
简介：golang proto 默认值坑点梳理，梳理 Protobuf 默认值坑，零值字段区分未赋值，避免业务逻辑错误。
 | 原文链接：www.blog.ltkbj.cn/Article/details/993998.sHtML

原标题：golang k8s 监控 prometheus 部署
简介：调试工具断点调试变量查看技巧，演示断点设置、变量监视、调用栈查看，借助调试工具高效排查业务逻辑错误。
 | 原文链接：www.blog.ltkbj.cn/Article/details/530703.sHtML

原标题：golang ci 流水线自动部署 k8s 示例
简介：golang context 超时取消实战案例，使用 context 控制协程、http 请求超时，自动终止超时任务，避免协程无限阻塞。
 | 原文链接：www.blog.ltkbj.cn/Article/details/268557.sHtML

原标题：效率笔记：GitWorkflow团队协作规范模板
简介：golang go1.18 + 泛型基础实操，go 泛型基础语法，泛型函数泛型类型，实现通用工具函数。
 | 原文链接：www.blog.ltkbj.cn/Article/details/602998.sHtML

原标题：golang http 代理客户端配置
简介：文件描述符优化进程卡死修复，及时关闭文件句柄，控制打开文件数量，解决文件句柄耗尽进程卡死。
 | 原文链接：www.blog.ltkbj.cn/Article/details/596703.sHtML

原标题：设计思考：分布式锁选型、风险、业务约束
简介：golang go 调度器 GMP 模型通俗讲解，拆解 GMP 模型，理解 goroutine M P 调度原理，看懂调度状态。
 | 原文链接：www.blog.ltkbj.cn/Article/details/102407.sHtML

原标题：golang mongodb 索引优化查询速度
简介：golang time 时间比较 Before After Equal，时间比较不要直接减，使用内置方法判断时间先后。
 | 原文链接：www.blog.ltkbj.cn/Article/details/107604.sHtML

原标题：OpenSource：开源项目版本发布CHANGELOG编写
简介：golang 协程泄露问题排查方法，识别 Go 协程泄露现象，分析泄露场景，给出排查定位协程泄露手段。
 | 原文链接：www.blog.ltkbj.cn/Article/details/120584.sHtML

原标题：消息队列重复消费业务处理
简介：golang 优雅处理 http 超时设置，Go HTTP 请求设置各类超时，防止请求无限阻塞，保护协程与连接。
 | 原文链接：www.blog.ltkbj.cn/Article/details/003736.sHtML

原标题：快速上手搭建简易内网测试服务
简介：golang defer panic 异常处理，理解 defer 延迟执行，panic 恐慌捕获，实现函数资源释放异常保护。
 | 原文链接：www.blog.ltkbj.cn/Article/details/897730.sHtML

原标题：Hands‑on：简易速率限制中间件完整实现
简介：golang http 服务并发连接数限制，自定义 listener 统计连接数量，限制最大并发连接数保护服务。
 | 原文链接：www.blog.ltkbj.cn/Article/details/819982.sHtML

原标题：golang 系统设计监控大盘故障快速定位思路
简介：golang 静态文件服务搭建教程，Go 搭建静态文件服务，托管静态资源，实现文件直接对外访问。
 | 原文链接：www.blog.ltkbj.cn/Article/details/131147.sHtML

原标题：golang 系统设计开源项目安全漏洞处理流程
简介：项目脚手架模板生成工具，搭建项目模板脚手架，一键生成标准化项目骨架，减少重复初始化工作。
 | 原文链接：www.blog.ltkbj.cn/Article/details/264598.sHtML

原标题：开发记录：短信发送服务封装，失败重试策略
简介：golang go 并发模式 or‑channel 信号合并，合并多个 done 信号，任意一个完成触发退出逻辑。
 | 原文链接：www.blog.ltkbj.cn/Article/details/747800.sHtML

原标题：Practice：实现数据库连接池简易模拟实现
简介：golang url 参数编码处理方案，Go URL 参数编码解码，处理特殊字符，避免 URL 参数错乱。
 | 原文链接：www.blog.ltkbj.cn/Article/details/341290.sHtML

原标题：效率笔记：批量处理文本命令行工具实战案例
简介：golang 雪花算法 workId 自动获取，自动获取机器 workId，不用手动配置，简化分布式 id 部署。
 | 原文链接：www.blog.ltkbj.cn/Article/details/714466.sHtML

原标题：安全复盘：Nginx配置不当带来的安全风险
简介：YAML 配置文件语法快速上手，讲解 YAML 基础语法、缩进规则，编写项目配置文件，规避语法错误引发程序异常。
 | 原文链接：www.blog.ltkbj.cn/Article/details/033631.sHtML

原标题：部署实践：内网开发环境代理配置实践
简介：Docker 网络模式容器互通设置，选择合适 Docker 网络模式，实现容器之间网络互相访问通信。
 | 原文链接：www.blog.ltkbj.cn/Article/details/672064.sHtML

原标题：手写简易 RPC 服务通信原型
简介：golang 配置文件热加载监听变更，监听配置文件改动，自动重新加载配置，业务即时生效无需重启。
 | 原文链接：www.blog.ltkbj.cn/Article/details/775663.sHtML

原标题：优化实践：异步改造同步接口提升吞吐能力
简介：分布式 ID 生成器高并发实现，实现高性能分布式 ID 生成器，适配高并发业务，生成全局唯一 ID。
 | 原文链接：www.blog.ltkbj.cn/Article/details/187719.sHtML

原标题：golang 系统设计日志本地打印线上关闭调试信息
简介：Cookie 跨环境登录配置调整，调整 Cookie 域、Secure 属性，适配开发测试生产环境，修复登录失效。
 | 原文链接：www.blog.ltkbj.cn/Article/details/820430.sHtML

原标题：nodejs 读取大文件 csv 处理方案
简介：golang 本地消息表实现最终一致性，本地消息表 + 定时任务轮询，可靠消息实现分布式事务。
 | 原文链接：www.blog.ltkbj.cn/Article/details/820189.sHtML

原标题：HelloShell：入门常用shell脚本编写
简介：golang 配置文件多环境加载，Go 多环境配置加载实现，读取配置文件环境变量，适配多套运行环境。
 | 原文链接：www.blog.ltkbj.cn/Article/details/884706.sHtML

原标题：golang 系统设计用户签到统计方案
简介：golang 分布式唯一 id 多种方案对比，雪花、redis、uuid 对比各方案优缺点，指导业务选型使用。
 | 原文链接：www.blog.ltkbj.cn/Article/details/278105.sHtML

原标题：golang 系统设计 go netpoll 多路复用简单理解
简介：golang go embed 嵌入静态资源文件，使用 go embed 把静态文件编译进二进制，单文件部署携带静态资源。
 | 原文链接：www.blog.ltkbj.cn/Article/details/018903.sHtML

原标题：Performance：大事务拆分，减少锁持有时间
简介：golang fasthttp 服务开发完整示例，fasthttp 搭建 http 服务，路由、参数读取、响应返回完整业务。
 | 原文链接：www.blog.ltkbj.cn/Article/details/302584.sHtML

原标题：项目实践：多环境配置管理组件设计与实现
简介：文件句柄耗尽资源泄露处理，定位文件句柄泄露，修复文件忘记关闭问题，解决句柄耗尽服务报错。
 | 原文链接：www.blog.ltkbj.cn/Article/details/624581.sHtML

原标题：Hands‑on：本地模拟分布式锁失效场景测试
简介：防火墙 IP 白名单回调接口放行，配置防火墙白名单，放行第三方回调服务器 IP，接收回调请求正常。
 | 原文链接：www.blog.ltkbj.cn/Article/details/306969.sHtML

原标题：项目实践：搭建监控大盘查看系统关键指标
简介：golang go 并发模式 or‑channel 信号合并，合并多个 done 信号，任意一个完成触发退出逻辑。
 | 原文链接：www.blog.ltkbj.cn/Article/details/675330.sHtML

原标题：开发记录：分布式锁超时业务安全处理实践
简介：golang consul 服务发现简单示例，对接 Consul 实现服务注册发现，微服务实例自动感知。
 | 原文链接：www.blog.ltkbj.cn/Article/details/268952.sHtML

原标题：Nginx 丢失请求头配置修正
简介：golang testify testify 断言库使用，testify assert require 断言，简化单元测试断言代码。
 | 原文链接：www.blog.ltkbj.cn/Article/details/112356.sHtML

原标题：golang 系统设计分布式任务调度
简介：golang go race 竞态检测工具，‑race 检测数据竞争，编译运行检测并发读写数据竞争 bug。
 | 原文链接：www.blog.ltkbj.cn/Article/details/909239.sHtML

原标题：Docker 容器时区错误修复方案
简介：golang 集成测试测试数据库回滚，集成测试结束自动回滚数据库，不污染测试环境数据。
 | 原文链接：www.blog.ltkbj.cn/Article/details/020742.sHtML

原标题：记一次第三方回调IP变动未更新防火墙拦截
简介：前端图片懒加载性能优化，实现图片懒加载，页面可视区域才加载图片，减少页面初始网络请求。
 | 原文链接：www.blog.ltkbj.cn/Article/details/113668.sHtML

原标题：效率笔记：调试网络请求curl命令高级用法
简介：golang 静态编译缩小镜像体积，Go 程序静态编译，不依赖系统库，产出单二进制文件，缩小镜像。
 | 原文链接：www.blog.ltkbj.cn/Article/details/882627.sHtML

原标题：Nginx 缓冲区调优大文件上传
简介：golang 滑动窗口限流算法 go 实现，滑动窗口限流，解决固定窗口临界流量突增漏洞，限流更精准。
 | 原文链接：www.blog.ltkbj.cn/Article/details/482302.sHtML

原标题：从零学习简单分页逻辑实现思路
简介：golang gin 路由分组权限管控，Gin 路由分组，不同分组绑定鉴权中间件，实现接口权限分组管控。
 | 原文链接：www.blog.ltkbj.cn/Article/details/668297.sHtML

原标题：方案对比：同步事务vs事务消息最终一致性
简介：golang defer panic 异常处理，理解 defer 延迟执行，panic 恐慌捕获，实现函数资源释放异常保护。
 | 原文链接：www.blog.ltkbj.cn/Article/details/662984.sHtML

三、实战开发｜Practice
原标题：记一次限流组件误配置把正常用户拦截
简介：golang sort 切片排序自定义 less，sort.Slice 切片快速排序，自定义 less 函数实现业务排序。
 | 原文链接：www.blog.ltkbj.cn/Article/details/291143.sHtML

原标题：SourceMap 生成线上报错定位
简介：golang sync/atomic 原子操作使用注意，理解原子操作内存顺序，规避原子操作错误使用带来 bug。
 | 原文链接：www.blog.ltkbj.cn/Article/details/613208.sHtML

原标题：golang 系统设计线程协程泄露定位方法
简介：golang go 程序版本号内置编译注入，编译时注入 git commit 版本号，程序运行输出版本便于排查。
 | 原文链接：www.blog.ltkbj.cn/Article/details/900224.sHtML

原标题：Redis 内存淘汰策略数据防丢失
简介：业务错误码体系设计方案，设计项目统一错误码，区分不同业务异常，标准化错误返回，便于前端识别处理。
 | 原文链接：www.blog.ltkbj.cn/Article/details/053737.sHtML

原标题：Debug：预加载逻辑错误服务启动时间成倍拉长
简介：浏览器缓存强制刷新方案，设置 HTTP 缓存头，处理浏览器缓存旧静态资源，让用户加载更新后的页面。
 | 原文链接：www.blog.ltkbj.cn/Article/details/507019.sHtML

原标题：golang go test 覆盖率统计实操
简介：golang 异步任务队列 worker 池开发，任务入数据库或 redis，worker 池消费执行，异步处理耗时业务。
 | 原文链接：www.blog.ltkbj.cn/Article/details/413269.sHtML

原标题：踩坑：环境变量未生效导致线上配置错乱
简介：golang gorm 子查询嵌套查询写法，Gorm 实现子查询、嵌套查询，复杂条件查询简化代码编写。
 | 原文链接：www.blog.ltkbj.cn/Article/details/497375.sHtML

原标题：安全复盘：OAuth2授权流程安全坑点汇总
简介：golang sync.Once 只执行一次，sync.Once 做单例初始化，保证代码只执行一次，并发安全。
 | 原文链接：www.blog.ltkbj.cn/Article/details/786845.sHtML

原标题：golang 系统设计 http 接口基准测试实操示例
简介：本地运行正常线上报错排查，对比本地与线上环境差异，从配置、系统版本、文件权限定位线上独有的 bug。
 | 原文链接：www.blog.ltkbj.cn/Article/details/354632.sHtML

原标题：业务接口幂等完整落地案例
简介：golang 限流器熔断降级组合使用，限流熔断降级组合架构，流量防护完整方案，保障服务稳定性。
 | 原文链接：www.blog.ltkbj.cn/Article/details/721656.sHtML

原标题：golang 系统设计配置热更新不重启服务实现
简介：nestjs 权限守卫鉴权实现方案，使用 Nest 守卫实现接口鉴权，角色权限控制，拦截未授权接口访问。
 | 原文链接：www.blog.ltkbj.cn/Article/details/098864.sHtML

原标题：SDK 版本兼容线上崩溃修复
简介：golang 数据库连接池参数调优详解，最大连接空闲连接最大生命周期，结合业务合理配置避免资源浪费。
 | 原文链接：www.blog.ltkbj.cn/Article/details/880500.sHtML

原标题：安全复盘：业务接口越权测试与修复实践
简介：前后端会话登录状态持久化，实现登录状态持久存储，重启服务登录状态不丢失，保障会话稳定性。
 | 原文链接：www.blog.ltkbj.cn/Article/details/901485.sHtML

原标题：踩坑：消息队列消息堆积，消费者处理能力不足
简介：TLS 版本兼容 HTTPS 握手失败，兼容老旧 TLS 协议版本，修复部分客户端 HTTPS 握手失败无法访问。
 | 原文链接：www.blog.ltkbj.cn/Article/details/209912.sHtML

原标题：golang 系统设计海量数据分页查询
简介：操作系统内核版本适配服务，针对服务运行要求，适配操作系统内核版本，规避内核兼容 bug。
 | 原文链接：www.blog.ltkbj.cn/Article/details/961668.sHtML

原标题：Hands‑on：简易短消息模板渲染组件实践
简介：golang 日志级别动态调整热更新，不用重启程序动态修改日志输出级别，线上调试排查问题十分方便。
 | 原文链接：www.blog.ltkbj.cn/Article/details/228125.sHtML

原标题：Troubleshooting：数据库主从延迟带来查询数据不一致
简介：golang grpc 负载均衡客户端实现，grpc 客户端负载均衡，轮询随机权重，分发请求到多个服务实例。
 | 原文链接：www.blog.ltkbj.cn/Article/details/127796.sHtML

原标题：入门实践：项目配置文件多环境管理方案
简介：TCP 长连接参数优化 TIME_WAIT，调整 TCP 内核参数，优化长连接，减少大量 TIME_WAIT 连接占用资源。
 | 原文链接：www.blog.ltkbj.cn/Article/details/914466.sHtML

原标题：运维笔记：系统内核参数调优生产服务器
简介：分布式任务调度集群原型开发，开发简易分布式调度原型，集群多节点运行，保证任务只执行一次。
 | 原文链接：www.blog.ltkbj.cn/Article/details/553699.sHtML

原标题：golang k8s 日志收集 efk 简单架构
简介：golang arp 缓存读取操作，读取系统 arp 缓存表，获取 ip 对应的 mac 地址信息。
 | 原文链接：www.blog.ltkbj.cn/Article/details/312393.sHtML

原标题：golang 优雅处理 http 超时设置
简介：golang docker 多阶段构建 go 镜像，Go 项目 Docker 多阶段构建，编译与运行阶段分离，大幅度缩减最终镜像体积，提升镜像分发效率。
 | 原文链接：www.blog.ltkbj.cn/Article/details/568448.sHtML

原标题：golang grafana 面板变量模板制作
简介：批量数据处理脚本编写技巧，编写脚本批量处理大量业务数据，循环处理、分批执行，提升数据处理效率。
 | 原文链接：www.blog.ltkbj.cn/Article/details/372524.sHtML

原标题：CI 流水线构建失败日志排查
简介：golang 处理连接被重置 reset 错误，识别 connection reset by peer，对端关闭连接异常处理逻辑。
 | 原文链接：www.blog.ltkbj.cn/Article/details/221479.sHtML

原标题：文件描述符优化进程卡死修复
简介：包管理器依赖缓存清理，清理本地依赖缓存，解决缓存旧包引发问题，拉取最新版本依赖包。
 | 原文链接：www.blog.ltkbj.cn/Article/details/260661.sHtML

原标题：golang 系统设计单元测试 mock 外部依赖技巧
简介：golang go 线上故障排查完整流程，CPU 高、内存上涨、接口超时、goroutine 泄露一套排查处理流程。
 | 原文链接：www.blog.ltkbj.cn/Article/details/827142.sHtML

原标题：golang 系统设计技术文档编写最佳实践
简介：golang go 优雅处理信号丢失场景，处理信号丢失、信号被忽略，保障程序可以正常接收终止信号。
 | 原文链接：www.blog.ltkbj.cn/Article/details/775296.sHtML

原标题：性能复盘：网络IO优化减少接口等待时间
简介：浏览器内存泄漏排查前端页面，梳理前端页面内存泄漏场景，讲解排查手段，修复页面内存持续上涨。
 | 原文链接：www.blog.ltkbj.cn/Article/details/635145.sHtML

原标题：golang mysql 索引失效常见场景
简介：golang 工具函数库封装思路，Go 通用工具库封装思路，错误处理、类型转换，业务项目复用工具代码。
 | 原文链接：www.blog.ltkbj.cn/Article/details/417289.sHtML

原标题：记一次日志切割脚本错误直接清空业务日志
简介：内存广播本地进程消息通知，实现进程内内存消息广播，进程内部模块之间事件通知解耦。
 | 原文链接：www.blog.ltkbj.cn/Article/details/486655.sHtML

原标题：安全复盘：CSRF跨站请求伪造防护配置
简介：golang 探测文件真实内容类型，读取文件头部字节判断真实文件格式，规避后缀伪造。
 | 原文链接：www.blog.ltkbj.cn/Article/details/520585.sHtML

原标题：从零学习简单分布式ID生成思路
简介：golang rsa 签名验签 pem 证书加载，加载 pem 格式密钥证书，rsa 签名与验签完整业务实现。
 | 原文链接：www.blog.ltkbj.cn/Article/details/926036.sHtML

原标题：golang 系统设计分布式任务调度
简介：golang gorm 索引设置与优化技巧，定义数据库索引，理解索引生效条件，避免索引失效慢查询。
 | 原文链接：www.blog.ltkbj.cn/Article/details/572888.sHtML

原标题：Issue：Nginxkeepalive参数不合理大量TIME_WAIT
简介：golang k8s secret 敏感配置加载，加载 k8s secret 存储密钥密码，敏感信息不存放配置文件。
 | 原文链接：www.blog.ltkbj.cn/Article/details/633034.sHtML

原标题：DevOps：CI构建产物缓存复用加速编译
简介：nodejs 定时任务生产环境避坑，Node 定时任务线上踩坑汇总，集群重复执行、任务阻塞等问题解决方案。
 | 原文链接：www.blog.ltkbj.cn/Article/details/003479.sHtML

原标题：架构复盘：慢查询治理架构层面优化手段
简介：golang 响应 body 流式返回大数据，http 流式输出数据，边生成边返回，无需在内存组装完整返回结果。
 | 原文链接：www.blog.ltkbj.cn/Article/details/869988.sHtML

原标题：golang 系统设计本地缓存更新失效方案实现
简介：SDK 版本兼容线上崩溃修复，处理 SDK 版本升级之后线上崩溃，定位 API 变更，做版本兼容适配改造。
 | 原文链接：www.blog.ltkbj.cn/Article/details/100149.sHtML

原标题：﻿【GettingStarted】从零搭建本地开发环境完整指南
简介：开源项目构建失败排查步骤，梳理构建报错排查流程，从依赖、网络、权限、脚本多角度定位项目构建失败原因。
 | 原文链接：www.blog.ltkbj.cn/Article/details/121144.sHtML

原标题：golang 系统设计数据脱敏架构实现
简介：golang go‑zero 监控指标埋点，go‑zero 内置 metrics 监控，上报业务指标对接监控平台。
 | 原文链接：www.blog.ltkbj.cn/Article/details/998595.sHtML

原标题：golang 数据库连接泄露排查
简介：golang context 超时取消实战案例，使用 context 控制协程、http 请求超时，自动终止超时任务，避免协程无限阻塞。
 | 原文链接：www.blog.ltkbj.cn/Article/details/938958.sHtML

原标题：HelloMarkdown：GitHubMarkdown完整语法速查
简介：golang 日志级别动态调整热更新，不用重启程序动态修改日志输出级别，线上调试排查问题十分方便。
 | 原文链接：www.blog.ltkbj.cn/Article/details/843397.sHtML

四、架构设计｜Architecture
原标题：安全复盘：消息队列未授权访问安全加固
简介：golang context 上下文传参讲解，讲解 Context 使用场景，传递元数据、控制协程超时取消，规范协程控制。
 | 原文链接：www.blog.ltkbj.cn/Article/details/398070.sHtML

原标题：golang 系统设计数据库连接池调优实践
简介：golang 限制 multipart 内存大小，设置 MaxMemory，大文件写入磁盘临时文件防止内存暴涨。
 | 原文链接：www.blog.ltkbj.cn/Article/details/386773.sHtML

原标题：golang http client 连接池调优
简介：不必要字符转义关闭业务异常，关闭多余自动转义逻辑，防止业务数据被错误转义，破坏原始数据。
 | 原文链接：www.blog.ltkbj.cn/Article/details/591547.sHtML

原标题：快速入门Nginx基础配置，反向代理示例
简介：nodejs http 服务性能调优实战，调优 Node HTTP 服务内核参数，连接复用，提升接口并发处理能力。
 | 原文链接：www.blog.ltkbj.cn/Article/details/782966.sHtML

原标题：前端骨架屏提升页面体验
简介：golang context.WithTimeout 超时上下文，WithTimeout 设置超时时间，超时自动 cancel 释放协程。
 | 原文链接：www.blog.ltkbj.cn/Article/details/866791.sHtML

原标题：快速入门gRPC基础概念与简单示例
简介：golang gorm select 指定查询字段，指定查询字段，避免查询全部字段，减少数据传输，提升查询性能。
 | 原文链接：www.blog.ltkbj.cn/Article/details/221062.sHtML

原标题：golang docker 多阶段构建 go 镜像
简介：golang benchmark 减少测试干扰，benchmark 执行循环 b.N，避免循环内部做非被测逻辑干扰结果。
 | 原文链接：www.blog.ltkbj.cn/Article/details/369322.sHtML

原标题：golang alertmanager 钉钉告警推送
简介：golang go 逃逸分析实操查看，go build‑gcflags=-m 查看逃逸分析，减少堆分配优化程序性能。
 | 原文链接：www.blog.ltkbj.cn/Article/details/196558.sHtML

原标题：项目实践：OpenTelemetry链路追踪本地部署实践
简介：nodejs 多进程任务分发处理，多进程拆分处理 CPU 密集任务，主进程分发任务，利用多核提升处理速度。
 | 原文链接：www.blog.ltkbj.cn/Article/details/743959.sHtML

原标题：golang http 服务性能优化调参
简介：golang json 自定义 MarshalJSON UnmarshalJSON，自定义 json 序列化反序列化逻辑，处理特殊格式字段。
 | 原文链接：www.blog.ltkbj.cn/Article/details/710004.sHtML

原标题：golang 布隆过滤器实现去重
简介：golang 正则表达式 Go 实操案例，正则匹配提取替换，处理手机号邮箱校验，规避正则回溯 CPU 暴涨。
 | 原文链接：www.blog.ltkbj.cn/Article/details/088300.sHtML

原标题：golang 项目目录分层规范设计
简介：ORM 框架数据库增删改查实操，使用 ORM 框架完成数据库基础操作，减少手写 SQL，简化业务层数据库交互代码。
 | 原文链接：www.blog.ltkbj.cn/Article/details/111789.sHtML

原标题：golang etcd watch 监听配置变更
简介：限流规则误拦截正常请求修复，修正限流规则阈值，避免合法用户被限流拦截，兼顾防护与可用性。
 | 原文链接：www.blog.ltkbj.cn/Article/details/039290.sHtML

原标题：记一次第三方SDK版本兼容引发线上故障
简介：移动端适配 rem vw 方案对比，对比 rem 与 vw 移动端适配方案，分析优缺点，给出选型建议。
 | 原文链接：www.blog.ltkbj.cn/Article/details/853636.sHtML

原标题：golang etcd 租约 lease 过期机制
简介：golang md5 sha 加密工具实现，实现 MD5、SHA 哈希工具，做数据摘要，用于签名校验场景。
 | 原文链接：www.blog.ltkbj.cn/Article/details/998425.sHtML

原标题：序列化版本不一致解析失败
简介：Spring 事务传播机制配置生效，理解事务传播行为，正确配置，修复事务不生效、事务失效的业务 bug。
 | 原文链接：www.blog.ltkbj.cn/Article/details/608119.sHtML

原标题：golang mysql 读写分离简单实现
简介：golang json 自定义 MarshalJSON UnmarshalJSON，自定义 json 序列化反序列化逻辑，处理特殊格式字段。
 | 原文链接：www.blog.ltkbj.cn/Article/details/638416.sHtML

原标题：DNS TTL 配置域名切换生效
简介：golang os/exec 安全执行外部命令，规避命令注入漏洞，参数分离，禁止拼接命令字符串执行。
 | 原文链接：www.blog.ltkbj.cn/Article/details/332119.sHtML

原标题：golang kafka 死信队列业务落地
简介：数据库主从延迟业务兼容处理，业务适配主从复制延迟，避免读取从库拿到还未同步完成旧数据。
 | 原文链接：www.blog.ltkbj.cn/Article/details/180607.sHtML

原标题：前端骨架屏提升页面体验
简介：golang redis bitmap 位图业务实战，bitmap 做签到统计、用户状态标记，节省大量内存空间。
 | 原文链接：www.blog.ltkbj.cn/Article/details/535946.sHtML

原标题：golang 文件上传下载接口开发
简介：golang go 测试 t.Run 子测试分组，t.Run 实现子测试，分组执行用例，输出分组测试结果。
 | 原文链接：www.blog.ltkbj.cn/Article/details/100161.sHtML

原标题：golang 系统设计 mq 消息重复消费处理
简介：golang 本地消息表实现最终一致性，本地消息表 + 定时任务轮询，可靠消息实现分布式事务。
 | 原文链接：www.blog.ltkbj.cn/Article/details/765812.sHtML

原标题：前端错误监控上报系统搭建
简介：nodejs 脚手架工具开发完整教程，从零开发 Node 命令行脚手架，实现项目模板生成，理解 CLI 开发。
 | 原文链接：www.blog.ltkbj.cn/Article/details/301299.sHtML

原标题：新手参与开源社区贡献指南
简介：golang url 解析路径参数提取，url.Parse 解析 url，获取协议主机路径查询参数。
 | 原文链接：www.blog.ltkbj.cn/Article/details/308088.sHtML

原标题：golang 系统设计自动化测试 ci 流水线集成实操
简介：Spring 事务传播机制配置生效，理解事务传播行为，正确配置，修复事务不生效、事务失效的业务 bug。
 | 原文链接：www.blog.ltkbj.cn/Article/details/231785.sHtML

原标题：golang 文件上传下载接口开发
简介：golang sqlx 原生 SQL 代码简化，sqlx 简化原生 SQL 结果映射结构体，兼顾性能与开发效率。
 | 原文链接：www.blog.ltkbj.cn/Article/details/110963.sHtML

原标题：Hands‑on：简易代理服务器开发实践
简介：golang cobra 命令行参数配置绑定，cobra 绑定配置文件环境变量命令行参数，多源配置合并。
 | 原文链接：www.blog.ltkbj.cn/Article/details/427042.sHtML

原标题：Practice：模拟数据库故障验证降级逻辑实践
简介：golang go 爬虫请求速率控制，爬虫限频、代理轮换，设置 UA，防止爬虫被目标站点封禁 IP。
 | 原文链接：www.blog.ltkbj.cn/Article/details/784711.sHtML

原标题：golang docker 部署 kafka 本地调试
简介：golang hertz http 框架快速上手，hertz 高性能 http 框架，路由中间件参数校验快速开发接口服务。
 | 原文链接：www.blog.ltkbj.cn/Article/details/992401.sHtML

原标题：坑点：Git工作区换行符CRLF/LF跨平台坑
简介：golang 程序崩溃 core dump 生成调试，开启 core dump，程序崩溃生成转储文件，事后分析崩溃原因。
 | 原文链接：www.blog.ltkbj.cn/Article/details/371419.sHtML

原标题：eslint prettier 代码规范落地
简介：Redis 热点 key 拆分降低集群压力，拆分访问量极高的热点 Key，分散请求压力，避免 Redis 节点压力过高。
 | 原文链接：www.blog.ltkbj.cn/Article/details/526527.sHtML

原标题：慢查询分析索引调优数据库实战
简介：golang go 死锁检测工具，静态检查、运行检测，发现 channel 锁导致死锁问题。
 | 原文链接：www.blog.ltkbj.cn/Article/details/820702.sHtML

原标题：golang 系统设计接口幂等架构设计
简介：golang go 代码覆盖率线上统计，单元测试覆盖率统计，找出未测试代码分支，提升测试质量。
 | 原文链接：www.blog.ltkbj.cn/Article/details/072821.sHtML

原标题：golang 定时任务 cron 使用指南
简介：Docker 网络模式容器互通设置，选择合适 Docker 网络模式，实现容器之间网络互相访问通信。
 | 原文链接：www.blog.ltkbj.cn/Article/details/932427.sHtML

原标题：golang 系统设计 api 网关核心能力完整梳理
简介：golang go xml 解析生成 xml 文档，encoding/xml 解析 xml，结构体标签映射 xml 节点属性。
 | 原文链接：www.blog.ltkbj.cn/Article/details/932820.sHtML

原标题：新手教程：gitstash暂存工作区变更实操
简介：数据库死锁成因规避方案，讲解数据库死锁产生条件，给出业务层面规避手段，减少死锁事件发生。
 | 原文链接：www.blog.ltkbj.cn/Article/details/360339.sHtML

原标题：项目实践：消息队列消息堆积模拟处理实践
简介：golang 数据库慢查询监控实现，Go 封装 SQL 执行监控，记录慢 SQL，上报日志，发现数据库性能问题。
 | 原文链接：www.blog.ltkbj.cn/Article/details/608856.sHtML

原标题：部署实践：Nginx反向代理传递真实客户端IP
简介：golang gitlab ci go 项目流水线编写，gitlab ci 流水线执行单元测试、静态检查、构建推送镜像。
 | 原文链接：www.blog.ltkbj.cn/Article/details/749822.sHtML

原标题：实践：灰度流量切分简易实现方案
简介：编译打包产物依赖分析解读，分析打包之后产物组成，理清运行依赖文件，排查打包后缺失文件问题。
 | 原文链接：www.blog.ltkbj.cn/Article/details/602299.sHtML

原标题：golang 系统设计内存复用 sync.pool 使用
简介：golang redis lua 脚本原子操作，使用 Lua 脚本实现原子逻辑，减少网络往返，保障多命令原子执行。
 | 原文链接：www.blog.ltkbj.cn/Article/details/267055.sHtML

五、文体娱乐
原标题：方案对比：本地缓存vs分布式缓存架构取舍
简介：JWT 令牌过期异常处理，捕获 JWT 过期、篡改异常，编写业务处理逻辑，引导用户重新获取令牌。
 | 原文链接：www.blog.ltkbj.cn/Article/details/958401.sHtML

原标题：golang grafana 面板变量模板制作
简介：nodejs 多进程任务分发处理，多进程拆分处理 CPU 密集任务，主进程分发任务，利用多核提升处理速度。
 | 原文链接：www.blog.ltkbj.cn/Article/details/024628.sHtML

原标题：golang 系统设计日志脱敏防止信息泄露
简介：golang errors.Is errors.As 错误判断，判断是否为指定错误类型，提取自定义错误信息，错误处理进阶。
 | 原文链接：www.blog.ltkbj.cn/Article/details/227715.sHtML

原标题：设计思考：系统幂等性整体架构层面保障
简介：golang redis bitmap 位图业务实战，bitmap 做签到统计、用户状态标记，节省大量内存空间。
 | 原文链接：www.blog.ltkbj.cn/Article/details/671597.sHtML

原标题：实践：多配置文件合并加载组件实现
简介：Docker 容器入门镜像实操教程，介绍 Docker 基础概念，演示镜像拉取、容器启停，帮助新手建立容器化开发认知。
 | 原文链接：www.blog.ltkbj.cn/Article/details/483014.sHtML

原标题：golang 系统设计敏感数据加密存储方案
简介：golang e2e 端到端测试 go 接口，编写 e2e 测试，完整模拟用户请求，校验整套业务链路正确性。
 | 原文链接：www.blog.ltkbj.cn/Article/details/255661.sHtML

原标题：golang channel 通道并发处理
简介：golang go mod tidy 依赖清理，go mod tidy 自动增删依赖，整理 go.mod go.sum 文件。
 | 原文链接：www.blog.ltkbj.cn/Article/details/711525.sHtML

原标题：Performance：数据库索引优化常见错误案例
简介：golang go 服务蓝绿发布实践思路，蓝绿两套实例，流量一键切换，回滚快速降低发布风险。
 | 原文链接：www.blog.ltkbj.cn/Article/details/371588.sHtML

原标题：Redis 热点 key 拆分降低集群压力
简介：golang 数据库分表策略按时间分片，按时间维度分表，历史数据拆分，单表数据量控制保证查询性能。
 | 原文链接：www.blog.ltkbj.cn/Article/details/220710.sHtML

原标题：安全实践：SQL注入产生场景与完整防御手段
简介：批量操作分批处理防止 OOM，大批量数据处理不一次性加载全部数据，分批循环处理，避免内存溢出。
 | 原文链接：www.blog.ltkbj.cn/Article/details/713071.sHtML

原标题：快速入门gRPC基础概念与简单示例
简介：golang make new 关键字使用区别，分清 new 与 make 适用类型，正确初始化切片 map 通道，杜绝 nil 引发 panic。
 | 原文链接：www.blog.ltkbj.cn/Article/details/994841.sHtML

原标题：Cookie Session 会话状态管理
简介：文件句柄上限调整上传随机失败，调高系统文件句柄上限，解决高并发上传场景随机打开文件失败。
 | 原文链接：www.blog.ltkbj.cn/Article/details/660077.sHtML

原标题：echarts 大数据渲染性能调优
简介：nodejs 集群模式多核利用实现，使用 cluster 集群模式，充分利用服务器多核 CPU，提升服务处理能力。
 | 原文链接：www.blog.ltkbj.cn/Article/details/262592.sHtML

原标题：包管理器依赖冲突解决方案
简介：golang url 解析路径参数提取，url.Parse 解析 url，获取协议主机路径查询参数。
 | 原文链接：www.blog.ltkbj.cn/Article/details/661787.sHtML

原标题：Practice：实现简单信号处理优雅停机实践
简介：golang strings.Builder 字符串高效拼接，strings.Builder 做字符串拼接，比 += 性能更高，减少内存拷贝。
 | 原文链接：www.blog.ltkbj.cn/Article/details/656275.sHtML

原标题：模拟登录鉴权权限判断示例
简介：golang interface 接口使用避坑，interface 判 nil 坑点，理解接口底层结构，避免判空逻辑失效。
 | 原文链接：www.blog.ltkbj.cn/Article/details/294889.sHtML

原标题：线上异常：时间时区问题，定时任务执行偏移
简介：消息队列消费堆积扩容处理，消息大量堆积时，扩容消费实例，优化消费逻辑，加快消息处理速度。
 | 原文链接：www.blog.ltkbj.cn/Article/details/954430.sHtML

原标题：项目构建脚本编译打包解析
简介：前端下载导出文件功能实现，前端实现文件流下载导出，处理异常，适配浏览器不同下载行为。
 | 原文链接：www.blog.ltkbj.cn/Article/details/889556.sHtML

原标题：优化实践：Redis性能调优，避免大key热key
简介：golang go yaml 解析自定义类型，yaml 自定义序列化，时间、特殊类型自定义解析逻辑。
 | 原文链接：www.blog.ltkbj.cn/Article/details/002958.sHtML

原标题：部署复盘：容器OOM问题完整排查流程
简介：golang gin 路由分组权限管控，Gin 路由分组，不同分组绑定鉴权中间件，实现接口权限分组管控。
 | 原文链接：www.blog.ltkbj.cn/Article/details/770675.sHtML

原标题：golang 系统设计测试覆盖率目标合理设定思路
简介：golang 命令行交互 cobra 开发 cli，cobra 库开发功能完善命令行工具，子命令参数标志解析。
 | 原文链接：www.blog.ltkbj.cn/Article/details/998109.sHtML

原标题：安全笔记：依赖包漏洞检测供应链安全
简介：golang go 程序 CPU 占用高定位步骤，pprof 定位热点函数，分析 CPU 高占用，优化耗时代码逻辑。
 | 原文链接：www.blog.ltkbj.cn/Article/details/924735.sHtML

原标题：主干开发团队代码合并策略
简介：golang lru 缓存淘汰算法编写，手写 LRU 缓存淘汰算法，实现本地缓存，淘汰最久未使用数据。
 | 原文链接：www.blog.ltkbj.cn/Article/details/846110.sHtML

原标题：golang minio 对象存储接口开发
简介：golang http 文件下载断点续传服务，服务端实现断点续传，支持大文件分段下载，提升大文件下载稳定性。
 | 原文链接：www.blog.ltkbj.cn/Article/details/824405.sHtML

原标题：golang mysql 联合索引最左匹配
简介：极简方式搭建个人技术文档站点，使用轻量化工具快速部署文档站点，支持 markdown 编写，实现知识沉淀与对外分享。
 | 原文链接：www.blog.ltkbj.cn/Article/details/965189.sHtML

原标题：golang es 批量 bulk 操作性能调优
简介：静态博客部署 GitHub Pages 教程，将静态博客项目部署至 GitHub Pages，完成线上访问，快速搭建个人技术博客站点。
 | 原文链接：www.blog.ltkbj.cn/Article/details/050760.sHtML

原标题：CI 构建缓存加速编译速度
简介：用户敏感数据脱敏代码实现，编写数据脱敏工具，对手机号、身份证做脱敏处理，防止敏感信息直接泄露。
 | 原文链接：www.blog.ltkbj.cn/Article/details/453442.sHtML

原标题：性能复盘：慢SQL定位、分析、改写完整案例
简介：全局本地依赖隔离冲突规避，区分全局依赖与项目本地依赖，隔离环境，防止全局包干扰项目运行。
 | 原文链接：www.blog.ltkbj.cn/Article/details/759937.sHtML

原标题：golang mysql 时间类型选型避坑
简介：golang md5 sha 加密工具实现，实现 MD5、SHA 哈希工具，做数据摘要，用于签名校验场景。
 | 原文链接：www.blog.ltkbj.cn/Article/details/005456.sHtML

原标题：golang 系统设计消息队列 topic 设计原则梳理
简介：系统文件描述符上限调大，调高操作系统文件描述符上限，解决高并发场景打开文件报错。
 | 原文链接：www.blog.ltkbj.cn/Article/details/898922.sHtML

原标题：golang 系统设计消息队列解耦削峰
简介：golang gorm 索引设置与优化技巧，定义数据库索引，理解索引生效条件，避免索引失效慢查询。
 | 原文链接：www.blog.ltkbj.cn/Article/details/698541.sHtML

原标题：短信服务封装失败自动重试
简介：golang redis bitmap 位图业务实战，bitmap 做签到统计、用户状态标记，节省大量内存空间。
 | 原文链接：www.blog.ltkbj.cn/Article/details/261871.sHtML

原标题：坑点：gitpull冲突处理不当造成代码丢失
简介：gRPC 服务端客户端入门示例，搭建 gRPC 服务端与调用客户端，学习 protobuf 定义，掌握 RPC 基础开发流程。
 | 原文链接：www.blog.ltkbj.cn/Article/details/127452.sHtML

原标题：动态定时任务业务调度实现
简介：golang 限流熔断放在代理层实践，代理层统一限流熔断，对后端服务做流量保护。
 | 原文链接：www.blog.ltkbj.cn/Article/details/715997.sHtML

原标题：架构笔记：分库分表中间件选型业务约束
简介：慢查询分析索引调优数据库实战，抓取慢查询，分析执行计划，优化索引，解决数据库慢查询拖慢业务。
 | 原文链接：www.blog.ltkbj.cn/Article/details/110060.sHtML

原标题：实践：消息队列死信处理业务落地实践
简介：golang sftp 文件上传下载操作，sftp 协议远程文件上传下载，实现服务器之间文件传输功能。
 | 原文链接：www.blog.ltkbj.cn/Article/details/650460.sHtML

原标题：性能复盘：系统上下文切换过高性能下降调优
简介：Nginx 反向代理路由配置实战，配置 Nginx 反向代理，实现请求转发、路由分发，掌握 Nginx 基础配置能力。
 | 原文链接：www.blog.ltkbj.cn/Article/details/447105.sHtML

原标题：记一次日志切割脚本错误直接清空业务日志
简介：golang redis 事务 multi exec 使用，Redis 事务 multi exec 实现批量命令原子执行，理解 redis 事务隔离特性。
 | 原文链接：www.blog.ltkbj.cn/Article/details/005550.sHtML

原标题：golang 系统设计网络 io 模型 epoll 原理讲解
简介：全量回归测试提升代码质量，搭建全量回归测试集，版本发布执行回归测试，避免迭代引入旧 bug。
 | 原文链接：www.blog.ltkbj.cn/Article/details/486731.sHtML

原标题：开发复盘：批量任务进度持久化实现方案
简介：golang excel 简单读写操作示例，Go 实现 Excel 简单读写，业务数据导出 Excel 报表。
 | 原文链接：www.blog.ltkbj.cn/Article/details/538690.sHtML

五、性能优化｜Performance
仓库链接：
https://github.com/griffineric92/dokwsr/commit/027fd3721b9a61f80185783061fd0b1cf4c39b34

https://github.com/popekimberly6070/gcndud/commit/5a1cf73c6012886da3cb6fcacb8e16b46b7c4ff2

https://github.com/rodriguezmatthew5/vtzhkz/commit/697ab36d457c1452d5e0d6f4c65757c2812b6af3

https://github.com/woodsdennis5/ixfsfx/commit/ad32430b2d21c25befca7a2f91f40ec929886f15

https://github.com/woodnatalie531/wsunre/commit/99b0e025a16c138d888eb274533d4d5e8384744c

https://github.com/reyesvicki427/tfxinp/commit/bb7a7fbda128c80ef38079d648e8b14176ce3806

https://github.com/allencassandra0463/cvnbsx/commit/2b3b92b372ef3a9a0bf9be8baa63e77f8d0628d6

https://github.com/hernandezmicheal9930/kvpqqa/commit/7fa188ed05bf2e88b90acb425827f15295899042

https://github.com/lopezmatthew5/gnmqar/commit/7a54c40bceddfe7b2f2f0cf5e9c6e123bd7c6781

https://github.com/garciacindy6770/fidydu/commit/1d46239920288d356458668649d76bd5a24cdd96

https://github.com/campbellgwendolyn04/rcbwlz/commit/37c672f17627e58ac6a58b92f8f2cbdfa4a664c9

https://github.com/dyerwendy576/yrwibx/commit/da5c319a81763726f00458ac17228cc9ec9b9910

https://github.com/shannontracy562/dusahi/commit/8ac289e45df52c7f634f8193215bb840a9f965bb

https://github.com/vargasgary779/xgzyue/commit/1399901935a92a99734957d298f421e4100bcfc3


六、安全｜Security
代码仓库：
https://github.com/piercekevin7/xvuwgj/commit/246c367d564711e1f7f6a7352109b9edc5daad9a

https://github.com/thomaseileen4/tfblzb/commit/b47533ec2d261ebe15a7aa45a440b5703fa5374b

https://github.com/haynesbrittany91/atftev/commit/47d31391d732e23c32f448c09952ca1416abf4ff

https://github.com/humphreykyle58/rspshh/commit/f8e835fcad65a2c148848ff1035adcf19e66c6e9

https://github.com/franklinvalerie417/ghnktp/commit/5c542ba7c493d9cc9ce0172f1f32ac6f885d82c2

https://github.com/williamslynn4829/scpzcl/commit/c8343def65332346804088b4a96bc51b263fa04c

https://github.com/garrettjoy2/soaxuk/commit/1256d7c111884e8b6f9330120d89a18c0ea158ea

https://github.com/monroealexis97/ghcmqg/commit/10b8424d592fb917db4848d104bb06512b4b092c

https://github.com/griffineric92/dokwsr/commit/b3eb88d802560fb9f3ca459feb716946223278de

https://github.com/smithmichael8495/jmnjgj/commit/39e7c9f1bd34ba68a6fc71dad768063e8cf1e9cc

https://github.com/rodriguezmatthew5/vtzhkz/commit/e724ab35e312a322491bb47dce036f3fe08a98b8

https://github.com/dyerwendy576/yrwibx/commit/c8068ff457b5f7f71911934f5a3b439b5ef8b34b

https://github.com/humphreykyle58/rspshh/commit/af458473ef58863ac5d3d9aef74810543027e54e

https://github.com/griffineric92/dokwsr/commit/63d4f50169fe543f3c780f43e5cdd6edd6cc831d


七、DevOps｜运维部署
参考资料[1]：https://github.com/popekimberly6070/gcndud/commit/47ac5330cd4da006c3e7cd4c0c68d24667d6c8db

参考资料[2]：https://github.com/garrettjoy2/soaxuk/commit/7a1d15e77c8d6c74901cd5066a9c58e43fd3a2bf

参考资料[3]：https://github.com/haynesbrittany91/atftev/commit/76c8e32f3fbe7a3eff07be591c686a26bb8f6517

参考资料[4]：https://github.com/piercekevin7/xvuwgj/commit/2e7b54ce60042111b7c0298df64fffd2fc4a4472

参考资料[5]：https://github.com/monroealexis97/ghcmqg/commit/65de20c2d8c60016ddd7f66945746754109f037f


八、开源、效率、AI、总结复盘
开源资料：https://github.com/carrbrian51/fsxudt/commit/271b59f5238c3f78c56d4df80e671227024122c6

开源资料：https://github.com/thomaseileen4/tfblzb/commit/f207826e115cd0d7b003597c9baaeac365efc6e3

开源资料：https://github.com/humphreykyle58/rspshh/commit/26448f423865b7007da11cf198b881513cc0459f

开源资料：https://github.com/woodsdennis5/ixfsfx/commit/44c5c4ea741f569c6675ea0030782ea18469ed1e

开源资料：https://github.com/lewisrobert902/dfpzmg/commit/720c7ef9130e44cfaf73bd38b8098d8c37f44fce

开源资料：https://github.com/reyesvicki427/tfxinp/commit/f4349f3d706c6e77cf8ef71e378254c9564bcfcc

开源资料：https://github.com/smithmichael8495/jmnjgj/commit/33ee1bfbf5b0288b21d28d813cc091bc452a183f

开源资料：https://github.com/garrettjoy2/soaxuk/commit/3c6fd4606f63470d5221fac4d625840c792f1ee1

开源资料：https://github.com/frederickcynthia322/sluyfj/commit/597e8132abc3c2282e5fec4f94a9086fb835a4e3


*数据更新时间：2026年08月24日03时18分25秒(UTC+8)*
*数据采集自，GitHub README、Issues、Blog、技术文档、项目 Wiki，包含：教程、踩坑、实战、架构、性能、部署、排错、最佳实践、复盘、迁移、重构、安全、运维、前端、后端、云原生、AI、效率工具。*
